<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5es36not"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove-from-queue-rounded" /></template>
<style>
.x5es36not {
  fill: currentColor;
  d: path("M9 12h6q.425 0 .713-.288T16 11t-.288-.712T15 10H9q-.425 0-.712.288T8 11t.288.713T9 12m-5 7q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v12q0 .825-.587 1.413T20 19h-4v1q0 .425-.288.713T15 21H9q-.425 0-.712-.288T8 20v-1z");
}

</style>
