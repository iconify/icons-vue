<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pstv7pbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:multiplier-1x-20-regular" /></template>
<style>
.pstv7pbwb {
  fill: currentColor;
  d: path("M8 6.5a.5.5 0 0 0-.898-.302a10 10 0 0 0-.22.306c-.33.472-.702 1.005-1.64 1.567a.5.5 0 1 0 .515.858c.545-.327.941-.66 1.243-.972V13.5a.5.5 0 1 0 1 0zm2.854 3.646a.5.5 0 0 0-.708.707L11.293 12l-1.147 1.146a.5.5 0 0 0 .708.707L12 12.707l1.146 1.146a.5.5 0 0 0 .708-.707L12.707 12l1.147-1.147a.5.5 0 0 0-.708-.707L12 11.293z");
}

</style>
