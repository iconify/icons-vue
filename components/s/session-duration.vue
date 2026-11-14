<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr-43xbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:session-duration" /></template>
<style>
.tr-43xbwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.6 20H2.5V4h19v7.4m-19-2.9h19m-16-2.25h.01m2.74 0h.01M6 12h7m-7 3.5h4m5.25 3.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm1.75-4.5h2m-1 4.5v-1.5");
}

</style>
