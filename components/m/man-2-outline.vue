<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lishsz4_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:man-2-outline" /></template>
<style>
.lishsz4_i {
  fill: currentColor;
  d: path("M10.673 21.5v-6.577H8.462V9.039q0-.667.474-1.141t1.141-.475h3.846q.667 0 1.141.475t.475 1.14v5.885h-2.212V21.5zM12 5.808q-.698 0-1.195-.497t-.497-1.195t.497-1.196T12 2.423t1.195.497t.497 1.196q0 .698-.497 1.195T12 5.808");
}

</style>
