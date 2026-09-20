<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs4f0fnek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-5-outline" /></template>
<style>
.gs4f0fnek {
  fill: currentColor;
  d: path("M7 17v-2h2v2zm3 0v-2h4v-2h-4V7h6v2h-4v2h2q.825 0 1.413.588T16 13v2q0 .825-.587 1.413T14 17z");
}

</style>
