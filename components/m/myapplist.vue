<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ko955srlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myapplist" /></template>
<style>
.ko955srlu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2Zm-11-11l11 11m-15.13 7.02h11.21M24.37 34.84h11.21m-22.41-.09l3.1 3.1m0 0l6.03-6.03m-9.13-9.39l3.1 3.1m0 0l6.03-6.02");
}

</style>
