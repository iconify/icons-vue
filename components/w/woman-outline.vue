<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9641dbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:woman-outline" /></template>
<style>
.h9641dbnk {
  fill: currentColor;
  d: path("M10 22v-6H7l3.05-7.7q.25-.6.775-.95T12 7t1.175.35t.775.95L17 16h-3v6zm.588-16.588Q10 4.825 10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6t-1.412-.587");
}

</style>
