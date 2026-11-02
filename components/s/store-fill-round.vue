<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1mtn1e3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-fill-round" /></template>
<style>
.q1mtn1e3e {
  fill: currentColor;
  d: path("M6 2h2v8H6v7a3 3 0 0 0 3 3v-3a3 3 0 1 1 6 0v3a3 3 0 0 0 3-3v-7h-2V2h2a4 4 0 0 1 2 7.465V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V9.465A4.001 4.001 0 0 1 6 2m4 0h4v8h-4Zm1 18h2v-3a1 1 0 0 0-2 0Z");
}

</style>
