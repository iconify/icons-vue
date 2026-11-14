<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kyjqjhbxq"/><path class="itga-mwsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-multiple-tills" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itga-mwsf {
  d: path("M9 5v-.5a2 2 0 0 1 2-2h8.5a2 2 0 0 1 2 2V8a2 2 0 0 1-2 2h-4m2.25 0v9m-2 0h4A1.25 1.25 0 0 1 21 20.25a1.25 1.25 0 0 1-1.25 1.25h-4a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 15.75 19m-10.5-8.75h4m-4 2.5h5.5");
}

.kyjqjhbxq {
  d: path("M5.563 7h4.875a3.063 3.063 0 0 1 3.062 3.063v1.875A3.063 3.063 0 0 1 10.438 15H5.563A3.063 3.063 0 0 1 2.5 11.938v-1.875A3.063 3.063 0 0 1 5.563 7M8 15v4m-2.75 0h5.5A1.25 1.25 0 0 1 12 20.25a1.25 1.25 0 0 1-1.25 1.25h-5.5A1.25 1.25 0 0 1 4 20.25A1.25 1.25 0 0 1 5.25 19");
}

</style>
