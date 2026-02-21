A Microwakeword for use with EspHome (Homeassistant) inspired by the the movie Fifth Element opening scene.

Where the professor yells: "Aziz Light"

in your EspHome YAML file include:

```
micro_wake_word:
  id: mww
  models:
    - model: https://raw.githubusercontent.com/olterman/MicroWakeWord-Assiss/refs/heads/main/assis.json
      id: jemmah
      probability_cutoff: 0.98
      sliding_window_size: 7   
``` 
