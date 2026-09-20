<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijwekib1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:recent-patient-rounded" /></template>
<style>
.ijwekib1i {
  fill: currentColor;
  d: path("M6 20q-.825 0-1.412-.587T4 18v-.8q0-.85.438-1.562T5.6 14.55q1.55-.775 3.15-1.162T12 13q.275 0 .538.013t.537.037q.4.05.663.338t.262.687V19q0 .425-.288.713T13 20zm3.175-9.175Q8 9.65 8 8t1.175-2.825T12 4t2.825 1.175T16 8t-1.175 2.825T12 12t-2.825-1.175M18 19h-1q-.425 0-.712-.288T16 18v-4q0-.425.288-.712T17 13h3.775q.425 0 .65.35t.025.725L20 17h.7q.425 0 .637.375t.013.75l-2.875 5.05q-.1.175-.288.125T18 23.05z");
}

</style>
