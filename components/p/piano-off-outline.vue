<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8cy6ac_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:piano-off-outline" /></template>
<style>
.p8cy6ac_j {
  fill: currentColor;
  d: path("M19.775 22.625L18.15 21H5q-.825 0-1.412-.587T3 19V5.85L1.375 4.225L2.8 2.8l18.4 18.4zM21 18.15l-2-2V5h-2v8.5q0 .125-.038.25t-.112.25L13 10.15V5h-2v3.15L5.85 3H19q.825 0 1.413.588T21 5zM5 19h3.25v-4.5H8q-.425 0-.712-.288T7 13.5V9.85l-2-2zm4.75 0h4.5v-1.9l-3.3-3.3q-.1.325-.362.513T10 14.5h-.25zm6 0h.4l-.4-.4z");
}

</style>
