<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f94qlxs-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vocabulary" /></template>
<style>
.f94qlxs-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.811 6.922H42.5m-2.844 0L28.278 41.078h-8.545L7.64 6.922m9.249 0L28.233 40.72M5.5 6.922h14.233");
}

</style>
