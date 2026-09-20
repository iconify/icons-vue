<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se6phrb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-landscape-add-rounded" /></template>
<style>
.se6phrb7v {
  fill: currentColor;
  d: path("M19.288 7.713Q19 7.425 19 7V6h-1q-.425 0-.712-.288T17 5t.288-.712T18 4h1V3q0-.425.288-.712T20 2t.713.288T21 3v1h1q.425 0 .713.288T23 5t-.288.713T22 6h-1v1q0 .425-.288.713T20 8t-.712-.288M7 16h3q.425 0 .713-.288T11 15V9q0-.425-.288-.712T10 8H7q-.425 0-.712.288T6 9v6q0 .425.288.713T7 16m-3 4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h10.3q.325 0 .525.238T15 4.8q-.05.875.213 1.688T16 8h-2q-.425 0-.712.288T13 9v6q0 .425.288.713T14 16h3q.425 0 .713-.288T18 15V9.575q.725.325 1.5.413t1.55-.088q.35-.075.65.125t.3.55V18q0 .825-.587 1.413T20 20z");
}

</style>
