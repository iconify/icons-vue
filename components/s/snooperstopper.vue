<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p9sigpgjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:snooperstopper" /></template>
<style>
.p9sigpgjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.68 12.92a21.2 21.2 0 0 1 13.81 10c-9.42 16.33-29.63 16.2-39 0a21.35 21.35 0 0 1 13.82-9.95A10.08 10.08 0 0 0 24 31.33a10.08 10.08 0 0 0 10.07-10.08a10.1 10.1 0 0 0-4.4-8.33Zm-4.32 8.4c0 3.61 3.19.77 3.42.55c.5-.5 1.6 0 1 1c-3.22 5.57-3.92 5-8 5c-2.3 0-2.3-2.64-2.3-6.58m0-3.75v3.75m1.89-5.85v5.85m2-7v7m2.07-5.84v5.84");
}

</style>
