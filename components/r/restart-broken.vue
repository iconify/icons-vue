<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbzbqg9av"/><path class="x1vm6db2y"/><path class="xsb0bgv9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vbzbqg9av {
  d: path("M19.7285 10.9283C20.4412 13.5973 19.7507 16.563 17.6568 18.6568C15.1798 21.1339 11.4825 21.647 8.49997 20.1961");
}

.x1vm6db2y {
  d: path("M18.364 8.05026L17.6568 7.34315M14.1213 8.05026H18.364V3.80762");
}

.xsb0bgv9z {
  d: path("M5.75374 17.9995C3.23316 14.8583 3.42963 10.2567 6.34315 7.34315C9.46734 4.21895 14.5327 4.21895 17.6569 7.34315");
}

</style>
