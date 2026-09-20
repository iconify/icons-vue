<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpqxzodbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:power" /></template>
<style>
.gpqxzodbl {
  fill: currentColor;
  d: path("M9.5 21v-3L6 14.5V9q0-.825.588-1.412T8 7h1L8 8V3h2v4h4V3h2v5l-1-1h1q.825 0 1.413.588T18 9v5.5L14.5 18v3z");
}

</style>
