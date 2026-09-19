<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g55lfcg7s"/><path class="f4g5ix6ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-branding-watermark" /></template>
<style>
.f4g5ix6ao {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H3V5h18zm-10-7h9v6h-9z");
}

.g55lfcg7s {
  fill: currentColor;
  d: path("M3 19h18V5H3zm8-7h9v6h-9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
