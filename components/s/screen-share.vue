<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4vkty59v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screen-share" /></template>
<style>
.a4vkty59v {
  fill: currentColor;
  d: path("M8 14h2v-2q0-.425.288-.712T11 11h2v2l3-3l-3-3v2h-2q-1.25 0-2.125.875T8 12zm-4 4q-.825 0-1.412-.587T2 16V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v11q0 .825-.587 1.413T20 18zm-3 3v-2h22v2z");
}

</style>
