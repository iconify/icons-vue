<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wolabgbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:upload-2-rounded" /></template>
<style>
.wolabgbrd {
  fill: currentColor;
  d: path("M5.5 20h13q.213 0 .356.144t.144.357t-.144.356T18.5 21h-13q-.213 0-.356-.144T5 20.499t.144-.356T5.5 20m4.942-2.77q-.343 0-.575-.231t-.232-.576v-5.98H7.992q-.502 0-.723-.448q-.221-.447.077-.85l4.008-5.293q.122-.161.294-.242q.173-.081.356-.081t.347.08q.165.082.295.243l3.988 5.292q.299.404.078.851t-.724.447h-1.642v5.981q0 .343-.232.576t-.576.232z");
}

</style>
