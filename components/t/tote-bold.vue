<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dh2q-z4fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tote-bold" /></template>
<style>
.dh2q-z4fq {
  fill: currentColor;
  d: path("M239 66.75A20.12 20.12 0 0 0 224 60h-44.17a52 52 0 0 0-103.66 0H32.08a20 20 0 0 0-19.94 22.35l14.25 120A20.06 20.06 0 0 0 46.33 220h163.34a20.06 20.06 0 0 0 19.94-17.65l14.25-120a20 20 0 0 0-4.86-15.6M128 36a28 28 0 0 1 27.71 24h-55.42A28 28 0 0 1 128 36m78.19 160H49.81L36.5 84H76v20a12 12 0 0 0 24 0V84h56v20a12 12 0 0 0 24 0V84h39.5Z");
}

</style>
