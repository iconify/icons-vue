<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enx9uxbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-menu-ios-outline" /></template>
<style>
.enx9uxbvq {
  fill: currentColor;
  d: path("M3 21v-2h12v2zm0-4v-2h18v2zm2-4q-.825 0-1.412-.587T3 11V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v6q0 .825-.587 1.413T19 13zm0-2h14V5H5zm0 0V5z");
}

</style>
