<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5ygn9bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shield-card-outline" /></template>
<style>
.p5ygn9bam {
  fill: currentColor;
  d: path("M13 22q-.825 0-1.412-.587T11 20v-5q0-.825.588-1.412T13 13h8q.825 0 1.413.588T23 15v5q0 .825-.587 1.413T21 22zm0-2h8v-2h-8zm0-4h8v-1h-8zM12 2l8 3v6h-2V6.375l-6-2.25l-6 2.25V11.1q0 2.025.813 3.863T9 18.1v2.25q0 .175.05.35q-2.275-1.5-3.662-4.075T4 11.1V5z");
}

</style>
