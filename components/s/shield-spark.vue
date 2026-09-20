<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x899d3b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shield-spark" /></template>
<style>
.x899d3b0m {
  fill: currentColor;
  d: path("M12 22q-3.475-.875-5.738-3.988T4 11.1V5l8-3l8 3v6.1q0 3.8-2.263 6.913T12 22Zm0-5q0-2.1 1.45-3.55T17 12q-2.1 0-3.55-1.45T12 7q0 2.1-1.45 3.55T7 12q2.1 0 3.55 1.45T12 17Z");
}

</style>
