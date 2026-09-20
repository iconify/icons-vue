<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erm0e1bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:toast-outline-rounded" /></template>
<style>
.erm0e1bdw {
  fill: currentColor;
  d: path("M7 18h10q.425 0 .713-.288T18 17t-.288-.712T17 16H7q-.425 0-.712.288T6 17t.288.713T7 18m-2 3q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
