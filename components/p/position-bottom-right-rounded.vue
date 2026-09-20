<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-7xvebkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:position-bottom-right-rounded" /></template>
<style>
.s-7xvebkk {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm5.5-4h6q.625 0 1.063-.437T18 15.5t-.437-1.062T16.5 14h-6q-.625 0-1.062.438T9 15.5t.438 1.063T10.5 17");
}

</style>
