<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="t6widbc4w"/><path class="vtvade9oe"/></g><g class="y9tr6bcfx"><path class="ho7b1vb_c"/><path class="ibie-9bnp"/><path class="w0pn9f1nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notion-calendar-13" /></template>
<style>
.ho7b1vb_c {
  d: path("m39.153 41.418l-24.717 1.08a2.97 2.97 0 0 1-3.097-2.966v-25.21a2.97 2.97 0 0 1 2.838-2.966l25.956-1.133a1.78 1.78 0 0 1 1.859 1.779v26.451a2.97 2.97 0 0 1-2.839 2.965");
}

.ibie-9bnp {
  d: path("M11.339 22.117v-2.97c0-.954.75-1.738 1.703-1.78l27.091-1.182a1.78 1.78 0 0 1 1.859 1.779v3.803");
}

.t6widbc4w {
  d: path("m18.775 24.889l3.2-1.928m0 0v12.8m4.902-1.337c.883.694 1.837.984 3.98.871l.5-.026c1.766-.092 3.198-1.6 3.198-3.367h0a3.005 3.005 0 0 0-3.199-3.031");
}

.vtvade9oe {
  d: path("M26.875 23.773c.886-.784 1.84-1.171 3.983-1.278l.498-.023a3.005 3.005 0 0 1 3.2 3.032h0c0 1.767-1.433 3.274-3.2 3.367M28.897 29l2.459-.129m-6.181 6.722l-6.4.335");
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
