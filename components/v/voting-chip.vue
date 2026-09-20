<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahigksbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:voting-chip" /></template>
<style>
.ahigksbol {
  fill: currentColor;
  d: path("M8 19q-2.925 0-4.962-2.037T1 12t2.038-4.962T8 5h8q2.925 0 4.963 2.038T23 12t-2.037 4.963T16 19zm.25-4h1.5v-2.25H12v-1.5H9.75V9h-1.5v2.25H6v1.5h2.25zm7.25 0H17V9h-3v1.5h1.5z");
}

</style>
