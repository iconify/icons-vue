<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-dw1ebrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webhook-sharp" /></template>
<style>
.v-dw1ebrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 17a4 4 0 1 0 8 0h4m0 4a4 4 0 1 0 0-8h-4V7m4 0a4 4 0 1 0-8 0v10");
}

</style>
