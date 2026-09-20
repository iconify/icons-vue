<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aj05txblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-20-regular" /></template>
<style>
.aj05txblq {
  fill: currentColor;
  d: path("M11.5 2a.5.5 0 0 1 0 1h-1v14h1a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1h1V3h-1a.5.5 0 0 1 0-1zm-3 3H5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h3.5v1H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h3.5zM15 4a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-3.5v-1H15a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2h-3.5V4z");
}

</style>
