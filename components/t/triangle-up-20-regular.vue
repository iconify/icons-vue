<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yx-22pqti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-up-20-regular" /></template>
<style>
.yx-22pqti {
  fill: currentColor;
  d: path("M8.682 2.785c.567-1.047 2.07-1.047 2.637 0l6.5 12a1.5 1.5 0 0 1-1.319 2.214H3.501a1.5 1.5 0 0 1-1.319-2.215zm1.758.477a.5.5 0 0 0-.879 0l-6.5 11.998a.5.5 0 0 0 .44.739H16.5a.5.5 0 0 0 .44-.739z");
}

</style>
