<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hr3-ijbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-32-regular" /></template>
<style>
.hr3-ijbgi {
  fill: currentColor;
  d: path("M17 19a1 1 0 0 1 1 1v9a1 1 0 0 1-2 0v-9a1 1 0 0 1 1-1m8 0a5.5 5.5 0 0 1 4.53 8.616l.677.677a1 1 0 0 1-1.414 1.414l-.677-.676A5.5 5.5 0 1 1 25 19M13.732 2.164a4.5 4.5 0 0 1 4.536 0l8.5 4.958A4.5 4.5 0 0 1 29 11.01V17a1 1 0 1 1-2 0v-5.99a2.5 2.5 0 0 0-1.24-2.16l-2.5-1.458a2.5 2.5 0 0 0-2.52 0l-8.5 4.958A2.5 2.5 0 0 0 11 14.51v9.979a2.5 2.5 0 0 0 1.224 2.149l1.28.747a1.001 1.001 0 0 1-1.008 1.729l-7.264-4.238A4.5 4.5 0 0 1 3 20.99v-9.98c0-1.6.85-3.081 2.232-3.888zM25 21a3.5 3.5 0 1 0 1.664 6.578l-1.371-1.37a1 1 0 0 1 1.414-1.415l1.371 1.371A3.5 3.5 0 0 0 25 21M17.26 3.892a2.5 2.5 0 0 0-2.52 0L6.24 8.85A2.5 2.5 0 0 0 5 11.01v9.979a2.5 2.5 0 0 0 1.24 2.16l2.769 1.614A5 5 0 0 1 9 24.489V14.51c0-1.6.85-3.081 2.232-3.888l8.5-4.958q.146-.084.296-.157z");
}

</style>
