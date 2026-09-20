<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rug820buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-group" /></template>
<style>
.rug820buq {
  fill: currentColor;
  d: path("M8 18q-.825 0-1.412-.587T6 16v-2h2v2h12V6H8v2H6V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm-4 4q-.825 0-1.412-.587T2 20V6h2v14h14v2zm9-7l-1.4-1.4l1.575-1.6H6v-2h7.175L11.6 8.4L13 7l4 4z");
}

</style>
