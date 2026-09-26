<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umyj5_yms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-zap" /></template>
<style>
.umyj5_yms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 4L17 7L21 7L18 10M9 14H11C14.3137 14 17 16.6863 17 20C17 20.5523 16.5523 21 16 21H4C3.44772 21 3 20.5523 3 20C3 16.6863 5.68629 14 9 14ZM10 4C11.6569 4 13 5.34315 13 7C13 8.65685 11.6569 10 10 10C8.34315 10 7 8.65685 7 7C7 5.34315 8.34315 4 10 4Z");
}

</style>
