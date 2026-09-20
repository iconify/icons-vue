<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzrnw0b2n"/><path class="a9nj5hbth"/><path class="v7bs_s3tb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:package-outline-thin" /></template>
<style>
.a9nj5hbth {
  d: path("M4 11h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7bs_s3tb {
  d: path("M12 6v5");
}

.wzrnw0b2n {
  d: path("M14 6h3a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

</style>
