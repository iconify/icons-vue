<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r-tv-oxcw"/><path class="ezkmwabnq"/><path class="janxgzbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-vertical-linear" /></template>
<style>
.ezkmwabnq {
  d: path("M19 2V2.5C19 3.88071 17.8807 5 16.5 5H7.5C6.11929 5 5 3.88071 5 2.5V2");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.janxgzbgp {
  d: path("M19 22V21.5C19 20.1193 17.8807 19 16.5 19H7.5C6.11929 19 5 20.1193 5 21.5V22");
}

.r-tv-oxcw {
  d: path("M9 16.5H15C16.8856 16.5 17.8284 16.5 18.4142 15.9142C19 15.3284 19 14.3856 19 12.5V11.5C19 9.61438 19 8.67157 18.4142 8.08579C17.8284 7.5 16.8856 7.5 15 7.5H9C7.11438 7.5 6.17157 7.5 5.58579 8.08579C5 8.67157 5 9.61438 5 11.5V12.5C5 14.3856 5 15.3284 5.58579 15.9142C6.17157 16.5 7.11438 16.5 9 16.5Z");
}

</style>
