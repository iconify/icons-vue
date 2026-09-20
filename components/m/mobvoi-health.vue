<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i772mtbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobvoi-health" /></template>
<style>
.i772mtbhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.272 42.5a6.99 6.99 0 0 0 6.992-6.992V24.567a6.99 6.99 0 0 0-6.992-6.984H13.331a6.99 6.99 0 0 0-6.988 6.984a6.99 6.99 0 0 0 6.988 6.996h3.942V35.5a6.99 6.99 0 0 0 6.988 6.995h.011zm6.992-12.083h3.401c3.86 0 6.99-3.128 6.992-6.988a6.99 6.99 0 0 0-6.992-6.991h-3.938v-3.946A6.99 6.99 0 0 0 23.735 5.5h-.003a6.99 6.99 0 0 0-6.992 6.992v5.09");
}

</style>
