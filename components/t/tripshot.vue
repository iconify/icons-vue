<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b4uh9jb9d"/><path class="apcutymba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tripshot" /></template>
<style>
.apcutymba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.592 8.333l18.703 7.91c1.304.551 2.08 2.087 1.844 3.656l-3.33 22.252");
}

.b4uh9jb9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.593 8.333a2.17 2.17 0 0 1 .128-1.585c.299-.594.848-.962 1.446-.967l33.658-.28c.598-.007 1.153.356 1.452.95s.297 1.325-.006 1.915l-17.018 33.17c-.307.6-.87.966-1.478.964a1.57 1.57 0 0 1-.966-.348");
}

</style>
