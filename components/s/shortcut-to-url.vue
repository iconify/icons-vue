<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wlnto5bxi"/><path class="j4_e-3w9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shortcut-to-url" /></template>
<style>
.j4_e-3w9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.848 38.896c-7.728-4.517-1.827-9.443 7.115-15.185l6.778 6.433V11.538H18.135l5.93 5.93c-15.688 14.79-10.352 18.36-1.217 21.428");
}

.wlnto5bxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29l-4 4v29l4 4h29l4-4v-29z");
}

</style>
