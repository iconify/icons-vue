<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6girf35l"/><path class="uj3tl7b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-network-wifi-2-bar" /></template>
<style>
.m6girf35l {
  fill: currentColor;
  d: path("M16.78 13.38A8.85 8.85 0 0 0 12 12c-1.76 0-3.4.5-4.78 1.38l-4.3-4.3C5.51 7.08 8.67 6 12 6s6.49 1.08 9.08 3.07z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.uj3tl7b3r {
  fill: currentColor;
  d: path("M12 4C7.31 4 3.07 5.9 0 8.98L12 21L24 8.98A16.88 16.88 0 0 0 12 4m4.78 9.38A8.85 8.85 0 0 0 12 12c-1.76 0-3.4.5-4.78 1.38l-4.3-4.3C5.51 7.08 8.67 6 12 6s6.49 1.08 9.08 3.07z");
}

</style>
