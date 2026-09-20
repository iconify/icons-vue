<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obl35w8qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:snooze-16-regular" /></template>
<style>
.obl35w8qd {
  fill: currentColor;
  d: path("M4.001 8h2.5a.5.5 0 0 1 .432.753l-.048.067L5.068 11h1.433a.5.5 0 0 1 .09.992L6.5 12H4a.5.5 0 0 1-.432-.753l.048-.067L5.433 9H4.001a.5.5 0 0 1-.09-.992zh2.5zm5-5h3.5a.5.5 0 0 1 .452.714l-.042.073L9.96 8h2.54a.5.5 0 0 1 .09.992L12.5 9H9a.5.5 0 0 1-.452-.714l.042-.073L11.541 4H9a.5.5 0 0 1-.09-.992zh3.5z");
}

</style>
