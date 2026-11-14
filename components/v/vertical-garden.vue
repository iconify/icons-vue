<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w55t3abnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vertical-garden" /></template>
<style>
.w55t3abnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h18v19H3Zm0 6.25h18M3 15h18m-9-6.25V5.5m0 3.25L9.5 6M12 8.75L14.5 6M12 15v-3.25M12 15l-2.5-2.75M12 15l2.5-2.75M12 21.5v-3.25m0 3.25l-2.5-2.75M12 21.5l2.5-2.75");
}

</style>
