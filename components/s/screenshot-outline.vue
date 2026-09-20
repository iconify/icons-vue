<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sby9ulbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-outline" /></template>
<style>
.sby9ulbsy {
  fill: currentColor;
  d: path("M16 15h-2v3h-3v2h5zm-9 8q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm0-2h10V3H7zm0 0V3zM8 9h2V6h3V4H8z");
}

</style>
