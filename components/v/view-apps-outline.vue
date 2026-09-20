<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_r603nva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-apps-outline" /></template>
<style>
.c_r603nva {
  fill: currentColor;
  d: path("M1 20V4l6 1v14zm8-1V5h6v14zm14 1l-6-1V5l6-1zM3 17.625l2-.325V6.7l-2-.35zM11 17h2V7h-2zm10 .65V6.35l-2 .35v10.6zm-18-.025l2-.325zM11 17h2zm10 .65l-2-.35z");
}

</style>
