<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x54tt_bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stroller-sharp" /></template>
<style>
.x54tt_bsq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9L19 9L19 14L3 14ZM3 9C3 5.134 6.134 2 10 2L10 9M19 9L20 4L22 4M9 20C9 21.1046 8.1046 22 7 22C5.8954 22 5 21.1046 5 20C5 18.8954 5.8954 18 7 18C8.1046 18 9 18.8954 9 20ZM17 20C17 21.1046 16.1046 22 15 22C13.8954 22 13 21.1046 13 20C13 18.8954 13.8954 18 15 18C16.1046 18 17 18.8954 17 20Z");
}

</style>
