<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-p3_7b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quetta" /></template>
<style>
.p-p3_7b_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.289 32.36A18.3 18.3 0 0 0 42.293 24c0-10.16-8.236-18.398-18.397-18.398S5.5 13.84 5.5 24s8.236 18.398 18.396 18.398H42.5");
}

</style>
