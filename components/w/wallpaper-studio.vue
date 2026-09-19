<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jtjcr3bou"/><path class="ymfej6bap"/><path class="u6b8f2bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallpaper-studio" /></template>
<style>
.jtjcr3bou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.565 14.505l2.96-5.323c.903-1.624 3.236-1.634 4.154-.017l8.342 14.704m-6.988 13.518c2.521 3.658 8.073 3.54 10.405-.379l5.658-11.304");
}

.u6b8f2bkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.78 21.682a4.41 4.41 0 0 1-2.44 6.36h0a4.41 4.41 0 0 1-5.233-2.007l-1.23-2.166l-8.342-14.704c-.917-1.617-3.25-1.607-4.154.018l-4.58 8.236c-.405.728-.4 1.614.011 2.337l9.771 17.159c2.35 4.126 8.278 4.18 10.702.097l5.75-11.506m9.889-3.824a4.41 4.41 0 0 1-2.44 6.36h0a4.41 4.41 0 0 1-5.234-2.007l-1.229-2.166");
}

.ymfej6bap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.667 14.432l2.919-5.25c.904-1.624 3.237-1.634 4.154-.017l7.183 12.517m-10.143 0a4.41 4.41 0 0 1-2.44 6.36h0a4.41 4.41 0 0 1-5.233-2.007");
}

</style>
