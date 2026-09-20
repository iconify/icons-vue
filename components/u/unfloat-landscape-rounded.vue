<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8dyzcoxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfloat-landscape-rounded" /></template>
<style>
.b8dyzcoxe {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h16q.825 0 1.413.588T22 6v4q0 .425-.288.713T21 11h-4q-.825 0-1.413.588T15 13v6q0 .425-.288.713T14 20H4Zm14 0q-.425 0-.713-.288T17 19v-5q0-.425.288-.713T18 13h3q.425 0 .713.288T22 14v5q0 .425-.288.713T21 20h-3ZM7 14q.425 0 .713-.288T8 13v-1.575l2.375 2.375q.3.3.7.3t.7-.3q.3-.3.3-.713t-.3-.712L9.4 10H11q.425 0 .713-.288T12 9q0-.425-.288-.713T11 8H7q-.425 0-.713.288T6 9v4q0 .425.288.713T7 14Z");
}

</style>
