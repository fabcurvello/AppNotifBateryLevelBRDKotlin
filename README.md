# App Notificação de Nível de Bateria (Kotlin)

> Repositório didático: exercício prático de Android nativo com **Kotlin**, desenvolvido e aplicado em sala de aula pelo Prof. Fabricio Curvello.

## Sobre o projeto

Aplicativo que mostra uma **notificação com o nível da bateria** sempre que ele muda.

## Contexto acadêmico

Exercício aplicado em sala de aula, usado como prática guiada com os alunos.

## Versão em Java

Esta mesma aplicação também foi desenvolvida em **Java**: [AppNotifBateryLevelBRDJava](https://github.com/fabcurvello/AppNotifBateryLevelBRDJava). Comparar as duas versões lado a lado ajuda a entender as diferenças de sintaxe entre Java e Kotlin no Android.

## O que o app faz

- Registra um `BroadcastReceiver` para `ACTION_BATTERY_CHANGED`.
- A cada mudança, lê o nível da bateria (`BatteryManager.EXTRA_LEVEL`).
- Cria um canal de notificação (Android 8+) e mostra uma notificação com a porcentagem atual da bateria.

## Conceitos trabalhados em aula

- `BroadcastReceiver` registrado dinamicamente
- **Notificações**: `NotificationChannel`, `NotificationCompat.Builder` e `NotificationManager`
- Permissão `POST_NOTIFICATIONS`
- Leitura de dados extras de um broadcast do sistema
- *String templates* em Kotlin

## Tecnologias

- **Kotlin**
- **Android SDK** (Android Studio)
- **Gradle**
- `minSdk 28` / `compileSdk 34`

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabcurvello/AppNotifBateryLevelBRDKotlin.git
   ```
2. Abra a pasta no **Android Studio** e aguarde a sincronização do Gradle.
3. Execute em um emulador ou dispositivo físico com Android compatível com a API 28 ou superior.

## Veja também

Outros repositórios de aula com o mesmo tema:

- [AppBroadcastReceiversJava](https://github.com/fabcurvello/AppBroadcastReceiversJava)
- [AppDetectBatteryLowDBRJava](https://github.com/fabcurvello/AppDetectBatteryLowDBRJava)
- [AppDetectBatteryLowDBRKotlin](https://github.com/fabcurvello/AppDetectBatteryLowDBRKotlin)
- [AppDetectChargeDBRJava](https://github.com/fabcurvello/AppDetectChargeDBRJava)
- [AppDetectChargeDBRKotlin](https://github.com/fabcurvello/AppDetectChargeDBRKotlin)
- [AppNotifBateryLevelBRDJava](https://github.com/fabcurvello/AppNotifBateryLevelBRDJava)
- [AppNotifBootCompletedBREJAVA](https://github.com/fabcurvello/AppNotifBootCompletedBREJAVA)
- [AppNotifBootCompletedBREKotlin](https://github.com/fabcurvello/AppNotifBootCompletedBREKotlin)

## Autor

**Fabricio Curvello**: professor de desenvolvimento de software no SENAI-RJ (desde 1997) e em faculdades do grupo Ânima Educação (IBMR e UNA).

- GitHub: [github.com/fabcurvello](https://github.com/fabcurvello)
- LinkedIn: [linkedin.com/in/fabriciocurvello](https://www.linkedin.com/in/fabriciocurvello)
- YouTube: [@fabriciocurvello](https://www.youtube.com/@fabriciocurvello)
