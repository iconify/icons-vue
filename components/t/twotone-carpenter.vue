<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw8g03oyv"/><path class="nu6j1gsic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-carpenter" /></template>
<style>
.cw8g03oyv {
  fill: currentColor;
  d: path("M5.71 5.62L7 4.33l8.49 8.49l-2.81 2.81z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nu6j1gsic {
  fill: currentColor;
  d: path("M19.73 14.23L7 1.5L3.11 5.39l8.13 11.67c-.78.78-.78 2.05 0 2.83l1.41 1.41c.78.78 2.05.78 2.83 0l4.24-4.24c.79-.78.79-2.05.01-2.83M5.71 5.62L7 4.33l8.49 8.49l-2.81 2.81zm8.36 14.26l-1.41-1.41l4.24-4.24l1.41 1.41z");
}

</style>
