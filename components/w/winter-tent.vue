<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d98fe_sdt"/><path class="gzedkrlxl"/><path class="nuk5habzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:winter-tent" /></template>
<style>
.d98fe_sdt {
  d: path("m7 12l5-7.5l5 7.5c-1.5 1-2.5-1-5-.5s-3.5-1-5 .5Z");
}

.gzedkrlxl {
  d: path("m7 12l-4.25 7.5h18.5L17 12");
}

.nuk5habzz {
  d: path("m9.5 19.5l2.5-5l2.5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
