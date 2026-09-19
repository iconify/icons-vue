<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wuap5ze6o"/><path class="wf_etvbkc"/><path class="q0u3vh27o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:snitch" /></template>
<style>
.q0u3vh27o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 42.5V10.125a4.625 4.625 0 0 0-9.25 0v27.75a4.625 4.625 0 0 1-9.25 0V5.5");
}

.wf_etvbkc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 14.75H10.125a4.625 4.625 0 0 0 0 9.25h27.75a4.625 4.625 0 0 1 0 9.25H5.5");
}

.wuap5ze6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 14.75H10.125a4.625 4.625 0 0 0 0 9.25h27.75a4.625 4.625 0 0 1 0 9.25");
}

</style>
