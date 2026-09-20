<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3zjyqbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:topic-outline-rounded" /></template>
<style>
.j3zjyqbsd {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h5.175q.4 0 .763.15t.637.425L12 6h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20zm0-2h16V8h-8.825l-2-2H4zm0 0V6zm3-2h6q.425 0 .713-.288T14 15t-.288-.712T13 14H7q-.425 0-.712.288T6 15t.288.713T7 16m0-4h10q.425 0 .713-.288T18 11t-.288-.712T17 10H7q-.425 0-.712.288T6 11t.288.713T7 12");
}

</style>
