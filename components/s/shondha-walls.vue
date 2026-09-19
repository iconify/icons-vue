<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_wgkebhr"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shondha-walls" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j_wgkebhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.216 29.785c3.111 6.224 6.912 6.737 11.634 6.737c4.235 0 7.934-2.142 7.934-6.863c0-7.935-17.378-5.66-17.378-12.878c0-3.188 3.23-5.303 7.497-5.303c2.882 0 6.041.924 9.102 4.965");
}

</style>
