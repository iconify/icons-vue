<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q1-swrbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:treinta" /></template>
<style>
.q1-swrbhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.883 14.174h9.797c-.618 7.22-4.846 9.03-9.797 9.758V43.5a9.466 9.466 0 0 1-9.563-9.673V14.173A9.466 9.466 0 0 1 23.883 4.5zm9.797 25.517a3.814 3.814 0 1 1-3.814-3.809a3.81 3.81 0 0 1 3.814 3.81");
}

</style>
