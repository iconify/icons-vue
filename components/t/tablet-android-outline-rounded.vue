<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7l6iouvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tablet-android-outline-rounded" /></template>
<style>
.y7l6iouvx {
  fill: currentColor;
  d: path("M5 23q-.825 0-1.412-.587T3 21V3q0-.825.588-1.412T5 1h14q.825 0 1.413.588T21 3v18q0 .825-.587 1.413T19 23zm0-5v3h14v-3zm5.5 2h3q.2 0 .35-.15t.15-.35t-.15-.35t-.35-.15h-3q-.2 0-.35.15t-.15.35t.15.35t.35.15M5 16h14V6H5zM5 4h14V3H5zm0 0V3zm0 14v3z");
}

</style>
