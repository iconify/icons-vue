<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r35682biw"/><path class="kdjsicbpv"/><path class="lip701r7h"/><path class="aoyq_1bnw"/><path class="lqiw_3bos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quote-reply-outline-regular" /></template>
<style>
.aoyq_1bnw {
  d: path("M10 9h7");
}

.kdjsicbpv {
  d: path("M7 16v3l3 -3");
}

.lip701r7h {
  d: path("M7 7v6");
}

.lqiw_3bos {
  d: path("M10 12h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r35682biw {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
