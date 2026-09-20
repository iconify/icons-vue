<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jr-52bb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-cable-car-20-regular" /></template>
<style>
.jr-52bb_q {
  fill: currentColor;
  d: path("M17.434 3.004a.5.5 0 1 1 .132.992L12 4.738V6a3 3 0 0 1-.764 2H13a3 3 0 0 1 3 3v4a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-4a3 3 0 0 1 3-3h2a2 2 0 0 0 2-2V4.871L2.566 5.996a.5.5 0 1 1-.132-.992L11 3.862V3.5a.5.5 0 1 1 1 0v.229zM15 11a2 2 0 0 0-2-2H7a2 2 0 0 0-2 2v2h10zM5 14v1a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-1z");
}

</style>
