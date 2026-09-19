<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ub_a_5b9o"/><g class="y9tr6bcfx"><path class="w2is1w0pj"/><path class="bdu1f-vgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:we-grow" /></template>
<style>
.bdu1f-vgz {
  d: path("M18.077 25.322c-1.407-2.656-3.504-3.872-5.742-5.774m22.38-12.061C25.625 13.246 18.76 19.54 19.81 33.18");
}

.ub_a_5b9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m32.926 26.091l-.153.001");
}

.w2is1w0pj {
  d: path("M42.273 31.592c-1.916.028-2.449.588-3.135 1.274l-11.445 2.9c-1.17-2.433-1.867-2.61-4.046-2.561l-.987.023c-1.493-3.23-.42-7.477 2.164-8.306c3.128-1.004 8.014-1.792 12.744-5.294c2.542-1.882 4.077-4.339 4.716-6.999M5.726 29.149c4.307-.62 6.136-.02 7.468 2.141c.67 1.088 1.31 2.058 4.051 2.058l.602.005c.237-1.842.531-4.375-1.425-4.803c-3.997-.874-11.343-3.074-9.123-13.58c2.571.268 6.395 1.234 9.291 2.899c-.11-5.255 2.895-9.699 8.358-12.154M42.287 35.93c-3.986 2.837-9.279 5.19-13.19 6.37");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
