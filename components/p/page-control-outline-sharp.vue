<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxme8ue4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-control-outline-sharp" /></template>
<style>
.rxme8ue4d {
  fill: currentColor;
  d: path("M2.588 13.413Q2 12.825 2 12t.588-1.412T4 10t1.413.588T6 12t-.587 1.413T4 14t-1.412-.587m1.874-.95q.188-.188.188-.463t-.187-.462T4 11.35t-.462.188T3.35 12t.188.463t.462.187t.463-.187m3.475.95Q7.35 12.825 7.35 12t.588-1.412T9.35 10t1.413.588T11.35 12t-.587 1.413T9.35 14t-1.412-.587m1.875-.95Q10 12.275 10 12t-.187-.462t-.463-.188t-.462.188T8.7 12t.188.463t.462.187t.463-.187m3.424.95q-.587-.588-.587-1.413t.588-1.412T14.65 10t1.413.588T16.65 12t-.587 1.413T14.65 14t-1.412-.587m1.875-.95q.187-.188.187-.463t-.187-.462t-.463-.188t-.462.188T14 12t.188.463t.462.187t.463-.187m3.475.95Q18 12.825 18 12t.588-1.412T20 10t1.413.588T22 12t-.587 1.413T20 14t-1.412-.587");
}

</style>
