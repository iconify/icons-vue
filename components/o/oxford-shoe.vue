<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nealgx4zf"/><path class="ozzmphbdl"/><rect class="fq13zebzr"/><path class="rkb3fybzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oxford-shoe" /></template>
<style>
.fq13zebzr {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 17.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nealgx4zf {
  d: path("M3.25 14.75V6.5a1 1 0 0 1 1.25-1l3.25.75C8.25 7.75 9.5 8.5 11 8.5h1.5l5.3 2.15c2.2.9 3.45 2.1 3.45 4.1ZM12.5 9l-.75 1.5M15 10l-.75 1.5");
}

.ozzmphbdl {
  d: path("M17.5 11c-.75 1-.75 2.75 0 3.5");
}

.rkb3fybzo {
  d: path("M8.25 18.25v2.5");
}

</style>
