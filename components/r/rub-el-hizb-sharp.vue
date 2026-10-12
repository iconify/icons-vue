<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bog22wb6w"/><path class="huo2d3hyt"/><circle class="gp0egaclj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rub-el-hizb-sharp" /></template>
<style>
.bog22wb6w {
  d: path("M6.8 5.8h11.4v12.4H5.8V5.8z");
}

.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.huo2d3hyt {
  d: path("m12.71 3.96l7.33 7.33l.71.71l-.71.71l-7.33 7.33l-.71.71l-.71-.71l-7.33-7.33l-.71-.71l.71-.71l7.33-7.33l.71-.71z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
