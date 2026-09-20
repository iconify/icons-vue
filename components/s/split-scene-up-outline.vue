<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p60zg16xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-up-outline" /></template>
<style>
.p60zg16xn {
  fill: currentColor;
  d: path("M6 21q-.825 0-1.412-.587T4 19v-4h2v4h12v-4h2v4q0 .825-.587 1.413T18 21zm-4-8v-2h2V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v6h2v2zm16 6H6z");
}

</style>
