<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs9sct9ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-1-75-outline" /></template>
<style>
.rs9sct9ic {
  fill: currentColor;
  d: path("M7 17v-2h2v2zm9 0v-2h4v-2h-4V7h6v2h-4v2h2q.825 0 1.413.588T22 13v2q0 .825-.587 1.413T20 17zM4 17V9H2V7h4v10zm7 0l2-8H9V7h4.25q.725 0 1.238.538T15 8.8l-.05.45L13 17z");
}

</style>
