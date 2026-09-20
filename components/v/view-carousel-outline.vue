<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge_a6bcyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-carousel-outline" /></template>
<style>
.ge_a6bcyl {
  fill: currentColor;
  d: path("M2 15V9q0-.825.588-1.412T4 7t1.413.588T6 9v6q0 .825-.587 1.413T4 17t-1.412-.587T2 15m7 4q-.825 0-1.412-.587T7 17V7q0-.825.588-1.412T9 5h6q.825 0 1.413.588T17 7v10q0 .825-.587 1.413T15 19zm9-4V9q0-.825.588-1.412T20 7t1.413.588T22 9v6q0 .825-.587 1.413T20 17t-1.412-.587T18 15m-9 2h6V7H9zm3-5");
}

</style>
