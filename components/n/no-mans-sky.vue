<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qupm5fbeo"/><path class="nh1_8ac8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:no-mans-sky" /></template>
<style>
.nh1_8ac8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.45a5.666 5.666 0 0 0 4.698-8.834");
}

.qupm5fbeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.466 18.784L24 13.689M24 44.5l12.535-25.716L24 3.5L11.466 18.784zm12.535-25.716L24 13.689M24 3.5v41");
}

</style>
