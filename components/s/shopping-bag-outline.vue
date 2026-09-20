<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3eul7b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shopping-bag-outline" /></template>
<style>
.o3eul7b5w {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V8q0-.825.588-1.412T6 6h2q0-1.65 1.175-2.825T12 2t2.825 1.175T16 6h2q.825 0 1.413.588T20 8v12q0 .825-.587 1.413T18 22zm0-2h12V8h-2v2q0 .425-.288.713T15 11t-.712-.288T14 10V8h-4v2q0 .425-.288.713T9 11t-.712-.288T8 10V8H6zm4-14h4q0-.825-.587-1.412T12 4t-1.412.588T10 6M6 20V8z");
}

</style>
