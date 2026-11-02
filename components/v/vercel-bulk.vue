<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_v0l4fit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vercel-bulk" /></template>
<style>
.u_v0l4fit {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.872 2.51l9 16A1 1 0 0 1 21 20H3a1 1 0 0 1-.872-1.49l9-16a1.002 1.002 0 0 1 1.744 0");
}

</style>
