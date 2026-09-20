<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw6j_6bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-left-outline" /></template>
<style>
.gw6j_6bez {
  fill: currentColor;
  d: path("M15 20v-2h4V6h-4V4h4q.825 0 1.413.588T21 6v12q0 .825-.587 1.413T19 20zm-4 2v-2H5q-.825 0-1.412-.587T3 18V6q0-.825.588-1.412T5 4h6V2h2v20zm8-16v12z");
}

</style>
