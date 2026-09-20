<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tc-h1hkqo"/><path class="wgjvznbin"/><path class="ahki9cbhd"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smarthome" /></template>
<style>
.ahki9cbhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.666 33.637a1.854 1.854 0 1 1 3.708 0v3.059m.463-12.651c0-1.024.83-1.854 1.854-1.854m-1.854 0v4.913m-21.19-.813c.455.592 1.025.813 1.818.813h1.098a1.85 1.85 0 0 0 1.85-1.85v-.008a1.85 1.85 0 0 0-1.85-1.85h-1.211a1.85 1.85 0 0 1-1.852-1.852c0-1.025.831-1.856 1.856-1.856h1.092c.793 0 1.363.22 1.818.812m21.029.161v5.516c0 .512.415.927.927.927h.278m-2.178-4.913h1.946M30.02 25.25a1.854 1.854 0 1 1-3.708 0v-1.205a1.854 1.854 0 1 1 3.708 0m0 3.059v-4.913m7.237 13.569a1.854 1.854 0 0 1-3.465-.918v-1.205a1.854 1.854 0 1 1 3.708 0v.602h-3.708m-15.96-.602a1.854 1.854 0 1 1 3.707 0v1.205a1.854 1.854 0 1 1-3.708 0zm16.029-16.651l-8.721-5.36c-.7-.43-1.58-.43-2.28 0l-8.721 5.36");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.tc-h1hkqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 29.28v7.416m4.913-7.416v7.416M10.5 32.974h4.913m1.744-8.929a1.854 1.854 0 1 1 3.708 0v3.059m-3.708-4.913v4.913");
}

.wgjvznbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.865 24.045a1.854 1.854 0 1 1 3.708 0v3.059m-.615 6.533a1.854 1.854 0 1 1 3.708 0v3.059m-3.708-4.913v4.913");
}

</style>
