<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn5bzcc8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pip-exit-outline" /></template>
<style>
.bn5bzcc8l {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18v-7h2v7h16V6h-9V4h9q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm13.075-3.5l1.425-1.425L15.4 12H18v-2h-6v6h2v-2.575zM2 9V4h7v5zm10 3");
}

</style>
