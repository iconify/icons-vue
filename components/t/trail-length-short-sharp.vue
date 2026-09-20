<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmv-7_tey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trail-length-short-sharp" /></template>
<style>
.pmv-7_tey {
  fill: currentColor;
  d: path("M15 17q-1.825 0-3.187-1.137T10.1 13H4v-2h6.1q.125-.575.338-1.075T11 9H6V7h9q2.075 0 3.538 1.463T20 12t-1.463 3.538T15 17m-8 0v-2h3v2z");
}

</style>
