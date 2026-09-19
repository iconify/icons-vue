<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oy6ln6bcp"/><path class="mscqs3k7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:randochat" /></template>
<style>
.mscqs3k7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.759 27.557c.141.643.22 1.303.22 1.978c0 6.124-6.156 11.086-13.74 11.086c-2.245 0-4.35-.44-6.202-1.21l-6.155 2.733l1.162-6.187C6.458 34.136 5.5 31.922 5.5 29.535c0-5.009 4.114-9.248 9.751-10.614");
}

.oy6ln6bcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.95 23.374c1.6-1.814 2.55-4.027 2.55-6.424c0-6.127-6.15-11.094-13.736-11.094S15.03 10.823 15.03 16.95s6.15 11.095 13.735 11.095c2.235 0 4.34-.44 6.204-1.206l6.145 2.724z");
}

</style>
