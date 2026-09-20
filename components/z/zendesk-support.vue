<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hfwzo-b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zendesk-support" /></template>
<style>
.hfwzo-b1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 38.95l18.2-20.8v20.8zm20.8 0a9.1 9.1 0 1 1 18.2 0zm18.2-29.9l-18.2 20.8V9.05zm-20.8 0a9.1 9.1 0 1 1-18.2 0z");
}

</style>
