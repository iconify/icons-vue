<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve8hqmbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:voucher-ticket" /></template>
<style>
.ve8hqmbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5.5H15v13H4.5a2 2 0 0 1-2-2V14a2 2 0 0 0 0-4V7.5a2 2 0 0 1 2-2Zm13.25 0h1.75a2 2 0 0 1 2 2V10a2 2 0 0 0 0 4v2.5a2 2 0 0 1-2 2h-1.75Zm-6.25 3l-4 7m0-6.5h.01m3.99 6h.01");
}

</style>
