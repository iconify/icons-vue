<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwckntp7w"/><path class="k8h2edcbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:police-tourist" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8h2edcbz {
  d: path("m12 8l.123.307a1.5 1.5 0 0 0 1.393.943h.234a.47.47 0 0 1 .309.823l-.333.291a1.5 1.5 0 0 0-.449 1.56l.098.326a.47.47 0 0 1-.711.526l-.332-.221a1.5 1.5 0 0 0-1.664 0l-.332.221a.47.47 0 0 1-.711-.526l.098-.326a1.5 1.5 0 0 0-.449-1.56l-.333-.291a.47.47 0 0 1 .309-.823h.234a1.5 1.5 0 0 0 1.393-.943L11 8a.539.539 0 0 1 1 0m6 13.75c-2-2-3-3.5-3-4.75a3 3 0 0 1 6 0c0 1.25-1 2.75-3 4.75M18 17h.01");
}

.pwckntp7w {
  d: path("M13.374 20.543q-.9.525-1.874.957c-4.5-2-8-5.5-8-10.5V5.25l8-2.75l8 2.75V11q0 .208-.008.412");
}

</style>
