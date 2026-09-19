<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahbn08bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-arrow-circle-left" /></template>
<style>
.ahbn08bls {
  fill: currentColor;
  d: path("M2 12c0 5.52 4.48 10 10 10s10-4.48 10-10S17.52 2 12 2S2 6.48 2 12m10-2.79V11h3c.55 0 1 .45 1 1s-.45 1-1 1h-3v1.79c0 .45-.54.67-.85.35l-2.79-2.79c-.2-.2-.2-.51 0-.71l2.79-2.79a.5.5 0 0 1 .85.36");
}

</style>
