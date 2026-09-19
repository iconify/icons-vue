<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fsvq07bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yanavi" /></template>
<style>
.fsvq07bqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 5.5l-37 15.83l19 2.22zm0 0l-18 18.05l2.23 19zm-37 15.83L20 28l6.68 14.5l-2.23-18.95z");
}

</style>
