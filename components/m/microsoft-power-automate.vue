<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pihwpcc_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-power-automate" /></template>
<style>
.pihwpcc_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.92 8.5a1.5 1.5 0 0 0-1.172 2.438L17.199 24L6.748 37.062A1.5 1.5 0 0 0 7.92 39.5h20.959a1.5 1.5 0 0 0 1.172-.563l11.2-14a1.5 1.5 0 0 0 0-1.875l-11.2-14a1.5 1.5 0 0 0-1.172-.563zm21.564.145L17.2 24m18.6-7.75L17.196 39.5");
}

</style>
