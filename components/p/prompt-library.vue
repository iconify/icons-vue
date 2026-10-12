<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg22wlw7i"/><rect class="rgzamlbej"/><path class="h6h5yxboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prompt-library" /></template>
<style>
.h6h5yxboh {
  d: path("m6.25 12.5l2.25 2.25L6.25 17m4.5 0h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg22wlw7i {
  d: path("M6.25 5.25h12.5a2.5 2.5 0 0 1 2.5 2.5v9.5");
}

.rgzamlbej {
  width: 15px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 2.5px;
}

</style>
