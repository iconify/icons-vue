<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cxero_mkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:s-kaupat" /></template>
<style>
.cxero_mkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 43.5c9.941 0 18-6.716 18-15v-9c0-1.933 2.239-3.5 5-3.5v-6C29.149 10 24 14.253 24 19.5v9c0 5.247-5.149 9.5-11.5 9.5v-6c2.761 0 5-1.567 5-3.5v-9c0-8.284 8.059-15 18-15");
}

</style>
