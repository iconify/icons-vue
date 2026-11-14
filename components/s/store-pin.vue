<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lml33hbwb"/><path class="syy6wabtn"/><path class="w7x-9fxsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-pin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lml33hbwb {
  d: path("m3.579 6.569l.6-2A1.5 1.5 0 0 1 5.616 3.5h12.768a1.5 1.5 0 0 1 1.437 1.069l.6 2A1.5 1.5 0 0 1 18.984 8.5H5.016a1.5 1.5 0 0 1-1.437-1.931");
}

.syy6wabtn {
  d: path("M4.5 8.5V21h15V8.5m-10-5l-.5 5m5.5-5l.5 5");
}

.w7x-9fxsn {
  d: path("M12 18.25c-1.75-1.5-2.75-3-2.75-4.25a2.75 2.75 0 0 1 5.5 0c0 1.25-1 2.75-2.75 4.25");
}

</style>
