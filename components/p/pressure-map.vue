<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5qzg2igi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pressure-map" /></template>
<style>
.g5qzg2igi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.46 3.89l4.289-1.43q.734-.245 1.479-.032l5.957 1.702q.298.085.592-.013l3.183-1.061q1.214-.404 2.252.344t1.038 2.028v12.311q0 1.802-1.71 2.372l-4.289 1.429q-.734.245-1.479.032L8.815 19.87q-.298-.085-.592.013L5.04 20.944q-1.214.404-2.252-.344T1.75 18.572V6.261q0-1.802 1.71-2.371m3.788 3.091Q5.25 7.695 5.25 10q0 2.774.543 4.312q.855 2.424 2.889 1.916q.81-.203 2.272.32q1.963.702 3.546.702q3.219 0 3.646-3.584q.137-1.143.316-1.679q.678-2.035-.33-3.61Q17.09 6.75 15 6.75q-.967 0-2.35.463q-1.226.41-1.815.116q-1.9-.95-3.587-.348");
}

</style>
