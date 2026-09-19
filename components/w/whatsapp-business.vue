<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p50gwyw4f"/><path class="iitj9jbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whatsapp-business" /></template>
<style>
.iitj9jbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.544 24a4.75 4.75 0 1 1 0 9.5h-7.838v-19h7.838a4.75 4.75 0 0 1 0 9.5m0 0h-7.838");
}

.p50gwyw4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c-11.885.013-21.51 9.658-21.497 21.543A21.5 21.5 0 0 0 5.15 34.36L3.5 44.5l10.14-1.65c10.41 5.71 23.48 1.901 29.19-8.51s1.902-23.479-8.509-29.19a21.5 21.5 0 0 0-10.32-2.65Z");
}

</style>
