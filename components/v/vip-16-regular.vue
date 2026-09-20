<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r1357-agi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-16-regular" /></template>
<style>
.r1357-agi {
  fill: currentColor;
  d: path("M12.5 3A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 10.5v-5A2.5 2.5 0 0 1 3.5 3zm-9 1A1.5 1.5 0 0 0 2 5.5v5A1.5 1.5 0 0 0 3.5 12h9a1.5 1.5 0 0 0 1.5-1.5v-5A1.5 1.5 0 0 0 12.5 4zm2.803 2.026a.5.5 0 0 1 .894.448l-1.75 3.5a.5.5 0 0 1-.894 0l-1.75-3.5a.5.5 0 0 1 .894-.448L5 8.632zM8.5 5.75a.5.5 0 0 1 .5.5v3.5a.5.5 0 0 1-1 0v-3.5a.5.5 0 0 1 .5-.5m3.125 0a1.625 1.625 0 1 1 0 3.25H11v.75a.5.5 0 0 1-1 0v-3.5a.5.5 0 0 1 .5-.5zM11 8h.625a.625.625 0 1 0 0-1.25H11z");
}

</style>
