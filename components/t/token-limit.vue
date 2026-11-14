<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wu7lmw6mt"/><path class="iaohes6ga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:token-limit" /></template>
<style>
.iaohes6ga {
  fill: currentColor;
  d: path("M6.25 10.75h11v2.5h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wu7lmw6mt {
  d: path("M20 8H6a2.5 2.5 0 0 0-2.5 2.5v3A2.5 2.5 0 0 0 6 16h14m0-11.5v15");
}

</style>
