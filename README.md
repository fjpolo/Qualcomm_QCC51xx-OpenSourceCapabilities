# Qualcomm_QCC51xx-OpenSourceCapabilities


## About

The idea of this repository is to have a place to learn Kalimba architecture and assembly, while applying it real DSP code. 

## Integrating capabilities

Instructions on how and where to integrate the capability, as well as how to instantiate the operator, should be included in the dir `<CapabilityName>/IntegrationGuide<CapabilityName>.md`

## Programming "rules" 

`API` naming should be following this rule: `<OpenSourceQCC>_<CapabilityName>_<APINameDescriptor>();`
    - eg: 
      - `OpenSourceQCC_IIRBiquadFilter_init(uint32_t sample_rate)`
      - `OpenSourceQCC_IIRBiquadFilter_process(int8_t* data_p, uint32_t data_size)`
      - `OpenSourceQCC_IIRBiquadFilter_deinit(void)`