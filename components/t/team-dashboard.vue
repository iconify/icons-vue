<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izi0b8bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:team-dashboard" /></template>
<style>
.izi0b8bfz {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19v-6.25h7V21zm7 0v-8.25h9V19q0 .825-.587 1.413T19 21zM3 10.75V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v5.75z");
}

</style>
