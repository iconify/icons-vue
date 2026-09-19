<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ci3a-5baq"/><path class="guvt6o97o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openwort" /></template>
<style>
.ci3a-5baq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.635 20.039L24 5.5l-9.25 37l-9.25-37m28.907 32.373L33.25 42.5l-1.157-4.627M42.5 5.5l-3.635 14.539M22.573 31.161h19.83v4.412h-19.83z");
}

.guvt6o97o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.573 26.75h19.83v4.412h-19.83zm0-4.412h19.83v4.412h-19.83z");
}

</style>
