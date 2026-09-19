<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a71jm51qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:visitluxembourg" /></template>
<style>
.a71jm51qv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h7.276l7.367 7.36v7.284h-7.24L5.5 12.85zm36.998.001l-7.274.001l-7.367 7.358v7.284h7.24L42.5 12.85zM5.5 42.5h7.276l7.367-7.359l-.002-7.283h-7.238L5.5 35.15zm37 0h-7.276l-7.367-7.359v-7.284h7.241l7.401 7.294z");
}

</style>
