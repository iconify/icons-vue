<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek6d2zunz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:things-to-do" /></template>
<style>
.ek6d2zunz {
  fill: currentColor;
  d: path("M2 21v-2h4v-4H4v-2h2.1q.3-1.875 1.663-3.238T11 8.1V3h7v4h-5v1.1q1.875.3 3.238 1.663T17.9 13H20v2h-2v4h4v2zm6-2h3v-4H8zm5 0h3v-4h-3z");
}

</style>
