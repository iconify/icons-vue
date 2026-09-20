<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="iynk9engs"/><path class="dli4mgb8q"/><path class="n03v90rrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multimodal-prompt-outline-regular" /></template>
<style>
.dli4mgb8q {
  d: path("M14 9h4");
}

.iynk9engs {
  d: path("m5 13.5 4 -4 4 4");
}

.jq9hovbrs {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.n03v90rrh {
  d: path("M14 12.5h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yomctlb4k {
  d: path("M7 17v4l4 -4");
}

</style>
