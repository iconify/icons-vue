<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7g7f3b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:qr-code-sharp" /></template>
<style>
.r7g7f3b-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4h6v6H4Zm10 0h6v6h-6ZM4 14h6v6H4Zm10 0h3m3 0h.01M14 18v2m4-2h2v2");
}

</style>
