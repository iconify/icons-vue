<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6xoltbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tkton-wallet" /></template>
<style>
.s6xoltbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 18.332h39m-39 0l6.204-11.896h26.591L43.5 18.332L24 41.564zM22.799 6.436l-6.123 11.896m14.648 0L25.201 6.436M24 18.332v23.232");
}

</style>
