<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pn931ibvx"/><path class="brt4pwb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roof-inspection" /></template>
<style>
.brt4pwb8f {
  d: path("M4 9.5v12h11v-12m6.5 12l-4-13m.5 13l-4-13m3 3.5h3.5M18 15.5h3.5M19.25 19H22");
}

.pn931ibvx {
  d: path("m2.5 11l7-7l7 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
