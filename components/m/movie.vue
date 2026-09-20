<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctwe9pbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie" /></template>
<style>
.ctwe9pbnb {
  fill: currentColor;
  d: path("m4 4l2 4h3L7 4h2l2 4h3l-2-4h2l2 4h3l-2-4h3q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4");
}

</style>
