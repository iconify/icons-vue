<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goxhdf_-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:woman-2-rounded" /></template>
<style>
.goxhdf_-w {
  fill: currentColor;
  d: path("M10.673 20.692v-5.307H8.571q-.426 0-.67-.351q-.243-.351-.082-.755l2.385-5.998q.23-.556.712-.88t1.08-.324q.596 0 1.083.324q.486.324.717.88l2.385 5.998q.161.404-.082.755q-.244.35-.67.35h-2.102v5.308q0 .344-.232.576t-.576.232h-1.038q-.343 0-.576-.232t-.232-.576M12 5.808q-.698 0-1.195-.497t-.497-1.195t.497-1.196T12 2.423t1.195.497t.497 1.196q0 .698-.497 1.195T12 5.808");
}

</style>
