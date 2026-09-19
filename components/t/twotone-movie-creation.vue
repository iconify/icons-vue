<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0lo7dwrk"/><path class="lp0mxph6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-movie-creation" /></template>
<style>
.f0lo7dwrk {
  fill: currentColor;
  d: path("M4 6.47V18h16v-8H5.76z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.lp0mxph6h {
  fill: currentColor;
  d: path("m18 4l2 4h-3l-2-4h-2l2 4h-3l-2-4H8l2 4H7L5 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4zm2 14H4V6.47L5.76 10H20z");
}

</style>
