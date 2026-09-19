<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="lhg_aqbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:servo" /></template>
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

.lhg_aqbyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.418 13.564l-5.053-6.958m20.218 6.958l5.057-6.956m-.37 21.378l8.18 2.657m-32.718-2.657l-8.178 2.66M24 45.5v-8.6l-12.268-8.914l4.686-14.423h15.165l4.686 14.423L24 36.9");
}

</style>
