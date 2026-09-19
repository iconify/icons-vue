<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sdg5icpfe"/><g class="y9tr6bcfx"><path class="ho7b1vb_c"/><path class="ibie-9bnp"/><path class="w0pn9f1nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notion-calendar-7" /></template>
<style>
.ho7b1vb_c {
  d: path("m39.153 41.418l-24.717 1.08a2.97 2.97 0 0 1-3.097-2.966v-25.21a2.97 2.97 0 0 1 2.838-2.966l25.956-1.133a1.78 1.78 0 0 1 1.859 1.779v26.451a2.97 2.97 0 0 1-2.839 2.965");
}

.ibie-9bnp {
  d: path("M11.339 22.117v-2.97c0-.954.75-1.738 1.703-1.78l27.091-1.182a1.78 1.78 0 0 1 1.859 1.779v3.803");
}

.sdg5icpfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.025 35.778l6.88-13.16l-8.48.444");
}

.w0pn9f1nf {
  d: path("M36.661 10.248V7.874a2.374 2.374 0 0 0-2.477-2.372L8.279 6.633a2.374 2.374 0 0 0-2.27 2.372v25.65a2.374 2.374 0 0 0 2.466 2.373l2.864-.112");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
