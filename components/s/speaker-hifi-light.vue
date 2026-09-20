<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pcb_b0bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-hifi-light" /></template>
<style>
.pcb_b0bwp {
  fill: currentColor;
  d: path("M192 26H64a14 14 0 0 0-14 14v176a14 14 0 0 0 14 14h128a14 14 0 0 0 14-14V40a14 14 0 0 0-14-14m2 190a2 2 0 0 1-2 2H64a2 2 0 0 1-2-2V40a2 2 0 0 1 2-2h128a2 2 0 0 1 2 2ZM118 76a10 10 0 1 1 10 10a10 10 0 0 1-10-10m10 38a38 38 0 1 0 38 38a38 38 0 0 0-38-38m0 64a26 26 0 1 1 26-26a26 26 0 0 1-26 26");
}

</style>
