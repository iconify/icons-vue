<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gsx32r4uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sunbird" /></template>
<style>
.gsx32r4uo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.03 20.333a2.008 2.008 0 1 1-4.016 0a2.008 2.008 0 0 1 4.016 0M18.849 34.25c-6.643.16-10.487-7.013-10.758-13.588C7.838 14.518 12.65 5.04 23.83 4.513c7.096-.334 15.172 5.766 16.027 14.444c.486 4.928-2.003 10.766-5.073 12.992L18.849 43.5V20.685c0-2.868 2.207-5.843 5.621-5.904c3.19-.057 5.181 2.634 5.654 5.395h3.985l-4.014 4.474c-.143 6.582-6.72 10.6-11.246 9.6");
}

</style>
