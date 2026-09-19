<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="gmt798iqt"/><g class="y9tr6bcfx"><path class="jbg898bxo"/><path class="dx986eesp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:truevisions" /></template>
<style>
.dx986eesp {
  d: path("m24.774 24l-1.77 1.022l-1.77 1.021v-4.086l1.77 1.021z");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.gmt798iqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.893 29.236V18.764l6.882 10.472V18.764m21.332 0L35.51 29.236l-2.597-10.472l-2.597 10.472l-2.597-10.472");
}

.jbg898bxo {
  d: path("M27.31 24a4.567 4.567 0 1 1-9.135 0a4.567 4.567 0 0 1 9.134 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
