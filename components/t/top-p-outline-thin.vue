<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yam3-1b2z"/><path class="sl7vxjbhd"/><path class="pt73j1ikv"/><path class="xa3jgydgh"/><path class="g620qibmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-p-outline-thin" /></template>
<style>
.g620qibmn {
  d: path("M20 17v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pt73j1ikv {
  d: path("M15 14v6");
}

.sl7vxjbhd {
  d: path("M10 11v9");
}

.xa3jgydgh {
  d: path("M3 12h9");
}

.yam3-1b2z {
  d: path("M5 8v12");
}

</style>
