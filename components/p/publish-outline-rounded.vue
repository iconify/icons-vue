<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfi4yfbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:publish-outline-rounded" /></template>
<style>
.kfi4yfbhv {
  fill: currentColor;
  d: path("m11 11.85l-1.875 1.875q-.3.3-.712.288T7.7 13.7q-.275-.3-.288-.7t.288-.7l3.6-3.6q.15-.15.325-.212T12 8.425t.375.063t.325.212l3.6 3.6q.3.3.288.7t-.288.7q-.3.3-.712.313t-.713-.288L13 11.85V19q0 .425-.288.713T12 20t-.712-.288T11 19zM4 8V6q0-.825.588-1.412T6 4h12q.825 0 1.413.588T20 6v2q0 .425-.288.713T19 9t-.712-.288T18 8V6H6v2q0 .425-.288.713T5 9t-.712-.288T4 8");
}

</style>
