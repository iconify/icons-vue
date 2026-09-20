<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="ddquyjb-w"/><path class="rg9q3g_gk"/><path class="br8ur4ckw"/><path class="vl7802bms"/><path class="jpq-obbuw"/><path class="pjjym-bdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-20-filled" /></template>
<style>
.br8ur4ckw {
  d: path("M8 14.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0z");
  fill: currentColor;
}

.ddquyjb-w {
  d: path("M6.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.jpq-obbuw {
  d: path("M15 9.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0z");
  fill: currentColor;
}

.pjjym-bdn {
  d: path("M13.5 16a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

.rg9q3g_gk {
  d: path("M6.5 11a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

.vl7802bms {
  d: path("M13.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

</style>
