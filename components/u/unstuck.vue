<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmx3f-b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unstuck" /></template>
<style>
.nmx3f-b5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.203 33.916c-2.207 3.104-9.671 5.263-18.2 5.263S8.013 37.02 5.806 33.915M42.5 25.543V15.291c0-3.432-2.874-6.214-6.42-6.214h0c-3.545 0-6.419 2.782-6.419 6.214m0 10.252V9.077M5.5 8.82v10.578c0 3.54 2.876 6.41 6.423 6.41h0c3.547 0 6.423-2.87 6.423-6.41V8.82m0 10.578v6.41");
}

</style>
