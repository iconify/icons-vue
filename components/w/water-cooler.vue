<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a7jz21n5d"/><rect class="a5-5u49il"/><path class="tcrk49udm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-cooler" /></template>
<style>
.a5-5u49il {
  width: 12.5px;
  height: 10px;
  x: 5.75px;
  y: 11.25px;
  rx: 2px;
}

.a7jz21n5d {
  d: path("M10.75 11.25v-.75c0-.8-.5-1.2-1.4-1.6C8 8.3 7.25 7.5 7.25 6V4.25a1.5 1.5 0 0 1 1.5-1.5h6.5a1.5 1.5 0 0 1 1.5 1.5V6c0 1.5-.75 2.3-2.1 2.9c-.9.4-1.4.8-1.4 1.6v.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tcrk49udm {
  d: path("M8.75 18.25V15a1 1 0 0 1 1-1h4.5a1 1 0 0 1 1 1v3.25ZM10.5 14v1.25m3-1.25v1.25");
}

</style>
