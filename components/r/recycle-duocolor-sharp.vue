<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dhioohpaz"/><path class="xt74fg1oh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-duocolor-sharp" /></template>
<style>
.dhioohpaz {
  stroke-opacity: 0.4;
  d: path("M6.34 18h-3L8.4 9.235m1.098 4.098L8.4 9.235l-4.098 1.098");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xt74fg1oh {
  d: path("M10.5 5.598L12 3l5.06 8.765m-4.098-1.098l4.098 1.098l1.098-4.098m1.002 7.735L20.66 18H10.54m3-3l-3 3l3 3");
}

</style>
