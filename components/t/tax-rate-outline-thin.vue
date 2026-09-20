<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jd_dotbnq"/><path class="kq98nmbqp"/><path class="pm5zs9u8l"/><path class="y4a8ig_7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tax-rate-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

.kq98nmbqp {
  d: path("M8.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pm5zs9u8l {
  d: path("m8.5 13.5 7 -7");
}

.y4a8ig_7t {
  d: path("M13.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
