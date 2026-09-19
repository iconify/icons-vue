<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="x0n8jx7vz"/><path class="cldhysblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sobriety" /></template>
<style>
.cldhysblb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.175 12.591c-9.205.475-15.744 3.052-15.687 6.117c.112 5.977 10.267 5.77 11.024 9.33c.773 3.634-4.655 7.238-10.121 7.356c-6.056.13-9.566-.599-9.566-2.281s4.239-4.43 13.313-4.946");
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

.x0n8jx7vz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.22 19.008l-1.271.622l-.645 1.26l-.622-1.271l-1.26-.645l1.27-.622l.646-1.26l.622 1.271z");
}

</style>
