<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ukj_7hb7x"/><path class="oazw04shg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yasnac" /></template>
<style>
.oazw04shg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.381 24.026V10.365L24 4.5l15.619 5.865v13.66C39.14 33.028 32.03 41.566 24 43.5C15.969 41.565 8.86 33.027 8.381 24.026");
}

.ukj_7hb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.296 18.865l-9.403 9.404l-5.196-5.304");
}

</style>
