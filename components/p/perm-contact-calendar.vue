<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj0ksabrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-contact-calendar" /></template>
<style>
.uj0ksabrq {
  fill: currentColor;
  d: path("M5 18.85q1.35-1.325 3.138-2.087T12 16t3.863.763T19 18.85V6H5zm4.525-5.875Q8.5 11.95 8.5 10.5t1.025-2.475T12 7t2.475 1.025T15.5 10.5t-1.025 2.475T12 14t-2.475-1.025M5 22q-.825 0-1.412-.587T3 20V6q0-.825.588-1.412T5 4h1V2h2v2h8V2h2v2h1q.825 0 1.413.588T21 6v14q0 .825-.587 1.413T19 22z");
}

</style>
