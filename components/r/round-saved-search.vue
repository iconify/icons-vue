<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps00jvbna"/><path class="y_4vks51o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-saved-search" /></template>
<style>
.ps00jvbna {
  fill: currentColor;
  d: path("M14.73 13.31c1.13-1.55 1.63-3.58.98-5.74c-.68-2.23-2.57-3.98-4.85-4.44a6.52 6.52 0 0 0-7.72 7.73c.46 2.29 2.21 4.18 4.44 4.85c2.16.65 4.19.15 5.74-.98l5.56 5.56a.996.996 0 1 0 1.41-1.41zM9.5 14C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5S14 7.01 14 9.5S11.99 14 9.5 14");
}

.y_4vks51o {
  fill: currentColor;
  d: path("M10.29 8.44L9.5 6l-.79 2.44H6.25l2.01 1.59l-.77 2.47l2.01-1.53l2.01 1.53l-.77-2.47l2.01-1.59z");
}

</style>
