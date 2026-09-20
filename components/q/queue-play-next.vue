<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtszi9rjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:queue-play-next" /></template>
<style>
.qtszi9rjl {
  fill: currentColor;
  d: path("M11 15h2v-3h3v-2h-3V7h-2v3H8v2h3zm8.5 7.5L18 21l3-3l-3-3l1.5-1.5L24 18zM8 21v-2H4q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v7h-5v7h-2v2z");
}

</style>
