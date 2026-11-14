<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gev5csbra"/><path class="st8bpl8_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:social-analytics" /></template>
<style>
.gev5csbra {
  d: path("M11.935 17H6.25V9.25l3-5.5c1-1.25 3-.75 2.75 1L11.75 8H16q.094-.001.188.008t.187.029q.092.019.182.048t.176.068t.168.086t.157.103q.076.057.145.121q.07.063.132.135q.062.071.116.148t.1.16t.082.17t.063.177t.044.184t.023.187t.004.188q-.004.095-.017.188l-.315 1.732M2.5 9H5v8H2.5Zm12.25 5.5v6.75h6.75");
}

.st8bpl8_q {
  d: path("m16.75 19l1.5-2.25L19.5 18l2-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
