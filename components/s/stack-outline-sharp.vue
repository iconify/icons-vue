<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuryfgbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stack-outline-sharp" /></template>
<style>
.yuryfgbtb {
  fill: currentColor;
  d: path("M6 14v2H2V2h14v4h-2V4H4v10zm2 8V8h14v14zm2-2h10V10H10zm5-5");
}

</style>
