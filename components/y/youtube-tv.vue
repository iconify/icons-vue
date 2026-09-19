<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="x9rx5gtxs"/><rect class="l-l1v-beh"/></g><path class="l4sgg6xgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:youtube-tv" /></template>
<style>
.l-l1v-beh {
  width: 39px;
  height: 26px;
  x: 4.5px;
  y: 9px;
  rx: 2px;
  ry: 2px;
}

.l4sgg6xgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.86 22l-9.72-5.596v11.192z");
}

.x9rx5gtxs {
  d: path("M12 39h24");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
