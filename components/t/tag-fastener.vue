<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k0o8uoo0e"/><path class="h7bqw2bqc"/><path class="efted6usd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tag-fastener" /></template>
<style>
.efted6usd {
  d: path("M12.5 7.75c2-2.25 4-3.5 6.5-3.5m0-1.75V6M9 13.5h5M9 17h3.5");
}

.h7bqw2bqc {
  d: path("M10.25 8.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.k0o8uoo0e {
  d: path("m6.5 9l5-5l5 5v12.5h-10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
