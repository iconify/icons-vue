<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc18mbb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:quick-links" /></template>
<style>
.uc18mbb4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5h7M3 14h7m-7 6h18M16.121 6.145l-2.039 3.173A1.092 1.092 0 0 0 15 11a1.4 1.4 0 0 1 1.317 1.88l-.317.87a.418.418 0 0 0 .73.39l2.587-3.527A1.013 1.013 0 0 0 18.5 9h-.17a1.5 1.5 0 0 1-1.471-1.794L17 6.5a.482.482 0 0 0-.879-.355");
}

</style>
