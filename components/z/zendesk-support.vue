<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hwy5nxb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zendesk-support" /></template>
<style>
.hwy5nxb-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 38.95l18.2-20.8v20.8zm20.8 0a9.1 9.1 0 0 1 9.1-9.1h0a9.1 9.1 0 0 1 9.1 9.1zm18.2-29.9l-18.2 20.8V9.05zm-20.8 0a9.1 9.1 0 0 1-9.1 9.1h0a9.1 9.1 0 0 1-9.1-9.1z");
}

</style>
