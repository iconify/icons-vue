<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tbvnr3bhy"/><rect class="cgtz95h4q"/><path class="x8ck8abqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:petition" /></template>
<style>
.cgtz95h4q {
  width: 6px;
  height: 2.5px;
  x: 9px;
  y: 2.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tbvnr3bhy {
  width: 14.5px;
  height: 16px;
  x: 4.75px;
  y: 5.25px;
  rx: 2px;
}

.x8ck8abqi {
  d: path("M8.25 9.5h7.5m-7.5 3.25h7.5m-7.5 4.75c.75-1.5 1.5-1.5 2 0s1.25 1.5 2 0s1.5-1.5 2 0l1.5-.5");
}

</style>
