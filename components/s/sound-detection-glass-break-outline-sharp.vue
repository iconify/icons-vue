<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjhltorqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sound-detection-glass-break-outline-sharp" /></template>
<style>
.tjhltorqj {
  fill: currentColor;
  d: path("M4 20V4h16v16zM5 5v9.712l4.5-4.525l4.02 4.019L19 8.05V5zm0 14h14V9.55l-5.52 6.194l-3.98-3.98L5 16.289z");
}

</style>
