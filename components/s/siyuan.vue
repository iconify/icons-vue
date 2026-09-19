<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eje_qyb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:siyuan" /></template>
<style>
.eje_qyb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8 38l9-9l7 7l7-7l9 8.95V38V19l-9-9l-7 7l-7-7l-9 9zm9-28v19m7-12v19m7-26v19");
}

</style>
