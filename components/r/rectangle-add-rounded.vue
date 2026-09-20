<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc7zo-b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rectangle-add-rounded" /></template>
<style>
.hc7zo-b4b {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm7-7v2q0 .425.288.713T12 16t.713-.288T13 15v-2h2q.425 0 .713-.288T16 12t-.288-.712T15 11h-2V9q0-.425-.288-.712T12 8t-.712.288T11 9v2H9q-.425 0-.712.288T8 12t.288.713T9 13z");
}

</style>
