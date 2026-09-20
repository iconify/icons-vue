<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fy-0tsb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-ltr-90-20-filled" /></template>
<style>
.fy-0tsb6s {
  fill: currentColor;
  d: path("M14 3.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 0 0-2.5 0M15.25 7a.75.75 0 0 1 .75.75v9.5a.75.75 0 0 1-1.5 0v-9.5a.75.75 0 0 1 .75-.75M11 7.75a.75.75 0 0 0-1.5 0v9.5a.75.75 0 0 0 1.5 0zm-5 0a.75.75 0 0 0-1.5 0v9.5a.75.75 0 0 0 1.5 0zm4.25-3.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5M4 3.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 0 0-2.5 0");
}

</style>
