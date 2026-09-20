<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhu11l-6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pin-end-outline-rounded" /></template>
<style>
.uhu11l-6y {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v5q0 .425-.288.713T21 12t-.712-.288T20 11V6H4v12h9q.425 0 .713.288T14 19t-.288.713T13 20zm8.4-10l2.25 2.25q.275.275.275.688t-.275.712q-.3.3-.712.3t-.713-.3L11 11.425v1.225q0 .425-.287.713T10 13.65t-.712-.288T9 12.65V9q0-.425.288-.712T10 8h3.65q.425 0 .713.288T14.65 9t-.288.713t-.712.287zM19 20q-1.25 0-2.125-.875T16 17t.875-2.125T19 14t2.125.875T22 17t-.875 2.125T19 20");
}

</style>
