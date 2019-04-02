The package `ElectricalEngineering.isy` provides electrical engineering circuits components for
[IPE](http://ipe.otfried.org/).

To start IPE from the command line with `ElectricalEngineering.isy` use: `/usr/bin/ipe -sheet /path_to/ElectricalEngineering.isy`, where `path_to` represents the absolute path of the file `ElectricalEngineering.isy`. Alternatively one can create start script (in Linux):

```bash
#!/bin/bash
/usr/bin/ipe -sheet /path_to/ElectricalEngineering.isy $*
```
## Example

### Induction machine

- Stored in `Resources/InductionMachine.ipe`

![Induction machine](https://raw.githubusercontent.com/christiankral/ElectricalEngineering.isy/master/Resources/png/InductionMachine.png?raw=true)

### Transformer

- Stored in `Resources/Transformer.ipe`

![Transformer](https://raw.githubusercontent.com/christiankral/ElectricalEngineering.isy/master/Resources/png/Transformer.png?raw=true)


## Circuit components

- Basic
  - Capacitor
  - Diode
  - Inductor
  - IGBT
  - Ground
  - Resistor
  - Switch open/close
  - Thyrisotor
  - Transistor
  - Winding
- Arrows
  - Current arrows
  - Curved arrow line
- Sources
  - Current source
  - Voltage source
- Machines
  - Three phase
  - Transformer