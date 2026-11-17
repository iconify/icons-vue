<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y37g5en_y"/><path class="zw3b81pam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.y37g5en_y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 12c2 2 2 3 1 4s-2 1-4-1l-2-2l-5.303.884A1.37 1.37 0 0 1 5.5 13.5a.61.61 0 0 1 .066-.924L9 10L8 8H6.707c-.453 0-.887-.18-1.207-.5a.707.707 0 0 1 0-1l3-3a.707.707 0 0 1 1 0c.32.32.5.754.5 1.207V6l2 1l2.576-3.434A.61.61 0 0 1 15.5 3.5c.314.314.457.76.384 1.197L15 10Z");
}

.zw3b81pam {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 12l-2-2l.884-5.303A1.37 1.37 0 0 0 15.5 3.5a.613.613 0 0 0-.924.066L12 7l-2-1V4.707c0-.453-.18-.887-.5-1.207a.707.707 0 0 0-1 0l-3 3a.707.707 0 0 0 0 1c.32.32.754.5 1.207.5H8l1 2l-3.434 2.576a.613.613 0 0 0-.066.924c.314.314.76.457 1.197.384L12 13l2 2c2 2 3 2 4 1s1-2-1-4M3 21h18");
}

</style>
