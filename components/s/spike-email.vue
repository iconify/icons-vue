<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="txdn8bbsk"/><path class="a_t6e-vht"/><path class="h1v4hr_7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spike-email" /></template>
<style>
.a_t6e-vht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 0 5.802 35.412l-1.334 8.12l8.12-1.334a21.45 21.45 0 0 0 19.78 1.612");
}

.h1v4hr_7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.145 27.936c-1.444 3.522.907 5.417 2.93 5.877c2.467.56 7.425-2.019 7.425-9.813");
}

.txdn8bbsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.819 24a11.807 11.807 0 1 0-.672 3.937A11.8 11.8 0 0 0 35.82 24m1.902 16.552q.802-.665 1.537-1.406");
}

</style>
