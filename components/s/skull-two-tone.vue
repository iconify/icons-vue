<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-hw114bt"/><path class="qud-iqc7y"/><path clip-rule="evenodd" class="wdmb74bkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skull-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-hw114bt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 18.1414C3.0812 16.2606 2 13.6868 2 11C2 5.4772 6.4772 1 12 1C17.5228 1 22 5.4772 22 11C22 13.6868 20.9188 16.2606 19 18.1414L19 20C19 21.6569 17.6569 23 16 23L8 23C6.3431 23 5 21.6569 5 20L5 18.1414Z");
  stroke: none;
}

.qud-iqc7y {
  d: path("M5.7 17.4273C3.9731 15.7346 3 13.4182 3 11C3 6.0294 7.0294 2 12 2C16.9706 2 21 6.0294 21 11C21 13.4182 20.0269 15.7346 18.3 17.4273C18.1081 17.6154 18 17.8727 18 18.1414L18 20C18 21.1046 17.1046 22 16 22L8 22C6.8954 22 6 21.1046 6 20L6 18.1414C6 17.8727 5.8919 17.6154 5.7 17.4273ZM10 22L10 20M14 22L14 20M10.75 16L12 14L13.25 16");
}

.wdmb74bkm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 11C10 11.8284 9.3284 12.5 8.5 12.5C7.6716 12.5 7 11.8284 7 11C7 10.1716 7.6716 9.5 8.5 9.5C9.3284 9.5 10 10.1716 10 11ZM17 11C17 11.8284 16.3284 12.5 15.5 12.5C14.6716 12.5 14 11.8284 14 11C14 10.1716 14.6716 9.5 15.5 9.5C16.3284 9.5 17 10.1716 17 11Z");
  stroke: none;
}

</style>
