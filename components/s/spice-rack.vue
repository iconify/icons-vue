<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o6iengbhb"/><rect class="lba74vbfn"/><rect class="xh_mtsbxf"/><path class="hhy_4mb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spice-rack" /></template>
<style>
.hhy_4mb8e {
  d: path("M6.5 7.5h3m5 0h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lba74vbfn {
  width: 5px;
  height: 10px;
  x: 5.5px;
  y: 10.25px;
  rx: 1.5px;
}

.o6iengbhb {
  d: path("M2.75 3.25v18m18.5-18v18m-18.5-1h18.5");
}

.xh_mtsbxf {
  width: 5px;
  height: 10px;
  x: 13.5px;
  y: 10.25px;
  rx: 1.5px;
}

</style>
