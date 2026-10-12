<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b4f9xvn3u"/><path class="p4qajlb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:protractor" /></template>
<style>
.b4f9xvn3u {
  d: path("M2.75 16.25a9.25 9.25 0 0 1 18.5 0v1a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1Zm9.25-7v2m4.95.05l-1.41 1.41M7.05 11.3l1.41 1.41");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4qajlb3l {
  d: path("M9.25 18.25v-2a2.75 2.75 0 0 1 5.5 0v2");
}

</style>
