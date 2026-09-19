<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_vswpb3u"/><path class="mf1yjdbqf"/><path class="tri553iuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:welab-bank" /></template>
<style>
.g_vswpb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.3h7.8v7.8H4.5z");
}

.mf1yjdbqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 12.375L4.5 27.825v7.95h7.8l15.6-15.6v-7.8z");
}

.tri553iuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.7 12.45L20.1 27.9v7.95h7.8l15.6-15.6v-7.8z");
}

</style>
