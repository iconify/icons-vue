<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yls1qbbvq"/><path class="bi9x9vb5f"/><circle class="urn-e0b9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pencil-sharpener" /></template>
<style>
.bi9x9vb5f {
  d: path("M12 10.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3M6.75 17h10.5m-14.5-5h4m10.5-1H20V5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urn-e0b9r {
  cx: 20px;
  cy: 4px;
  r: 1.25px;
}

.yls1qbbvq {
  width: 10.5px;
  height: 13.5px;
  x: 6.75px;
  y: 7.75px;
  rx: 2.5px;
}

</style>
