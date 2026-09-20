<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uikb6_r2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-header-outline-rounded" /></template>
<style>
.uikb6_r2n {
  fill: currentColor;
  d: path("M4 5q-.425 0-.712-.288T3 4t.288-.712T4 3h16q.425 0 .713.288T21 4t-.288.713T20 5zm15 2q.825 0 1.413.588T21 9v10q0 .825-.587 1.413T19 21H5q-.825 0-1.412-.587T3 19V9q0-.825.588-1.412T5 7zm0 2H5v10h14zM5 9v10z");
}

</style>
