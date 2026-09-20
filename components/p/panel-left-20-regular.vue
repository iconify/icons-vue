<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ha7ewhb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-20-regular" /></template>
<style>
.ha7ewhb2z {
  fill: currentColor;
  d: path("M15 4a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zM8.5 15H15a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2H8.5zM5 5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h2.5V5z");
}

</style>
