<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lfpfczh4t"/><path class="zl3fw2elx"/><path class="lywtx37wy"/><path class="y-uxy98jv"/><path class="mk09shb8p"/><path class="t-j_eedxl"/><path class="dziiqebqk"/><path class="u0vfu357j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-columns-split-linear" /></template>
<style>
.dziiqebqk {
  d: path("M21.9918 2.00891C19.5201 2.04522 18.1175 2.23012 17.176 3.17161C16.0044 4.34318 16.0044 6.2288 16.0044 10L16.0044 14C16.0044 17.7713 16.0044 19.6569 17.176 20.8285C18.1183 21.7708 19.5227 21.9552 21.9987 21.9913");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfpfczh4t {
  d: path("M2 15.333L11 15.333");
}

.lywtx37wy {
  d: path("M5 2.00879L5 21.9914");
}

.mk09shb8p {
  d: path("M2 2L3 2C6.77124 2 8.65685 2 9.82843 3.17157C11 4.34315 11 6.22876 11 10L11 14C11 17.7712 11 19.6569 9.82843 20.8284C8.65685 22 6.77124 22 3 22L2 22");
}

.t-j_eedxl {
  d: path("M21.9985 15.333L16.0043 15.333");
}

.u0vfu357j {
  d: path("M21.9941 8.6665L16.0043 8.6665");
}

.y-uxy98jv {
  d: path("M13.5 2.00879V3.67267M13.5 20.3502V22.014M13.5 7.00269V10.3488M13.5 13.66V17.0062");
}

.zl3fw2elx {
  d: path("M2 8.6665L11 8.6665");
}

</style>
