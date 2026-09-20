<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxebhzeor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shades-closed" /></template>
<style>
.sxebhzeor {
  fill: currentColor;
  d: path("M3 22V4H2V2h20v2h-1v18h-2.125q-.325-.875-1.1-1.437T16 20q-1.025 0-1.787.563T13.125 22H10.85q-.3-.875-1.075-1.437T8 20q-1.025 0-1.8.563T5.1 22zM13 4h-2v14.125h2z");
}

</style>
