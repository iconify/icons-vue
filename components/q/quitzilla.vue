<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="smgf0hjzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quitzilla" /></template>
<style>
.smgf0hjzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.984 21.984l-3.988-3.988a8.492 8.492 0 1 0 0 12.008l12.008-12.008a8.492 8.492 0 1 1 0 12.008l-3.988-3.988");
}

</style>
