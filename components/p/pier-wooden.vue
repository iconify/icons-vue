<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cz8qrt41v"/><path class="jt2g_kuaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pier-wooden" /></template>
<style>
.cz8qrt41v {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt2g_kuaa {
  d: path("M8.75 7.25v3.5m6.5-3.5v3.5m-9.75 0v10.5m6.5-10.5v10.5m6.5-10.5v10.5m-15.75-5c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

</style>
