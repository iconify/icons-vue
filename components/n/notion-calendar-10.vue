<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8k42-4sr"/><g class="y9tr6bcfx"><path class="ho7b1vb_c"/><path class="ibie-9bnp"/><path class="w0pn9f1nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notion-calendar-10" /></template>
<style>
.ho7b1vb_c {
  d: path("m39.153 41.418l-24.717 1.08a2.97 2.97 0 0 1-3.097-2.966v-25.21a2.97 2.97 0 0 1 2.838-2.966l25.956-1.133a1.78 1.78 0 0 1 1.859 1.779v26.451a2.97 2.97 0 0 1-2.839 2.965");
}

.ibie-9bnp {
  d: path("M11.339 22.117v-2.97c0-.954.75-1.738 1.703-1.78l27.091-1.182a1.78 1.78 0 0 1 1.859 1.779v3.803");
}

.j8k42-4sr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.866 31.216c0 2.37 1.896 4.167 4.267 4.043s4.109-2.112 4.109-4.482V26.51c0-2.37-1.897-4.167-4.11-4.051s-4.266 2.12-4.266 4.49zm-8.777-6.313l3.2-1.928m0 0v12.8m3.2-.168l-6.4.336");
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
