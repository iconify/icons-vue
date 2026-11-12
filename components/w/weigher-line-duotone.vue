<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wyf-9gbfh"/><path class="hwifnpb2v"/><path class="jc2hwtrrg"/><path class="wvqgt30sr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:weigher-line-duotone" /></template>
<style>
.hwifnpb2v {
  d: path("M8 18H16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jc2hwtrrg {
  d: path("M17.0774 8.30695L16.4117 9.97103C16.176 10.5604 15.5411 10.8851 14.9252 10.7311C13.0047 10.251 10.9957 10.251 9.07523 10.7311C8.45936 10.8851 7.82443 10.5604 7.58866 9.97103L6.92303 8.30695C6.44885 7.12149 7.19178 5.80129 8.45119 5.59138L8.87663 5.52048C10.9447 5.17579 13.0557 5.17579 15.1238 5.52048L15.5492 5.59138C16.8086 5.80129 17.5516 7.12149 17.0774 8.30695Z");
}

.wvqgt30sr {
  d: path("M10.1794 9.92881L9.50439 8.04614");
}

.wyf-9gbfh {
  d: path("M11 22H13C16.7712 22 18.6569 22 19.8284 20.8284C21 19.6569 21 17.7712 21 14V10C21 6.22876 21 4.34315 19.8284 3.17157C18.6569 2 16.7712 2 13 2H11C7.22876 2 5.34315 2 4.17157 3.17157C3 4.34315 3 6.22876 3 10V14C3 17.7712 3 19.6569 4.17157 20.8284C5.34315 22 7.22876 22 11 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
