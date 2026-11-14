<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mie9b5bhx"/><path class="ln_ikth2q"/><path class="xuv-p6wvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marketing-automation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ln_ikth2q {
  d: path("m4.5 3.5l3 .75L6.75 7m2 1.5h6.5A1.75 1.75 0 0 1 17 10.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 13.75v-3.5A1.75 1.75 0 0 1 8.75 8.5");
}

.mie9b5bhx {
  d: path("M4.206 7.5a9 9 0 1 1 0 9");
}

.xuv-p6wvo {
  d: path("M7.25 9.25L12 12.5l4.75-3.25");
}

</style>
