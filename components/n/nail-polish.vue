<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xgpihqbae"/><rect class="oc8ukib0y"/><path class="j54qjsbwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nail-polish" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j54qjsbwj {
  d: path("M9.25 16.5h5.5");
}

.oc8ukib0y {
  width: 11.5px;
  height: 9.5px;
  x: 6.25px;
  y: 11.75px;
  rx: 2.5px;
}

.xgpihqbae {
  width: 5px;
  height: 6.5px;
  x: 9.5px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
