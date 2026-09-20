<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjjcyhbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-shades-rounded" /></template>
<style>
.tjjcyhbso {
  fill: currentColor;
  d: path("M3 21q-.425 0-.712-.288T2 20t.288-.712T3 19h1V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v14h1q.425 0 .713.288T22 20t-.288.713T21 21zm7-2h4V5h-4z");
}

</style>
