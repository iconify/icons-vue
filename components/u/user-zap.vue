<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l52ic60vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-zap" /></template>
<style>
.l52ic60vq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 13H10C13.3137 13 16 15.6863 16 19V20C16 20.5523 15.5523 21 15 21H3C2.44772 21 2 20.5523 2 20V19C2 15.6863 4.68629 13 8 13ZM9 3C10.6569 3 12 4.34315 12 6C12 7.65685 10.6569 9 9 9C7.34315 9 6 7.65685 6 6C6 4.34315 7.34315 3 9 3ZM21 3L18 6L22 6L19 9");
}

</style>
