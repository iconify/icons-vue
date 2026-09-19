<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mj3yjac0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zeal" /></template>
<style>
.mj3yjac0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h37V13c0 4.415-3.585 8-8 8h-29zm37 37h-37V35c0-4.415 3.585-8 8-8h29z");
}

</style>
