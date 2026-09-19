<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl048v9hd"/><path class="flqz0qbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-add-box" /></template>
<style>
.flqz0qbws {
  fill: currentColor;
  d: path("M19 3H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14zm-8-2h2v-4h4v-2h-4V7h-2v4H7v2h4z");
}

.rl048v9hd {
  fill: currentColor;
  d: path("M5 19h14V5H5zm2-8h4V7h2v4h4v2h-4v4h-2v-4H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
