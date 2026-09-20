<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb60brbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-email" /></template>
<style>
.yb60brbbc {
  fill: currentColor;
  d: path("M3 21q-.825 0-1.412-.587T1 19V6.5h2V19h16.5v2zm4-4q-.825 0-1.412-.587T5 15V5q0-.825.588-1.412T7 3h14q.825 0 1.413.588T23 5v10q0 .825-.587 1.413T21 17zm7-4.7l7-4.875V5l-7 4.85L7 5v2.425z");
}

</style>
