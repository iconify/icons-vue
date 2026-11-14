<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lz0u3l3nd"/><path class="wyli5loxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mixed-use-building" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lz0u3l3nd {
  d: path("M4.5 12.75V4A1.5 1.5 0 0 1 6 2.5h12A1.5 1.5 0 0 1 19.5 4v8.75m-15.5 0h16a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5m.5 3v5.75h15v-5.75m-11.25-3v3m3.75-3v3m3.75-3v3m-8-9.25H9m2.5 0h1m2.5 0h1.25m-8.5 3H9m2.5 0h1m2.5 0h1.25");
}

.wyli5loxo {
  d: path("M10.5 21.5v-3h3v3");
}

</style>
