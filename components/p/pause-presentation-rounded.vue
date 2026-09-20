<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvsmxkbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pause-presentation-rounded" /></template>
<style>
.bvsmxkbzh {
  fill: currentColor;
  d: path("M10.713 15.713Q11 15.425 11 15V9q0-.425-.288-.712T10 8t-.712.288T9 9v6q0 .425.288.713T10 16t.713-.288m4 0Q15 15.426 15 15V9q0-.425-.288-.712T14 8t-.712.288T13 9v6q0 .425.288.713T14 16t.713-.288M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
