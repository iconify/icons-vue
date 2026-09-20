<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vm8gvh4cw"/><path class="v__n0ccyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tc001" /></template>
<style>
.v__n0ccyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.741 20.959v.066a5.36 5.36 0 1 1-10.719 0v-5.46a5.36 5.36 0 1 1 10.719 0v.066M18.37 29.795za2.644 2.644 0 0 1 2.65 2.65v2.7a2.644 2.644 0 0 1-2.65 2.65a2.644 2.644 0 0 1-2.65-2.65v-2.7a2.644 2.644 0 0 1 2.65-2.65m7.28 0za2.644 2.644 0 0 1 2.65 2.65v2.7a2.644 2.644 0 0 1-2.65 2.65a2.644 2.644 0 0 1-2.65-2.65v-2.7a2.644 2.644 0 0 1 2.65-2.65m4.63 1.089l2-1.09v8");
}

.vm8gvh4cw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m2.759 4.705h10.719m-5.36 16.18v-16.18");
}

</style>
