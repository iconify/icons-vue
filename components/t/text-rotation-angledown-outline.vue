<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6nzvfo7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-rotation-angledown-outline" /></template>
<style>
.g6nzvfo7j {
  fill: currentColor;
  d: path("M10.577 20.5v-1h2.215l-9.8-9.8l.708-.708l9.8 9.8v-2.215h1V20.5zm4.235-5.858l-.735-.715l1.28-2.727l-3.284-3.284l-2.727 1.269l-.715-.735l10.046-4.504l.708.689zm-1.881-7.13l2.819 2.83l2.389-5.08l-.07-.07z");
}

</style>
