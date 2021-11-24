# Ring Light
Control the elgato ring light

## Setup
### Dependencies
`pip install eglight`

`pip install click`

### Exporting your light ip (Non-discovery mode)
`echo 'export ELGATO_RING_LIGHT_IP=THE_IP_ADDRESS >> ~/.your_shell_file`

`echo 'export ELGATO_RING_LIGHT_IP=192.168.0.2 >> ~/.bash_profile`

### Download
`curl https://raw.githubusercontent.com/kinncj/ringlight/main/elgato > ~/.elgato`

`chmod +x ~/.elgato`

## Commands
- brightness
  - Sets the brightness
  - `~/.elgato brightness 12`
- temperature
  - Sets the temperature
  - `~/.elgato temperature 6900`
- toggle
  - Toggle ON/OFF
  - `~/.elgato toggle`

### Extras

Usage with StreamDeck

- Download and setup [stresmdeck-ui](https://timothycrosley.github.io/streamdeck-ui/)
- Configure the python script as in the screenshot:
   - ![streamdeck](https://user-images.githubusercontent.com/292542/143156253-4efe79d0-b7b9-4a4e-94a7-f19b4e2467e5.png)
