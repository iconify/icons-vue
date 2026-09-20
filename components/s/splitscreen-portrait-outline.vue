<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwdq-fl_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-portrait-outline" /></template>
<style>
.cwdq-fl_m {
  fill: currentColor;
  d: path("M8 18h8v-5H8zm0-7h8V6H8zm12 9q0 .825-.587 1.413T18 22H6q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4zm-2 0V4H6v16zm0-16H6z");
}

</style>
