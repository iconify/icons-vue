<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="stc29ybvs"/><g class="y9tr6bcfx"><path class="g7yq545_p"/><path class="l4hrmx44z"/></g><path class="qwa0l-dfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myq" /></template>
<style>
.g7yq545_p {
  d: path("M28.748 25.086v3.912a2.897 2.897 0 0 1-4.946 2.048");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.l4hrmx44z {
  d: path("M28.748 20.306v4.78a2.897 2.897 0 1 1-5.794 0v-4.78");
}

.qwa0l-dfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.5 27.694l-3.839-3.793m0-7.796za3.84 3.84 0 0 1 3.839 3.839v3.911a3.839 3.839 0 0 1-7.678 0v-3.911a3.84 3.84 0 0 1 3.84-3.839");
}

.stc29ybvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 22.914a2.897 2.897 0 1 1 5.794 0v4.78M9.5 20.016v7.678m5.794-4.78a2.897 2.897 0 1 1 5.794 0v4.78");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
