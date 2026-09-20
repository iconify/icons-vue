<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2vdfzblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wall-art" /></template>
<style>
.f2vdfzblb {
  fill: currentColor;
  d: path("M4 22q-.825 0-1.412-.587T2 20V8q0-.825.588-1.412T4 6h4l4-4l4 4h4q.825 0 1.413.588T22 8v12q0 .825-.587 1.413T20 22zm2-4h12l-3.75-5l-3 4L9 14zm12.563-5.437Q19 12.125 19 11.5t-.437-1.062T17.5 10t-1.062.438T16 11.5t.438 1.063T17.5 13t1.063-.437M10.1 6h3.8L12 4.1z");
}

</style>
