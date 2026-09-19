<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyl7zebob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-camera-outdoor" /></template>
<style>
.lyl7zebob {
  fill: currentColor;
  d: path("M18 13c0-.55-.45-1-1-1h-4c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-1l2 1.06v-4.12L18 14zM12 3L4 9v12h16v-2H6v-9l6-4.5l6 4.5v1h2V9z");
}

</style>
