<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="k0ypx8b8c"/><path class="ef_jh_-8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:neeva" /></template>
<style>
.ef_jh_-8b {
  d: path("M25.22 18.272a7.376 7.376 0 0 1 6.204 7.567M28.662 7.813a19.426 19.426 0 0 1 14.8 18.018m-38.793-.078a19.427 19.427 0 0 0 20.51-18.444m3.384.695s.271 5.93-3.294 10.22");
}

.k0ypx8b8c {
  d: path("m4.5 28.51l.002 12.232h12.08V28.51zm26.918-2.76l.002 14.992H43.5V25.75M4.653 25.7c.542-10.68 9.615-18.914 20.299-18.42");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
