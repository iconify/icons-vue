<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2mmqxbdr"/><rect class="fl_-5p0zs"/><rect class="jqyvi1bbu"/><rect class="fq5dzg2ve"/><rect class="xl_slmblv"/><rect class="by2zr3vuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:polygon-tool" /></template>
<style>
.by2zr3vuo {
  width: 3px;
  height: 3px;
  x: 3.75px;
  y: 15.75px;
  rx: 0.5px;
}

.fl_-5p0zs {
  width: 3px;
  height: 3px;
  x: 3.5px;
  y: 5.5px;
  rx: 0.5px;
}

.fq5dzg2ve {
  width: 3px;
  height: 3px;
  x: 18.25px;
  y: 9.5px;
  rx: 0.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqyvi1bbu {
  width: 3px;
  height: 3px;
  x: 12px;
  y: 2.75px;
  rx: 0.5px;
}

.p2mmqxbdr {
  d: path("m6.84 6.4l4.82-1.55m3.48 1.17l2.97 3.21m.95 3.62l-1.87 5.05m-2.64 1.42L7.2 17.68m-2-2.34l-.15-6.43");
}

.xl_slmblv {
  width: 3px;
  height: 3px;
  x: 15px;
  y: 18.25px;
  rx: 0.5px;
}

</style>
