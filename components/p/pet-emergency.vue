<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atk-epbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-emergency" /></template>
<style>
.atk-epbcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.235 19.069c-1.315.917-2.946 1.431-4.735 1.431c-4.5 0-8-3.25-8-8v-10l5 3.5h6l5-3.5v9.493m-11-.493h.01m5.99 0h.01M18 14.75v3.5M18 21h.01");
}

</style>
