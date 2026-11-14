<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pu605qa-n"/><path class="gy8uoibmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:package-uninstall" /></template>
<style>
.gy8uoibmf {
  d: path("m3 7l9 4.5L21 7m-9 4.5v1.2M7.5 4.75l9 4.5M13 17.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm1.75 0h5.5");
}

.pu605qa-n {
  d: path("M11.128 21.064L3 17V7l9-4.5L21 7v4.038");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
