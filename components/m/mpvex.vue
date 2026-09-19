<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zbqznkb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mpvex" /></template>
<style>
.zbqznkb8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.624 7.98l.082 32.043c0 .264.2.477.445.477a.4.4 0 0 0 .223-.065l25.781-16.097a.498.498 0 0 0-.002-.829L11.289 7.564a.43.43 0 0 0-.607.176a.5.5 0 0 0-.06.24z");
}

</style>
