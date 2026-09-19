<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d07o0bawj"/><path class="v4_3xbb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:superset" /></template>
<style>
.d07o0bawj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12L11.427 24.575m25.146-.001L25.147 35.999m-9.529-7.234l12.573-12.573a5.927 5.927 0 0 1 8.382 0l4.191 4.19a5.927 5.927 0 0 1 0 8.382L29.338 40.19");
}

.v4_3xbb9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.382 20.383L19.809 32.956a5.927 5.927 0 0 1-8.382 0l-4.191-4.192a5.927 5.927 0 0 1 0-8.381L19.809 7.81");
}

</style>
