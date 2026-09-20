<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nhnjymbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-header-1-20-filled" /></template>
<style>
.nhnjymbbh {
  fill: currentColor;
  d: path("M9.25 4a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-1.5 0V10.5h-5v4.75a.75.75 0 0 1-1.5 0V4.75a.75.75 0 0 1 1.5 0V9h5V4.75A.75.75 0 0 1 9.25 4m7.111.008a.75.75 0 0 1 .64.742v10.5a.75.75 0 0 1-1.5 0V7.463a9.5 9.5 0 0 1-1.813 1.65l-.066.041a.75.75 0 0 1-.794-1.27l.388-.288a7.7 7.7 0 0 0 1.786-1.985c.205-.33.341-.611.425-.805q.061-.145.088-.217l.02-.059a.75.75 0 0 1 .826-.522");
}

</style>
