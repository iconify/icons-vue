<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av9cxrbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pin-invoke-rounded" /></template>
<style>
.av9cxrbki {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h9q.425 0 .713.288T14 5t-.288.713T13 6H4v12h16v-5q0-.425.288-.712T21 12t.713.288T22 13v5q0 .825-.587 1.413T20 20zm9-6.575l-2.25 2.25q-.3.3-.7.288t-.7-.313q-.275-.3-.288-.7t.288-.7L11.6 12h-1.25q-.425 0-.712-.287T9.35 11t.288-.712t.712-.288H14q.425 0 .713.288T15 11v3.65q0 .425-.288.713T14 15.65t-.712-.288T13 14.65zM19 10q-1.25 0-2.125-.875T16 7t.875-2.125T19 4t2.125.875T22 7t-.875 2.125T19 10");
}

</style>
