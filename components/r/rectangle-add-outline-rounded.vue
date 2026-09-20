<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-eldab4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rectangle-add-outline-rounded" /></template>
<style>
.s-eldab4q {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zm0 0V6zm7-5v2q0 .425.288.713T12 16t.713-.288T13 15v-2h2q.425 0 .713-.288T16 12t-.288-.712T15 11h-2V9q0-.425-.288-.712T12 8t-.712.288T11 9v2H9q-.425 0-.712.288T8 12t.288.713T9 13z");
}

</style>
