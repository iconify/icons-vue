<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhcjuobrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:submarine-sharp" /></template>
<style>
.bhcjuobrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 20H7v-8h3V8h4v4h3a4 4 0 1 1 0 8M3 12v8m0-4h4m5-8V4h4m-4 12h.01M16 16h.01");
}

</style>
