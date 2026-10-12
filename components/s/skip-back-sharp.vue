<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pomijbckr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skip-back-sharp" /></template>
<style>
.pomijbckr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.81 5.74l-7.62 5.27l-1.44.99l1.44.99l7.62 5.27l1.44.99V4.75zM4.75 4.75v14.5");
}

</style>
