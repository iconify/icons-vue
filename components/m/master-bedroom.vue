<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfud58tjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:master-bedroom" /></template>
<style>
.gfud58tjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5V21m0-4h9.2m-9.2-5h13.6m3.862.192q.141.059.273.134t.255.166t.232.196q.111.105.208.223q.097.117.178.246q.082.128.148.266q.066.137.114.281t.079.294M5 8h4.5v4H5Zm9.5 13.5v-6.75L16.25 18L18 14.5l1.75 3.5l1.75-3.25v6.75Z");
}

</style>
