<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9mw40byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zerocam" /></template>
<style>
.k9mw40byw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 36c-6.627 0-12-5.373-12-12s5.373-12 12-12h17c6.627 0 12 5.373 12 12s-5.373 12-12 12z");
}

</style>
