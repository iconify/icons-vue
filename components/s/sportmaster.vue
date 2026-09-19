<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vhm37hbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sportmaster" /></template>
<style>
.vhm37hbkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 38.36l-27.015-13.7L4.579 38.113l13.383-5.321zm-39-23.045l22.155 11.553l10.378-11.716l-11.546 4.664zm23.55-2.062a3.61 3.61 0 0 1-3.61 3.61a3.611 3.611 0 0 1 0-7.223a3.61 3.61 0 0 1 3.61 3.613");
}

</style>
