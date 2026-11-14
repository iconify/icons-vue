<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z91ytdz-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reaction-clap" /></template>
<style>
.z91ytdz-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5v-5l-2.5-3c-.75-1 .5-2.5 1.75-1.75l.75.75v-2a2.5 2.5 0 0 1 5 0v11m8 0v-5l2.5-3c.75-1-.5-2.5-1.75-1.75l-.75.75v-2a2.5 2.5 0 0 0-5 0v11M12 2.5V6M8 3l1 2.25M16 3l-1 2.25");
}

</style>
