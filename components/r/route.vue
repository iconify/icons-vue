<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="da5imtbyr"/><path class="rk8s6pb7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route" /></template>
<style>
.da5imtbyr {
  d: path("M8.5 18.5H15a3 3 0 0 0 0-6H9a3.5 3.5 0 0 1 0-7h6.5");
}

.rk8s6pb7a {
  d: path("M3.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12-13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
