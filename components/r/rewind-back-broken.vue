<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xv_eznbni"/><path class="zf-7-266r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-back-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xv_eznbni {
  d: path("M13 15.2316L19.0966 19.6916C20.3991 20.5888 21.9998 19.4211 21.9998 17.5737L21.9998 15M13 8.76844L19.0966 4.30838C20.3991 3.41122 21.9998 4.57894 21.9998 6.42631L21.9998 11");
}

.zf-7-266r {
  d: path("M6.63008 7.70832L10.3388 5.26983C11.5327 4.48482 13 5.50658 13 7.12303V16.877C13 18.4934 11.5327 19.5152 10.3388 18.7302L2.92135 13.8532C1.69288 13.0455 1.69288 10.9545 2.92136 10.1468L3.84854 9.53719");
}

</style>
