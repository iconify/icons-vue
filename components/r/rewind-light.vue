<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bntzjc7wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rewind-light" /></template>
<style>
.bntzjc7wy {
  fill: currentColor;
  d: path("M222.81 59.72a14 14 0 0 0-14.22.46L126 112.79V71.84a13.83 13.83 0 0 0-7.19-12.12a14 14 0 0 0-14.22.46l-88.18 56.17a13.79 13.79 0 0 0 0 23.3l88.18 56.17a14 14 0 0 0 14.22.46a13.83 13.83 0 0 0 7.19-12.12v-40.95l82.59 52.61a14 14 0 0 0 14.22.46a13.83 13.83 0 0 0 7.19-12.12V71.84a13.83 13.83 0 0 0-7.19-12.12M114 184.16a1.73 1.73 0 0 1-1 1.59a1.9 1.9 0 0 1-2-.06l-88.15-56.16a1.8 1.8 0 0 1 0-3.06L111 70.31a1.87 1.87 0 0 1 1-.32a2 2 0 0 1 1 .26a1.73 1.73 0 0 1 1 1.59Zm104 0a1.73 1.73 0 0 1-1 1.59a1.9 1.9 0 0 1-2-.06l-88.19-56.16a1.8 1.8 0 0 1 0-3.06L215 70.31a1.87 1.87 0 0 1 1-.32a2 2 0 0 1 1 .26a1.73 1.73 0 0 1 1 1.59Z");
}

</style>
