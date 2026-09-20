<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fth-dmqih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:meeting-room-rounded" /></template>
<style>
.fth-dmqih {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h1V4q0-.425.288-.712T6 3h7q.425 0 .713.288T14 4h4q.425 0 .713.288T19 5v14h1q.425 0 .713.288T21 20t-.288.713T20 21h-2q-.425 0-.712-.288T17 20V6h-3v14q0 .425-.288.713T13 21zm7.713-9.712Q11.425 11 11 11t-.712.288T10 12t.288.713T11 13t.713-.288T12 12t-.288-.712");
}

</style>
