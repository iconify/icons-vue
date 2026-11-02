<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d807uab4r"/><path class="j_psw1y4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-user-duocolor-sharp" /></template>
<style>
.d807uab4r {
  stroke-opacity: 0.4;
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0M7 21c0-2.21 2.239-4 5-4s5 1.79 5 4");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
