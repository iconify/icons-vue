<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut157lqys"/><path class="kad-_-bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-backspace" /></template>
<style>
.kad-_-bao {
  fill: currentColor;
  d: path("M22 3H7c-.69 0-1.23.35-1.59.88L0 12l5.41 8.11c.36.53.9.89 1.59.89h15c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H7.07L2.4 12l4.66-7H22zm-11.59-2L14 13.41L17.59 17L19 15.59L15.41 12L19 8.41L17.59 7L14 10.59L10.41 7L9 8.41L12.59 12L9 15.59z");
}

.ut157lqys {
  fill: currentColor;
  d: path("M7.06 5L2.4 12l4.67 7H22V5zq.015 0 0 0M9 8.41L10.41 7L14 10.59L17.59 7L19 8.41L15.41 12L19 15.59L17.59 17L14 13.41L10.41 17L9 15.59L12.59 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
