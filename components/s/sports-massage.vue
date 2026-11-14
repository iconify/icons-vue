<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amiq36e_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sports-massage" /></template>
<style>
.amiq36e_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 4.5H20a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-9.5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Zm2.5 6L11 21h4.5l2-10.5m-15-3a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h3");
}

</style>
