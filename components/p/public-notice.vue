<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="at4zutbux"/><path class="ob0tszt2t"/><rect class="oyd2sjbrn"/><path class="d5kfdtb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:public-notice" /></template>
<style>
.at4zutbux {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

.d5kfdtb5m {
  d: path("M10.25 8.25h3.5m-3.5 2.25h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ob0tszt2t {
  d: path("M6.5 15.25v6m11-6v6");
}

.oyd2sjbrn {
  width: 7.5px;
  height: 7px;
  x: 8.25px;
  y: 5.75px;
  rx: 1px;
}

</style>
