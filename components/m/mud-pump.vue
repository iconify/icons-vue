<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h51x6nu8h"/><path class="s3ax_7btf"/><path class="z-87ixqgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mud-pump" /></template>
<style>
.h51x6nu8h {
  d: path("M10 8.5a5 5 0 1 0 0 8");
}

.s3ax_7btf {
  fill: currentColor;
  d: path("M6 12.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-87ixqgy {
  d: path("M7 8v9m3-8.5h7v8h-7Zm7 2h1.5v4H17Zm1.5 2h3m0-2.25v4.5");
}

</style>
