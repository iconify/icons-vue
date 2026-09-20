<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9npsbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-add" /></template>
<style>
.dg9npsbvt {
  fill: currentColor;
  d: path("M5 11q-.825 0-1.412-.587T3 9V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v4q0 .825-.587 1.413T19 11zm0 10q-.825 0-1.412-.587T3 19v-4q0-.825.588-1.412T5 13h14q.825 0 1.413.588T21 15v.1q-.225-.05-.5-.075T20 15q-2.1 0-3.55 1.463T15 20q0 .275.025.525T15.1 21zm14 2v-2h-2v-2h2v-2h2v2h2v2h-2v2z");
}

</style>
