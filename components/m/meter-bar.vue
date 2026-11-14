<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zjq2zngzk"/><path class="ywyqoqb2h"/><path class="qv8s9kl7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meter-bar" /></template>
<style>
.qv8s9kl7k {
  d: path("M3.5 16.5v3m4.5-3v2m4-2v3m4-3v2m4.5-2v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywyqoqb2h {
  fill: currentColor;
  d: path("M4.5 8.5H15V11H4.5Z");
}

.zjq2zngzk {
  d: path("M3.75 6h16.5A1.75 1.75 0 0 1 22 7.75v4a1.75 1.75 0 0 1-1.75 1.75H3.75A1.75 1.75 0 0 1 2 11.75v-4A1.75 1.75 0 0 1 3.75 6Z");
}

</style>
