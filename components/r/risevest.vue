<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dz-s92f-q"/><circle class="zcax966yi"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:risevest" /></template>
<style>
.dz-s92f-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 23.259a2.86 2.86 0 0 1 2.862-2.862m-2.862 0v7.584m6.447-7.584v7.584m3.908-.641c.523.44 1.087.64 2.354.64h.642a1.894 1.894 0 0 0 1.892-1.895a1.894 1.894 0 0 0-1.892-1.896h-1.284a1.894 1.894 0 0 1-1.892-1.896c0-1.047.847-1.896 1.892-1.896h.642c1.267 0 1.83.201 2.353.64m9.218 5.5a2.862 2.862 0 0 1-5.348-1.418v-1.86a2.862 2.862 0 0 1 5.723 0v.93h-5.723");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.zcax966yi {
  cx: 37.427px;
  cy: 21.092px;
  r: 1.073px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
