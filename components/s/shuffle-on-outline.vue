<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl8chacww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shuffle-on-outline" /></template>
<style>
.bl8chacww {
  fill: currentColor;
  d: path("M3 23q-.825 0-1.412-.587T1 21V3q0-.825.588-1.412T3 1h18q.825 0 1.413.588T23 3v18q0 .825-.587 1.413T21 23zm11-3h6v-6h-2v2.55l-3.15-3.15l-1.425 1.425L16.6 18H14zm-8.6 0L18 7.4V10h2V4h-6v2h2.6L4 18.6zm3.775-9.425l1.4-1.4L5.4 4L4 5.4z");
}

</style>
