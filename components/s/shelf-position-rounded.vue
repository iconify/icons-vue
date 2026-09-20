<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4iurovta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shelf-position-rounded" /></template>
<style>
.r4iurovta {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19v-3h18v3q0 .825-.587 1.413T19 21zm11.5-7V3H19q.825 0 1.413.588T21 5v9zM3 14V5q0-.825.588-1.412T5 3h2.5v11zm6.5 0V3h5v11z");
}

</style>
