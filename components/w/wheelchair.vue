<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lggu7zbfi"/><path class="zhbmsgb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wheelchair" /></template>
<style>
.lggu7zbfi {
  d: path("M9 9L9 14C9 14.5523 9.4477 15 10 15L15.2792 15C15.7097 15 16.0918 15.2754 16.2279 15.6838L17.7721 20.3162C17.9082 20.7246 18.2903 21 18.7208 21L21 21M9 11L13 11M13.209 19.276C12.126 20.3422 10.6398 21 9 21C5.6863 21 3 18.3137 3 15C3 13.223 3.7725 11.6264 5 10.5278");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zhbmsgb3y {
  fill: currentColor;
  d: path("M12 4C12 5.1046 11.1046 6 10 6C8.8954 6 8 5.1046 8 4C8 2.8954 8.8954 2 10 2C11.1046 2 12 2.8954 12 4Z");
  stroke: none;
}

</style>
