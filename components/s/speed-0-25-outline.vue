<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhq8rabvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-25-outline" /></template>
<style>
.mhq8rabvx {
  fill: currentColor;
  d: path("M4 17v-2h2v2zm10 0v-2h4v-2h-4V7h6v2h-4v2h2q.825 0 1.413.588T20 13v2q0 .825-.587 1.413T18 17zm-7 0v-4q0-.825.588-1.412T9 11h2V9H7V7h4q.825 0 1.413.588T13 9v2q0 .825-.587 1.413T11 13H9v2h4v2z");
}

</style>
