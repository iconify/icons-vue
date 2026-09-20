<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="eitn-4bdu"/><path class="hd9_jzcmb"/><path class="dcp8edcqu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:metfi-background" /></template>
<style>
.dcp8edcqu {
  fill: var(--svg-color--000, #000);
  d: path("M15.765 11.75v6.42c0 .494-.433.889-.941.889c-.509 0-.942-.395-.942-.89v-5.698a.455.455 0 0 0-.47-.47a.455.455 0 0 0-.47.47v2.875c0 .494-.537.89-.942.89s-.941-.424-.941-.909v-2.87c0-.264-.193-.457-.47-.457c-.278 0-.471.193-.471.461v5.76c0 .494-.433.838-.941.838c-.509 0-.942-.395-.942-.89v-6.446c0-1.666 1.685-3.017 3.765-3.017c1.774 0 3.784 1.148 3.765 3.045");
}

.eitn-4bdu {
  fill: var(--svg-color--77fcd1, #77fcd1);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hd9_jzcmb {
  fill: var(--svg-color--000, #000);
  d: path("M12 6.353c-3.614 0-6.588 2.937-6.588 6.278a.75.75 0 0 1-.744.781c-.423 0-.668-.348-.668-.781c0-4.292 3.624-7.69 8-7.69c4.377 0 8 3.398 8 7.69c0 .433-.245.781-.668.781a.753.753 0 0 1-.744-.781c0-3.341-2.974-6.278-6.588-6.278");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
