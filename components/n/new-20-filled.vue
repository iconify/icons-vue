<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tpnnbdb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:new-20-filled" /></template>
<style>
.tpnnbdb8o {
  fill: currentColor;
  d: path("M15.5 2.75a.75.75 0 0 1 .75.75v8a.75.75 0 0 1-1.5 0v-8a.75.75 0 0 1 .75-.75M5.97 5.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 1 1-1.06 1.06l-6-6a.75.75 0 0 1 0-1.06M3.5 14.75a.75.75 0 0 0 0 1.5h8a.75.75 0 0 0 0-1.5z");
}

</style>
