<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vq_q_tsjp"/><path class="qkxtq1brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:state-connect-traffic-control" /></template>
<style>
.qkxtq1brt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.321 19.255H14.693c2.547-2.106 5.026-5.237 6.532-8.477m-1.945 8.476v-5.091m0 10.642v-1.662m3.888-3.889V5.653m0 19.152v-1.662m5.552-3.889V5.653m0 19.152v-1.662m-3.888-3.889V5.653m0 19.152v-1.662M19.28 5.653c.094 6.362-7.3 13.018-12.019 13.602H5.679m0 5.603h36.642M5.679 28.745h27.628c-2.547 2.106-5.026 5.237-6.532 8.477m1.945-8.476v5.091m-3.888-5.091v13.601M19.28 28.746v13.601m3.888-13.601v13.601m5.552 0c-.094-6.362 7.3-13.018 12.019-13.602h1.582m-28.494-1.944h3.002m10.441 0h3.003m-9.048 7.006v3.002m5.55-6.923v3.003m0-24.209v3.003m-5.55 5.712v1.454m-12.788 2.35h3.003m11.116 0h3.003m8.481 0h3.003");
}

.vq_q_tsjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m32.821 17.642H5.679");
}

</style>
