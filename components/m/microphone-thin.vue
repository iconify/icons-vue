<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vuj5eeb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:microphone-thin" /></template>
<style>
.vuj5eeb-l {
  fill: currentColor;
  d: path("M128 172a44.05 44.05 0 0 0 44-44V64a44 44 0 0 0-88 0v64a44.05 44.05 0 0 0 44 44M92 64a36 36 0 0 1 72 0v64a36 36 0 0 1-72 0Zm40 139.89V240a4 4 0 0 1-8 0v-36.11A76.09 76.09 0 0 1 52 128a4 4 0 0 1 8 0a68 68 0 0 0 136 0a4 4 0 0 1 8 0a76.09 76.09 0 0 1-72 75.89");
}

</style>
