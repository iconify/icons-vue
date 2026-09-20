<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvdn-0llx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-menu-ios-rounded" /></template>
<style>
.bvdn-0llx {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h10q.425 0 .713.288T15 20t-.288.713T14 21zm0-4q-.425 0-.712-.288T3 16t.288-.712T4 15h16q.425 0 .713.288T21 16t-.288.713T20 17zm1-4q-.825 0-1.412-.587T3 11V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v6q0 .825-.587 1.413T19 13z");
}

</style>
