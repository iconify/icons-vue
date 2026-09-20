<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="edr2cqsrt"/><path class="juej44_6j"/><path class="yih0nfb7c"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pull-refresh-outline-regular" /></template>
<style>
.edr2cqsrt {
  d: path("M9.5 3 12 5.5 14.5 3");
}

.juej44_6j {
  d: path("M9.5 7.5 12 10l2.5 -2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.yih0nfb7c {
  d: path("M3 14h18");
}

</style>
