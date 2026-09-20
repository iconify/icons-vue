<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rl4n-dboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:step-20-filled" /></template>
<style>
.rl4n-dboe {
  fill: currentColor;
  d: path("M13 2a1 1 0 0 0-1 1v4H8a1 1 0 0 0-1 1v4H3a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h12a3 3 0 0 0 3-3V3a1 1 0 0 0-1-1z");
}

</style>
