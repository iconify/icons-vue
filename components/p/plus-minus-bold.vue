<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l0jlo_qef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:plus-minus-bold" /></template>
<style>
.l0jlo_qef {
  fill: currentColor;
  d: path("m208.49 64.49l-144 144a12 12 0 0 1-17-17l144-144a12 12 0 0 1 17 17M60 112a12 12 0 0 0 24 0V84h28a12 12 0 0 0 0-24H84V32a12 12 0 0 0-24 0v28H32a12 12 0 0 0 0 24h28Zm164 60h-80a12 12 0 0 0 0 24h80a12 12 0 0 0 0-24");
}

</style>
