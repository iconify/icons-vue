<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch4x5rb1h"/><path class="g5wnm1b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-rectangle" /></template>
<style>
.ch4x5rb1h {
  fill: currentColor;
  d: path("M4 6h16v12H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.g5wnm1b8d {
  fill: currentColor;
  d: path("M2 4v16h20V4zm18 14H4V6h16z");
}

</style>
