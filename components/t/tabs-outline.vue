<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3e6xkbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tabs-outline" /></template>
<style>
.o3e6xkbay {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14v-7H5zm0-9h14V5H5zm7-2h6V6h-6zm-7 2V5z");
}

</style>
