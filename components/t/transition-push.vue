<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pes08yb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-push" /></template>
<style>
.pes08yb-h {
  fill: currentColor;
  d: path("M8 20v-1.975h2V6H8V4h2q.825 0 1.413.588T12 6v12q0 .825-.587 1.413T10 20zm8 0q-.825 0-1.412-.587T14 18V6q0-.825.588-1.412T16 4h5q.825 0 1.413.588T23 6v12q0 .825-.587 1.413T21 20zM5 16l-1.425-1.4L5.15 13H1v-2h4.15L3.575 9.425L5 8l4 4z");
}

</style>
