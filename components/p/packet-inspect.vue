<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xazz_lb4s"/><path class="a8keexbaw"/><circle class="rzdlp7b7j"/><path class="k-7o9iach"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:packet-inspect" /></template>
<style>
.a8keexbaw {
  d: path("M6.25 2.75v4h4.25v-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-7o9iach {
  d: path("m19.3 19.3l1.95 1.95");
}

.rzdlp7b7j {
  cx: 17px;
  cy: 17px;
  r: 3.25px;
}

.xazz_lb4s {
  width: 11.25px;
  height: 11.25px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
