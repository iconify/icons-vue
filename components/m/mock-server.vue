<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txpwiw1ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mock-server" /></template>
<style>
.txpwiw1ga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h17V9h-17Zm9.2 15.75H2.5v-6.5h9.2m2.5 0h5.3v1.8M6.25 5.75h.01M6.25 15h.01m8.24 6.5V16l3.25 3.25L21 16v5.5");
}

</style>
