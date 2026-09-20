<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzuhgibvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settop-component-outline-rounded" /></template>
<style>
.jzuhgibvz {
  fill: currentColor;
  d: path("M4 17q-.825 0-1.412-.587T2 15V9q0-.825.588-1.412T4 7h16q.825 0 1.413.588T22 9v6q0 .825-.587 1.413T20 17zm0-2h16V9H4zm2-2h4q.425 0 .713-.288T11 12t-.288-.712T10 11H6q-.425 0-.712.288T5 12t.288.713T6 13m8.713-.288Q15 12.426 15 12t-.288-.712T14 11t-.712.288T13 12t.288.713T14 13t.713-.288m3 0Q18 12.426 18 12t-.288-.712T17 11t-.712.288T16 12t.288.713T17 13t.713-.288M4 15V9z");
}

</style>
