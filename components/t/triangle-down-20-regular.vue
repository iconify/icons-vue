<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y48lexoan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-down-20-regular" /></template>
<style>
.y48lexoan {
  fill: currentColor;
  d: path("M8.682 17.215c.567 1.047 2.07 1.047 2.637 0l6.5-12A1.5 1.5 0 0 0 16.5 3.003H3.501a1.5 1.5 0 0 0-1.319 2.214zm1.758-.477a.5.5 0 0 1-.879 0L3.061 4.74a.5.5 0 0 1 .44-.74H16.5a.5.5 0 0 1 .44.739z");
}

</style>
