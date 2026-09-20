<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGRL8h5dvm)" class="m0bx-sb7s"/><defs><linearGradient id="SVGRL8h5dvm" x1="5.25" x2="22.79" y1="2.196" y2="13.693" gradientUnits="userSpaceOnUse"><stop offset=".06" class="svuu6gb_h"/><stop offset="1" class="ygqosjbbg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rev" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m0bx-sb7s {
  d: path("m9.29 3l8.165 4.636v3.818l-3.71 1.997L18 16.636V21l-7.636-5.727v-3.818l3.72-2.002l-4.795-2.706v11.526L6 21V4.636L9.284 3z");
}

.svuu6gb_h {
  stop-color: var(--svg-color--1a1c3c, #1a1c3c);
}

.ygqosjbbg {
  stop-color: var(--svg-color--720044, #720044);
}

</style>
