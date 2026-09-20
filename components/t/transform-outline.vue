<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-ggjj1hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transform-outline" /></template>
<style>
.i-ggjj1hd {
  fill: currentColor;
  d: path("m16 23l-4-4l1.4-1.45l1.6 1.6V17H9q-.825 0-1.412-.587T7 15V9H2V7h5V4.85l-1.6 1.6L4 5l4-4l4 4l-1.4 1.45L9 4.85V15h13v2h-5v2.15l1.6-1.6L20 19zm-1-10V9h-4V7h4q.825 0 1.413.588T17 9v4z");
}

</style>
