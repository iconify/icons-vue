<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyh_9hbqh"/><path class="cvnuxqb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-pin-off" /></template>
<style>
.cvnuxqb1b {
  fill: currentColor;
  d: path("M1.635 2.905a.9.9 0 0 0 0 1.27l18.19 18.19a.898.898 0 0 0 1.27-1.27L11 11L2.905 2.905a.9.9 0 0 0-1.27 0");
}

.yyh_9hbqh {
  fill: currentColor;
  d: path("m9 9l7 7h-3v4l-1 3l-1-3v-4H7a1 1 0 0 1-1-1v-1.586a1 1 0 0 1 .293-.707L9 10zm7-7a1 1 0 0 1 1 1v.382a1 1 0 0 1-.553.894L15 5v5l2.707 2.707a1 1 0 0 1 .293.707V15a1 1 0 0 1-.076.383L12.27 9.73L9 6.46V5l-1.447-.724A1 1 0 0 1 7 3.382V3a1 1 0 0 1 1-1z");
}

</style>
