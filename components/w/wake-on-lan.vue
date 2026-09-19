<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="eucol4b-l"/><path class="s8ud4iiwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wake-on-lan" /></template>
<style>
.eucol4b-l {
  d: path("M28.662 11.167a16.503 16.503 0 1 1-9.016-.088");
}

.s8ud4iiwq {
  d: path("M24.004 4.5h.096v25.18h-.096z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
