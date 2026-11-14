<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_p-fm7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-failure-diff" /></template>
<style>
.k9_p-fm7z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H11v18H2.5Zm11 10.6V3H22v10.1m-8.5 5.5v-1.2M5.25 8h3m-3 4.5h3m8-4.5h3m-3.75 7.5l5 5m0-5l-5 5");
}

</style>
