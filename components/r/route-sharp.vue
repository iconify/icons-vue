<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slk3ngysw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-sharp" /></template>
<style>
.slk3ngysw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0M16 6H6v6h12v6H8m8-12a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
