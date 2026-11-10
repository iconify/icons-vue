<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fvbo0w6nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mevo" /></template>
<style>
.fvbo0w6nn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 17.788h2.36v8.207m0-8.205l4.082 4.08l4.08-4.08v8.206m14.425-8.206h-3.25m-.787 11.187a4.216 4.216 0 1 1 1.235-3.006H22.43m4.88-8.181l2.989 8.182h1.115l2.989-8.183h1.36m7.737 8.206a4.216 4.216 0 1 1-8.433 0a4.216 4.216 0 0 1 8.433 0");
}

</style>
