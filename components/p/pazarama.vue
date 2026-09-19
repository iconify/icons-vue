<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="up03khmnw"/><circle class="uk_-kpbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pazarama" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uk_-kpbdx {
  cx: 26.111px;
  cy: 20.73px;
  r: 9.73px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.up03khmnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.16 20.73V37m19.46-16.27c0 5.374-4.356 9.73-9.73 9.73s-9.73-4.356-9.73-9.73S16.517 11 21.89 11s9.73 4.356 9.73 9.73");
}

</style>
