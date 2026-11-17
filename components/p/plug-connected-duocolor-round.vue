<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l_td3lbam"/><path class="b8ni2bcki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-connected-duocolor-round" /></template>
<style>
.b8ni2bcki {
  d: path("m6 12l6 6a4.243 4.243 0 0 1-6-6m12 0l-6-6a4.243 4.243 0 0 1 6 6M6 18l-3 3M18 6l3-3");
}

.l_td3lbam {
  stroke-opacity: 0.4;
  d: path("m11 17l3-3m-7-1l3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
