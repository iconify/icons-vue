<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc0emhv5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-cast" /></template>
<style>
.uc0emhv5s {
  fill: currentColor;
  d: path("M23 3H1v5h2V5h18v14h-7v2h9zM1 18v3h3c0-1.66-1.34-3-3-3m0-4v2c2.76 0 5 2.24 5 5h2c0-3.87-3.13-7-7-7m0-4v2a9 9 0 0 1 9 9h2c0-6.08-4.93-11-11-11");
}

</style>
