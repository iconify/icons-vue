<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szingbcxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:robot-2-outline" /></template>
<style>
.szingbcxo {
  fill: currentColor;
  d: path("M4 21v-5q0-.825.588-1.412T6 14h12q.825 0 1.413.588T20 16v5zm5-8q-2.075 0-3.537-1.463T4 8t1.463-3.537T9 3h6q2.075 0 3.538 1.463T20 8t-1.463 3.538T15 13zm-3 6h12v-3H6zm3-8h6q1.25 0 2.125-.875T18 8t-.875-2.125T15 5H9q-1.25 0-2.125.875T6 8t.875 2.125T9 11m.713-2.287Q10 8.425 10 8t-.288-.712T9 7t-.712.288T8 8t.288.713T9 9t.713-.288m6 0Q16 8.426 16 8t-.288-.712T15 7t-.712.288T14 8t.288.713T15 9t.713-.288M12 8");
}

</style>
