# DAY 1: Basic GPIO & UART Execution

- **Platform:** STM32 NUCLEO (Simulated in Wokwi)
- **Features:** Toggled PA5 output pin using `HAL_GPIO_TogglePin()` and transmitted serial data over UART2.
- **Interactive Simulation:** (Run Day 1 in Wokwi)[https://wokwi.com/projects/477114062409128961]

## Code Snippet
```c
while (1) {
    HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_5);
    HAL_Delay(500);
}
