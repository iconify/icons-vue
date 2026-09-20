<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydadwkbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-outline-rounded" /></template>
<style>
.ydadwkbwv {
  fill: currentColor;
  d: path("M4 19q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v12q0 .825-.587 1.413T20 19h-4v1q0 .425-.288.713T15 21H9q-.425 0-.712-.288T8 20v-1zm0-2h16V5H4zm0 0V5z");
}

</style>
