<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yocylzble"/><path class="kwxrv6rmf"/><path class="d-_jzwb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:network-6g" /></template>
<style>
.d-_jzwb5p {
  d: path("M4.218 6.551a9.5 9.5 0 0 1 15.564 0");
}

.kwxrv6rmf {
  d: path("M6.676 8.272a6.5 6.5 0 0 1 10.648 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yocylzble {
  d: path("m12 12l4.25 2.5V19L12 21.5L7.75 19v-4.5ZM9.133 9.992a3.5 3.5 0 0 1 5.734 0");
}

</style>
