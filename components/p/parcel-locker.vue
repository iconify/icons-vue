<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hoi44xq4a"/><path class="g7gikz6ze"/><rect class="buevg_brm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parcel-locker" /></template>
<style>
.buevg_brm {
  width: 4.25px;
  height: 4.5px;
  x: 14.5px;
  y: 5.25px;
  rx: 0.75px;
}

.g7gikz6ze {
  d: path("M12 2.75v18.5M2.75 9H12m-9.25 6H12m0-2.25h9.25m-11.75-7v.5m0 5.5v.5m0 5.5v.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hoi44xq4a {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
