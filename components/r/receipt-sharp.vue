<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj_herbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-sharp" /></template>
<style>
.rj_herbfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h8v18l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2V3zM8 7h8m-8 4h8m-8 4h4");
}

</style>
