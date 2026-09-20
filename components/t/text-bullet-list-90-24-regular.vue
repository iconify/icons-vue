<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-jirb1ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-90-24-regular" /></template>
<style>
.x-jirb1ak {
  fill: currentColor;
  d: path("M6.5 3.25a1.25 1.25 0 1 1-2.498 0a1.25 1.25 0 0 1 2.499 0M6 6.75v14.5a.75.75 0 0 1-1.493.102l-.006-.102V6.75a.75.75 0 0 1 1.493-.102zm7-3.5a1.25 1.25 0 1 1-2.498 0a1.25 1.25 0 0 1 2.499 0m-.5 3.5v14.5a.75.75 0 0 1-1.493.102l-.006-.102V6.75a.75.75 0 0 1 1.493-.102zm7-3.5a1.25 1.25 0 1 1-2.498 0a1.25 1.25 0 0 1 2.499 0m-.5 3.5v14.5a.75.75 0 0 1-1.493.102l-.007-.102V6.75a.75.75 0 0 1 1.494-.102z");
}

</style>
