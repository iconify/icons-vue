<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="j3f1k_yzu"/><rect transform="rotate(10 29.525 24.956)" class="s0ety1spr"/></g><path class="pomfakxrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:twenty" /></template>
<style>
.j3f1k_yzu {
  d: path("M15.164 20.398a3.922 3.922 0 0 1 5.291-2.97c1.564.596 2.609 2.224 2.48 3.892c-.094 1.24-.693 2.376-1.666 2.967c-1.802 1.095-7.479 3.9-7.479 3.9l7.717 1.36m11.748-8.523l-7.469 7.864");
}

.pomfakxrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.052 10.548L12.578 5.527a1.75 1.75 0 0 0-2.03 1.421L5.527 35.422a1.75 1.75 0 0 0 1.421 2.03l28.474 5.021a1.75 1.75 0 0 0 2.03-1.421l5.021-28.474a1.75 1.75 0 0 0-1.421-2.03");
}

.s0ety1spr {
  width: 7.836px;
  height: 11.828px;
  x: 25.607px;
  y: 19.043px;
  rx: 3.918px;
  ry: 3.918px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
