<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xrgyn5baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-bottom-row-32-regular" /></template>
<style>
.xrgyn5baf {
  fill: currentColor;
  d: path("M9 4a5 5 0 0 0-5 5v14a5 5 0 0 0 5 5h14a5 5 0 0 0 5-5V9a5 5 0 0 0-5-5zM6 9a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10H6zm0 14v-2h5v5H9a3 3 0 0 1-3-3m7 3v-5h6v5zm8 0v-5h5v2a3 3 0 0 1-3 3z");
}

</style>
