<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_x7o5bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shadow-add" /></template>
<style>
.a_x7o5bdj {
  fill: currentColor;
  d: path("M13 14v-3h-3V9h3V6h2v3h3v2h-3v3zm-9 8q-.825 0-1.412-.587T2 20V8q0-.825.588-1.412T4 6h2V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18h-2v2q0 .825-.587 1.413T16 22zm4-6h12V4H8z");
}

</style>
