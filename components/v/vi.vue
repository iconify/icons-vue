<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="wwtw2abnq"/><path class="pdg919lsi"/><circle class="z7cfyip2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vi" /></template>
<style>
.pdg919lsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.018 8.635L18.55 26.507L14.082 8.635a.51.51 0 0 0-.492-.384H5.507a.507.507 0 0 0-.492.63l5.832 23.327a.51.51 0 0 0 .492.384h14.422a.51.51 0 0 0 .492-.384l5.832-23.327a.507.507 0 0 0-.492-.63H23.51a.51.51 0 0 0-.492.384");
}

.wwtw2abnq {
  width: 9.128px;
  height: 24.342px;
  x: 33.872px;
  y: 8.251px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.507px;
}

.z7cfyip2v {
  cx: 38.436px;
  cy: 39.185px;
  r: 4.564px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
