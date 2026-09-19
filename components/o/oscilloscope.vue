<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bc07uv-xm"/><path class="jr6k_6diz"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oscilloscope" /></template>
<style>
.bc07uv-xm {
  fill: currentColor;
  d: path("M11.709 4.998L7 5h4.709zM36.289 43v.002l4.71-.002z");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jr6k_6diz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.542 10.826c10.663 0 10.486 26.348 20.972 26.348m7.986-7.366c-1.974 4.168-4.333 7.366-7.986 7.366M13.542 10.826c-3.675 0-6.062 3.13-8.042 7.232");
}

</style>
