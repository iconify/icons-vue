<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydmdk9c9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sound-detection-glass-break" /></template>
<style>
.ydmdk9c9w {
  fill: currentColor;
  d: path("M4 15.712V4h16v2.935l-6.48 7.27l-4.02-4.018zM4 20v-2.712l5.5-5.525l3.98 3.981L20 8.434V20z");
}

</style>
