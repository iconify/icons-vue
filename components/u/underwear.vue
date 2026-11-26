<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_t-42bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:underwear" /></template>
<style>
.g_t-42bun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5L21 5C21.5523 5 22 5.4477 22 6L22 9.2792C22 9.7096 21.7246 10.0918 21.3162 10.2279L18.0016 11.3328C16.749 11.7503 15.7831 12.7591 15.4204 14.0287L14.2072 18.2747C14.0846 18.704 13.6922 19 13.2457 19L10.7543 19C10.3078 19 9.9154 18.704 9.7928 18.2747L8.5796 14.0287C8.2169 12.7591 7.251 11.7503 5.9984 11.3328L2.6838 10.2279C2.2754 10.0918 2 9.7096 2 9.2792L2 6C2 5.4477 2.4477 5 3 5Z");
}

</style>
