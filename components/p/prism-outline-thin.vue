<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sojjg40ea"/><path class="l3yb7ybjz"/><path class="kz82t0nla"/><path class="gy18-zqeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prism-outline-thin" /></template>
<style>
.gy18-zqeb {
  d: path("M14 19h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz82t0nla {
  d: path("M14 15h7");
}

.l3yb7ybjz {
  d: path("M2 9h6");
}

.sojjg40ea {
  d: path("m12 5 7 7H5Z");
}

</style>
