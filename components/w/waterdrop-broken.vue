<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a-0srri6l"/><path class="w6stm6ief"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:waterdrop-broken" /></template>
<style>
.a-0srri6l {
  d: path("M6.1813 19.6349C7.7115 21.103 9.75482 21.9995 11.9992 21.9995C16.7433 21.9995 20.5892 17.9934 20.5892 13.0516C20.5892 9.95962 17.2263 5.83273 14.7088 3.17644C13.2185 1.60395 10.7799 1.60395 9.28953 3.17644C6.77201 5.83273 3.40918 9.95962 3.40918 13.0516C3.40918 14.0655 3.57105 15.0399 3.86933 15.9485");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6stm6ief {
  d: path("M7.64209 10.7591C8.68441 9.27182 9.91704 7.84888 11.0088 6.6875");
}

</style>
