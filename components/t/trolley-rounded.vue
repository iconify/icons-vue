<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrtnokb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trolley-rounded" /></template>
<style>
.wrtnokb5f {
  fill: currentColor;
  d: path("M20 17H6q-.825 0-1.412-.587T4 15V5H3q-.425 0-.712-.288T2 4t.288-.712T3 3h1q.825 0 1.413.588T6 5v10h14q.425 0 .713.288T21 16t-.288.713T20 17M6 22q-.825 0-1.412-.587T4 20t.588-1.412T6 18t1.413.588T8 20t-.587 1.413T6 22m2-8q-.425 0-.712-.288T7 13V9q0-.425.288-.712T8 8h4q.425 0 .713.288T13 9v4q0 .425-.288.713T12 14zm7 0q-.425 0-.712-.288T14 13V9q0-.425.288-.712T15 8h4q.425 0 .713.288T20 9v4q0 .425-.288.713T19 14zm2.588 7.413Q17 20.825 17 20t.588-1.412T19 18t1.413.588T21 20t-.587 1.413T19 22t-1.412-.587");
}

</style>
