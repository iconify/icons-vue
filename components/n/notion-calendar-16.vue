<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="cohxzfiow"/><path class="w9yty8svk"/></g><g class="y9tr6bcfx"><path class="ho7b1vb_c"/><path class="ibie-9bnp"/><path class="w0pn9f1nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notion-calendar-16" /></template>
<style>
.cohxzfiow {
  d: path("m18.562 24.884l3.2-1.928m0 0v12.8m8.74-8.991c2.356-.124 4.267 1.687 4.267 4.043s-1.91 4.367-4.267 4.49s-4.267-1.686-4.267-4.043s1.91-4.367 4.267-4.49");
}

.ho7b1vb_c {
  d: path("m39.153 41.418l-24.717 1.08a2.97 2.97 0 0 1-3.097-2.966v-25.21a2.97 2.97 0 0 1 2.838-2.966l25.956-1.133a1.78 1.78 0 0 1 1.859 1.779v26.451a2.97 2.97 0 0 1-2.839 2.965");
}

.ibie-9bnp {
  d: path("M11.339 22.117v-2.97c0-.954.75-1.738 1.703-1.78l27.091-1.182a1.78 1.78 0 0 1 1.859 1.779v3.803");
}

.w0pn9f1nf {
  d: path("M36.661 10.248V7.874a2.374 2.374 0 0 0-2.477-2.372L8.279 6.633a2.374 2.374 0 0 0-2.27 2.372v25.65a2.374 2.374 0 0 0 2.466 2.373l2.864-.112");
}

.w9yty8svk {
  d: path("M34.295 23.88c-.633-.915-1.739-1.49-3.477-1.398l-.316.016c-2.37.124-4.267 2.12-4.267 4.49v4.267m-1.273 4.334l-6.4.335");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
