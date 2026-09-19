<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7iuzcj2r"/><path class="i8a-4abem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-hospital" /></template>
<style>
.i8a-4abem {
  fill: currentColor;
  d: path("M21 5c0-1.1-.9-2-2-2H5c-1.1 0-1.99.9-1.99 2L3 19c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2zm-2 14H5V5h14zm-8.5-2h3v-3.5H17v-3h-3.5V7h-3v3.5H7v3h3.5z");
}

.u7iuzcj2r {
  fill: currentColor;
  d: path("M5 19h14V5H5zm2-8.5h3.5V7h3v3.5H17v3h-3.5V17h-3v-3.5H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
