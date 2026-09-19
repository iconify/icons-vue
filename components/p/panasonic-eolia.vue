<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rja6csn6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:panasonic-eolia" /></template>
<style>
.rja6csn6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 28c0 2.77-2.23 5-5 5h-29c-2.77 0-5-2.23-5-5V17c0-1.108.892-2 2-2h35c1.108 0 2 .892 2 2zm-32.934-.73h26.868");
}

</style>
