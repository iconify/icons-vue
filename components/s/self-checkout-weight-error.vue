<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xddhwqbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:self-checkout-weight-error" /></template>
<style>
.xddhwqbzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.2 17.5H2.5V15h9.4m.3 6.5H5v-4h6.2M5 15V8.5L6 5h2v3c1 1 3 1 4 0V5h2l1 3.5v3.348M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-2.25v2.75m0 2h.01");
}

</style>
