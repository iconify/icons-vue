<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1olohblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-hexagon" /></template>
<style>
.v1olohblh {
  fill: currentColor;
  d: path("M16.05 3h-8.1c-.71 0-1.37.38-1.73 1l-4.04 7c-.36.62-.36 1.38 0 2l4.04 7c.36.62 1.02 1 1.73 1h8.09c.71 0 1.37-.38 1.73-1l4.04-7c.36-.62.36-1.38 0-2l-4.04-7c-.35-.62-1.01-1-1.72-1");
}

</style>
