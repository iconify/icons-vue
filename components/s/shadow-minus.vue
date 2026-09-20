<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqahodb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shadow-minus" /></template>
<style>
.kqahodb4q {
  fill: currentColor;
  d: path("M4 22q-.825 0-1.412-.587T2 20V8q0-.825.588-1.412T4 6h2V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18h-2v2q0 .825-.587 1.413T16 22zm4-6h12V4H8zm2-5V9h8v2z");
}

</style>
