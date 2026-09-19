<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="uf6u5hg-j"/><g class="y9tr6bcfx"><path class="rqthuvx5t"/><path class="cvazfwbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pill-time" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cvazfwbnz {
  d: path("M21.272 22.782a2.79 2.79 0 0 0 3.946 3.946l5.92-5.92l-3.947-3.945z");
}

.rqthuvx5t {
  d: path("m27.191 16.863l3.946 3.946l5.919-5.92a2.79 2.79 0 0 0-3.946-3.945z");
}

.uf6u5hg-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5V12");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
