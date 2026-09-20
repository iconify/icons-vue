<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n18hdu8zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove-from-queue-outline" /></template>
<style>
.n18hdu8zr {
  fill: currentColor;
  d: path("M8 12h8v-2H8zm0 9v-2H4q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v12q0 .825-.587 1.413T20 19h-4v2zm-4-4h16V5H4zm0 0V5z");
}

</style>
