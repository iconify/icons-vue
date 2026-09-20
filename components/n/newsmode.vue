<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ataqonblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:newsmode" /></template>
<style>
.ataqonblw {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v14q0 .825-.587 1.413T20 21zm2-4h12v-2H6zm0-4h4V7H6zm6 0h6v-2h-6zm0-4h6V7h-6z");
}

</style>
