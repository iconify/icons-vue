<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ksghrjbho"/><path class="g6rhjkb-x"/><path class="txb9q-7nl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:remote-atv" /></template>
<style>
.g6rhjkb-x {
  d: path("M26.647 29.183a2.646 2.646 0 1 1-5.293 0a2.646 2.646 0 0 1 5.293 0m.139 6.455v2.542m-5.572-2.542v2.542M16.04 24.83H9.215c-.87 0-1.57-.7-1.57-1.57V7.07c0-.87.7-1.57 1.57-1.57h29.572c.87 0 1.57.7 1.57 1.57v16.19c0 .87-.7 1.57-1.57 1.57H31.96");
}

.ksghrjbho {
  d: path("M19.864 23.47h8.272c.87 0 1.569.7 1.569 1.569V40.93c0 .87-.7 1.57-1.57 1.57h-8.27c-.87 0-1.57-.7-1.57-1.57V25.039c0-.87.7-1.57 1.57-1.57");
}

.txb9q-7nl {
  d: path("M15.212 17.244c1.977-2.32 5.268-3.71 8.788-3.71s6.81 1.39 8.788 3.71M18.9 20.782c1.273-1.222 3.137-1.926 5.1-1.926s3.827.704 5.1 1.926");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
