<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ut6bbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:menu-book-2" /></template>
<style>
.j_ut6bbbf {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20v-2H3v-2h1v-3H3v-2h1V8H3V6h1V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm3.5-5H11v-4q.65-.175 1.075-.712t.425-1.213V7h-1v3.775h-.75V7h-1v3.775H9V7H8v4.075q0 .675.425 1.213T9.5 13zm5.5 0h1.5V7q-1.25 0-2.125.875T13.5 10v3H15z");
}

</style>
