<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue5tjrbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sound-detection-glass-break-outline" /></template>
<style>
.ue5tjrbhd {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 5v9l4.5-4.525l4 4L19 7.3V5zm0 14h14v-8.7l-5.5 6.175l-4-4L5 17z");
}

</style>
