<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qnnrv1m-v"/><circle class="e0onlwxab"/><path class="a_1c4zbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ytalarm" /></template>
<style>
.a_1c4zbag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.112 14.394a5 5 0 0 0-3.533-3.533c-2.314-.894-24.732-1.332-31.236.025A5 5 0 0 0 4.81 14.42c-1.045 4.583-1.124 14.491.026 19.177a5 5 0 0 0 3.533 3.533c4.583 1.055 26.371 1.203 31.236 0a5 5 0 0 0 3.533-3.533c1.114-4.993 1.193-14.287-.026-19.203");
}

.e0onlwxab {
  cx: 24px;
  cy: 31.378px;
  r: 1.622px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qnnrv1m-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.504 27.908H17.496a.483.483 0 0 1-.482-.483v-1.852c0-.226.092-.443.255-.6l2.898-2.791v-4.546c0-.407.33-.738.738-.738h1.191a1.898 1.898 0 1 1 3.797 0h1.192c.407 0 .738.33.738.739v4.545l2.907 2.79a.83.83 0 0 1 .256.602v1.851a.483.483 0 0 1-.482.483");
}

</style>
