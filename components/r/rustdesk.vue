<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g64ayebsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rustdesk" /></template>
<style>
.g64ayebsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.132 3.08a21.475 21.475 0 0 0 0 41.84m9.734.001a21.475 21.475 0 0 0 0-41.842");
}

</style>
