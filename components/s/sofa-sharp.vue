<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ee9cb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-sharp" /></template>
<style>
.f5ee9cb9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11v6h18v-6a2 2 0 1 0-4 0v2H7v-2a2 2 0 1 0-4 0m2 6v2m14-2v2M12 5v8M5 9V5h14v4");
}

</style>
