<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itxu8ccdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:water-heater-fill-round" /></template>
<style>
.itxu8ccdb {
  fill: currentColor;
  d: path("M10 3v2h4V3a1 1 0 0 1 2 0v2.416A5 5 0 0 1 19 10v7a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 22h-4a5 5 0 0 1-5-5v-7c0-1.99 1.175-3.79 3-4.584V3a1 1 0 0 1 2 0m.5 10.5a1.002 1.002 0 0 0-1.707-.707C8.22 13.366 8 14.21 8 15a4 4 0 0 0 8 0c0-1.374-.29-2.704-1.293-3.707a1 1 0 0 0-.107-.093c-.801-.601-1.42-1.399-1.619-2.396a1.002 1.002 0 0 0-1.606-.585c-.649.52-1.233 1.175-1.486 1.983c-.238.763-.138 1.535.217 2.245q.084.166.175.328c.151.27.219.408.219.725");
}

</style>
