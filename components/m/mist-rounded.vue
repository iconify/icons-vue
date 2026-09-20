<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkx0h0biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mist-rounded" /></template>
<style>
.rkx0h0biy {
  fill: currentColor;
  d: path("M4 19q-.425 0-.712-.288T3 18t.288-.712T4 17h10q.425 0 .713.288T15 18t-.288.713T14 19zm14 0q-.425 0-.712-.288T17 18t.288-.712T18 17h2q.425 0 .713.288T21 18t-.288.713T20 19zM4 15q-.425 0-.712-.288T3 14t.288-.712T4 13h2q.425 0 .713.288T7 14t-.288.713T6 15zm6 0q-.425 0-.712-.288T9 14t.288-.712T10 13h10q.425 0 .713.288T21 14t-.288.713T20 15zm-6-4q-.425 0-.712-.288T3 10t.288-.712T4 9h11q.425 0 .713.288T16 10t-.288.713T15 11zm15 0q-.425 0-.712-.288T18 10t.288-.712T19 9h1q.425 0 .713.288T21 10t-.288.713T20 11zM4 7q-.425 0-.712-.288T3 6t.288-.712T4 5h5q.425 0 .713.288T10 6t-.288.713T9 7zm9 0q-.425 0-.712-.288T12 6t.288-.712T13 5h7q.425 0 .713.288T21 6t-.288.713T20 7z");
}

</style>
