<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="obqscbcxp"/><path class="r0va9zsfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.obqscbcxp {
  stroke-opacity: 0.4;
  d: path("M3 21h18");
}

.r0va9zsfm {
  d: path("m17 12l-2-2l.884-5.303A1.37 1.37 0 0 0 15.5 3.5a.613.613 0 0 0-.924.066L12 7l-2-1V4.707c0-.453-.18-.887-.5-1.207a.707.707 0 0 0-1 0l-3 3a.707.707 0 0 0 0 1c.32.32.754.5 1.207.5H8l1 2l-3.434 2.576a.613.613 0 0 0-.066.924c.314.314.76.457 1.197.384L12 13l2 2c2 2 3 2 4 1s1-2-1-4");
}

</style>
