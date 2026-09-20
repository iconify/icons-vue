<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgvhsachg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:partner-reports-outline-rounded" /></template>
<style>
.qgvhsachg {
  fill: currentColor;
  d: path("M11.288 16.713Q11 16.425 11 16t.288-.712T12 15t.713.288T13 16t-.288.713T12 17t-.712-.288m0-4Q11 12.425 11 12V4q0-.425.288-.712T12 3t.713.288T13 4v8q0 .425-.288.713T12 13t-.712-.288M5 21q-.825 0-1.412-.587T3 19v-2q0-.425.288-.712T4 16t.713.288T5 17v2h14v-2q0-.425.288-.712T20 16t.713.288T21 17v2q0 .825-.587 1.413T19 21z");
}

</style>
