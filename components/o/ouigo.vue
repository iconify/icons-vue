<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h8flz-y4i"/><circle class="oaxkj7bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ouigo" /></template>
<style>
.h8flz-y4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 1 24 2.5A21.51 21.51 0 0 1 45.5 24m-21.68 3.85V21.2m-2.74 4v-3.95m-5.29 3.94v-3.94m5.29 3.94a2.65 2.65 0 1 1-5.29 0M32 22a3.3 3.3 0 0 0-3.65-.34a3.24 3.24 0 0 0 .52 6a3.35 3.35 0 0 0 3.61-.88v-2.15h-2.09m11-.09a3.24 3.24 0 1 1-3.29-3.24a3.24 3.24 0 0 1 3.24 3.24Zm-28.08 0A3.23 3.23 0 0 1 10 27.77h0a3.24 3.24 0 1 1 3.23-3.23ZM45.5 24A21.5 21.5 0 1 1 24 2.5A21.51 21.51 0 0 1 45.5 24");
}

.oaxkj7bhu {
  cx: 23.82px;
  cy: 18.44px;
  r: 0.75px;
  fill: currentColor;
}

</style>
