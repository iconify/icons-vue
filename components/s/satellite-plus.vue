<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z1tcsbb0h"/><path class="kzfshtbfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:satellite-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzfshtbfx {
  d: path("m4.929 15.536l2.121-2.122a1.5 1.5 0 0 1 2.122 0l1.414 1.414a1.5 1.5 0 0 1 0 2.122l-2.122 2.121a1.5 1.5 0 0 1-2.121 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.121m8.485-8.486l2.122-2.121a1.5 1.5 0 0 1 2.121 0l1.414 1.414a1.5 1.5 0 0 1 0 2.121l-2.121 2.122a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122M5.636 5.636a3 3 0 0 1 4.243 4.243M18 15v6m-3-3h6");
}

.z1tcsbb0h {
  d: path("m8.995 10.763l1.768-1.768a1.75 1.75 0 0 1 2.474 0l1.768 1.768a1.75 1.75 0 0 1 0 2.474l-1.768 1.768a1.75 1.75 0 0 1-2.474 0l-1.768-1.768a1.75 1.75 0 0 1 0-2.474");
}

</style>
