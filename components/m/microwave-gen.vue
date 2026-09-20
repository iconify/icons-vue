<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo5onbcwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:microwave-gen" /></template>
<style>
.oo5onbcwr {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm1-3h10V7H5zm13.713-.288Q19 16.426 19 16t-.288-.712T18 15t-.712.288T17 16t.288.713T18 17t.713-.288M7 15V9h6v6zm11.713-2.287Q19 12.425 19 12t-.288-.712T18 11t-.712.288T17 12t.288.713T18 13t.713-.288m0-4Q19 8.426 19 8t-.288-.712T18 7t-.712.288T17 8t.288.713T18 9t.713-.288");
}

</style>
