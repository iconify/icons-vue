<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1tod1bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:task-outline-sharp" /></template>
<style>
.q1tod1bdp {
  fill: currentColor;
  d: path("m10.95 18l5.65-5.65l-1.45-1.45l-4.225 4.225l-2.1-2.1L7.4 14.45zM4 22V2h10l6 6v14zm9-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
