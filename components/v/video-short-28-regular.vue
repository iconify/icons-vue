<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="la1bq3bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-28-regular" /></template>
<style>
.la1bq3bsr {
  fill: currentColor;
  d: path("M20.25 2A3.75 3.75 0 0 1 24 5.75v16.5A3.75 3.75 0 0 1 20.25 26H7.75A3.75 3.75 0 0 1 4 22.25V5.75A3.75 3.75 0 0 1 7.75 2zM7.75 3.5A2.25 2.25 0 0 0 5.5 5.75v16.5a2.25 2.25 0 0 0 2.25 2.25h12.5a2.25 2.25 0 0 0 2.25-2.25V5.75a2.25 2.25 0 0 0-2.25-2.25zM11 11.501a1.5 1.5 0 0 1 2.295-1.271l4 2.497a1.5 1.5 0 0 1 0 2.546l-4 2.499A1.5 1.5 0 0 1 11 16.499z");
}

</style>
