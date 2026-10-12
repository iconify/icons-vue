<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xqm19zbyf"/><path class="kzuym2bho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:math" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzuym2bho {
  d: path("M6.25 9.5h3.5M8 7.75v3.5m4.75-2.75h5m-5 2.25h5M12 16.25v5m-3.5 0h7");
}

.xqm19zbyf {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
