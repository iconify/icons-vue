<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iay0cjsqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-vertical" /></template>
<style>
.iay0cjsqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4L7 3C7 2.4477 7.4477 2 8 2L16 2C16.5523 2 17 2.4477 17 3L17 4M12 2L12 10M10 10L14 10M7 16L7 15C7 14.4477 7.4477 14 8 14L16 14C16.5523 14 17 14.4477 17 15L17 16M12 14L12 22M10 22L14 22");
}

</style>
