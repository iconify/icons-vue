<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q30q40bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:scb-easy" /></template>
<style>
.q30q40bhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.901 11.115C3.761 24.34 10.15 43.312 22.625 35.546V42.5H15.03c-7.801-3.502-8.596-2.173-9.666-6.776C6.848 29.76 8.088 24.36 9.839 17.782C15.318 12.469 19.513 9.132 24 5.5c4.487 3.632 8.683 6.969 14.16 12.282c1.752 6.578 2.993 11.98 4.476 17.942c-1.07 4.603-1.865 3.274-9.666 6.776h-7.595v-6.954C37.85 43.312 44.239 24.34 24 11.115C3.762 24.34 10.15 43.312 22.625 35.546V42.5H15.03c-7.801-3.502-8.596-2.173-9.666-6.776C6.848 29.76 8.088 24.36 9.839 17.782c5.479-5.313 9.674-8.65 14.062-12.282");
}

</style>
