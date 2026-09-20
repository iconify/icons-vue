<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0b1nzbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shield-card" /></template>
<style>
.i0b1nzbbz {
  fill: currentColor;
  d: path("M13 22q-.825 0-1.412-.587T11 20v-5q0-.825.588-1.412T13 13h8q.825 0 1.413.588T23 15v5q0 .825-.587 1.413T21 22zm0-2h8v-2h-8zm0-4h8v-1h-8zm-9-4.9V5l8-3l8 3v6h-7q-1.65 0-2.825 1.175T9 15v5.35q0 .175.05.35q-2.275-1.5-3.662-4.075T4 11.1");
}

</style>
