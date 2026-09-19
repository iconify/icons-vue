<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lz4jn1rbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:milanote" /></template>
<style>
.lz4jn1rbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.83 41.83L7.207 7.207c-.63-.63-1.707-.184-1.707.707V40.5a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2V7.914c0-.89-1.077-1.337-1.707-.707L6.086 41.914");
}

</style>
