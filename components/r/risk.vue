<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="irrzblbue"/><circle class="k9e2fwbiv"/><path class="w88sl8bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:risk" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.irrzblbue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.73 29.5V19.086h3.41c1.927 0 3.49 1.566 3.49 3.497s-1.563 3.498-3.49 3.498h-3.41m3.41 0l3.409 3.416m12.514-10.411V29.5m.001-2.212l4.714-4.691m-3.214 3.198l3.706 3.689");
}

.k9e2fwbiv {
  cx: 21.288px;
  cy: 19.411px;
  r: 0.75px;
  fill: currentColor;
}

.w88sl8bpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.288 22.601V29.5m2.75-.582c.475.4.988.582 2.14.582h.585c.95 0 1.72-.772 1.72-1.725h0c0-.952-.77-1.725-1.72-1.725h-1.168a1.72 1.72 0 0 1-1.721-1.725h0c0-.952.77-1.725 1.72-1.725h.585c1.152 0 1.666.183 2.14.583");
}

</style>
