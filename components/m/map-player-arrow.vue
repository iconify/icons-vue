<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etj_605kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-player-arrow" /></template>
<style>
.etj_605kp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.46 4.389q-1.71.569-1.71 2.371v11.311q0 1.28 1.038 2.028t2.252.344l3.183-1.061q.294-.098.592-.013l5.957 1.702q.745.213 1.479-.032l4.289-1.429q1.71-.57 1.71-2.372V5.928q0-1.28-1.038-2.028t-2.252-.344l-3.183 1.061q-.294.098-.592.013L9.228 2.928q-.745-.213-1.479.032zm9.325 4.251q1.412-.548 2.451.554q1.039 1.101.409 2.479l-1.515 3.314q-.446.973-1.507.833t-1.238-1.197l-.201-1.203q-.087-.523-.61-.615l-1.081-.192q-1.009-.18-1.109-1.2t.855-1.394z");
}

</style>
