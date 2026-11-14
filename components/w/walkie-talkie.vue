<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hekmgtbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:walkie-talkie" /></template>
<style>
.hekmgtbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.875 7h2.25a4.375 4.375 0 0 1 4.375 4.375v5.75a4.375 4.375 0 0 1-4.375 4.375h-2.25A4.375 4.375 0 0 1 6.5 17.125v-5.75A4.375 4.375 0 0 1 10.875 7M9 7V2.5m.5 8.5h5m-5 3h5M12 18h.01");
}

</style>
