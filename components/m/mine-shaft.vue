<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4zguvbno"/><path class="uzslpf_sk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mine-shaft" /></template>
<style>
.d4zguvbno {
  d: path("M2 6h5v15.5h10V6h5M12 2v9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzslpf_sk {
  d: path("M9.75 11h4.5v5h-4.5Z");
}

</style>
