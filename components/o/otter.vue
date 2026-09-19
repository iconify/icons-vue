<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ugj4e4oev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:otter" /></template>
<style>
.ugj4e4oev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.076 23.98a8.28 8.28 0 1 1-.004-.24m4.375-7.698l.09 15.916m6.654-15.916l.09 16.096m6.475-11.06l.09 5.935m6.474-8.003l.18 10.16");
}

</style>
