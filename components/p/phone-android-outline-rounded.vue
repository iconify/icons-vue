<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpe90mn1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-android-outline-rounded" /></template>
<style>
.hpe90mn1v {
  fill: currentColor;
  d: path("M10.5 20h3q.2 0 .35-.15t.15-.35t-.15-.35t-.35-.15h-3q-.2 0-.35.15t-.15.35t.15.35t.35.15M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v18q0 .825-.587 1.413T17 23zm0-5v3h10v-3zm0-2h10V6H7zM7 4h10V3H7zm0 14v3zM7 4V3z");
}

</style>
