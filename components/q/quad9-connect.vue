<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ttei64bbw"/><path class="fi3_v8c0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quad9-connect" /></template>
<style>
.fi3_v8c0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.258 24V11L24 4.5L12.742 11v13L24 17.5zM24 17.5v-13m0 13L12.742 11m22.516 0L24 17.5");
}

.ttei64bbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.258 37V24L24 17.5L12.742 24v13L24 43.5zm0-13L12.742 37m0-13l22.516 13M24 43.5v-26");
}

</style>
