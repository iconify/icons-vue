<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3m5_ybuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:more-vert-outline-rounded" /></template>
<style>
.m3m5_ybuk {
  fill: currentColor;
  d: path("M12 20q-.825 0-1.412-.587T10 18t.588-1.412T12 16t1.413.588T14 18t-.587 1.413T12 20m0-6q-.825 0-1.412-.587T10 12t.588-1.412T12 10t1.413.588T14 12t-.587 1.413T12 14m0-6q-.825 0-1.412-.587T10 6t.588-1.412T12 4t1.413.588T14 6t-.587 1.413T12 8");
}

</style>
