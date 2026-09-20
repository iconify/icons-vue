<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se2z7rb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:moped-sharp" /></template>
<style>
.se2z7rb-o {
  fill: currentColor;
  d: path("M4.875 18.125Q4 17.25 4 16H2V9h8v5h3.5L17 9.65V7h-3V5h5v5.35L14.5 16H10q0 1.25-.875 2.125T7 19t-2.125-.875m2.838-1.412Q8 16.425 8 16H6q0 .425.288.713T7 17t.713-.288M5 8V6h5v2zm11.875 10.125Q16 17.25 16 16t.875-2.125T19 13t2.125.875T22 16t-.875 2.125T19 19t-2.125-.875m2.838-1.412Q20 16.425 20 16t-.288-.712T19 15t-.712.288T18 16t.288.713T19 17t.713-.288");
}

</style>
