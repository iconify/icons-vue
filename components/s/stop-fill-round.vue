<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr-vo4brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stop-fill-round" /></template>
<style>
.lr-vo4brq {
  fill: currentColor;
  d: path("M9 4h6a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 20H9a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5");
}

</style>
