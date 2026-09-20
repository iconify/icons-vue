<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clntq1b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-footer-outline-rounded" /></template>
<style>
.clntq1b6y {
  fill: currentColor;
  d: path("M20 21H4q-.425 0-.712-.288T3 20t.288-.712T4 19h16q.425 0 .713.288T21 20t-.288.713T20 21M5 17q-.825 0-1.412-.587T3 15V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v10q0 .825-.587 1.413T19 17zm0-2h14V5H5zm0 0V5z");
}

</style>
