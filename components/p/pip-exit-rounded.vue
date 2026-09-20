<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgg4xy7ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pip-exit-rounded" /></template>
<style>
.dgg4xy7ti {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18v-6q0-.425.288-.712T3 11h6q.825 0 1.413-.587T11 9V5q0-.425.288-.712T12 4h8q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm9-10q-.425 0-.712.288T12 11v4q0 .425.288.713T13 16t.713-.288T14 15v-1.575l2.375 2.375q.3.3.7.3t.7-.3t.3-.712t-.3-.713L15.4 12H17q.425 0 .713-.288T18 11t-.288-.712T17 10zM3 9q-.425 0-.712-.288T2 8V5q0-.425.288-.712T3 4h5q.425 0 .713.288T9 5v3q0 .425-.288.713T8 9z");
}

</style>
