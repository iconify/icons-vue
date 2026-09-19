<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yfz3w9lrl"/><path class="iznk6u15j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-woman" /></template>
<style>
.iznk6u15j {
  fill: currentColor;
  d: path("m16.45 14.63l-2.52-6.32c-.32-.79-1.08-1.3-1.94-1.31c-.85 0-1.62.51-1.94 1.31l-2.52 6.32c-.25.66.24 1.37.94 1.37H10v5c0 .55.45 1 1 1h2c.55 0 1-.45 1-1v-5h1.53c.7 0 1.19-.71.92-1.37");
}

.yfz3w9lrl {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

</style>
