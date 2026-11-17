<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crysd7zol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-warning" /></template>
<style>
.crysd7zol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 8A8.944 8.944 0 0 0 4 8m4 0H4V4m0 12a8.944 8.944 0 0 0 16 0m-4 0h4v4M12 8v5m0 3h.01");
}

</style>
