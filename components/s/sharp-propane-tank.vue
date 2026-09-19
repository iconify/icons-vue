<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm_o21bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-propane-tank" /></template>
<style>
.jm_o21bud {
  fill: currentColor;
  d: path("M4 15v3c0 2.21 1.79 4 4 4h8c2.21 0 4-1.79 4-4v-3zm16-2v-3c0-1.86-1.28-3.41-3-3.86V2H7v4.14c-1.72.45-3 2-3 3.86v3zM9 4h6v2h-2V5h-2v1H9z");
}

</style>
