<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jyg8v47hd"/><path class="p-qnklbzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:screen-cast" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyg8v47hd {
  d: path("M6.5 17.25H5.25a2.5 2.5 0 0 1-2.5-2.5v-8.5a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v8.5a2.5 2.5 0 0 1-2.5 2.5H17.5");
}

.p-qnklbzu {
  d: path("m12.54 15.34l2.92 4.57q.54.84-.46.84H9q-1 0-.46-.84l2.92-4.57q.54-.84 1.08 0");
}

</style>
