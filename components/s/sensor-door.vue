<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1h1whk8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sensor-door" /></template>
<style>
.h1h1whk8f {
  fill: currentColor;
  d: path("M4 22V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v18zm11.5-8.5q.625 0 1.063-.437T17 12t-.437-1.062T15.5 10.5t-1.062.438T14 12t.438 1.063t1.062.437");
}

</style>
