<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q2b99zbug"/><path class="uieyxabrz"/><ellipse class="dopk_vbap"/><path class="znk_dv1iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:studentid" /></template>
<style>
.dopk_vbap {
  cx: 24px;
  cy: 36.842px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.173px;
  ry: 6.659px;
}

.q2b99zbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 20.956l-15.885-8.18L24 4.5l15.885 8.276z");
}

.uieyxabrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.246 17.437c-.095.57-.19 1.046-.19 1.617c0 3.9 3.14 6.944 6.944 6.944s6.944-3.14 6.944-6.944c0-.571-.095-1.047-.19-1.617");
}

.znk_dv1iz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.115 12.776v9.131");
}

</style>
