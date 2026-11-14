<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xviek2b0y"/><path class="oh5f30b0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-plan-kitchen" /></template>
<style>
.oh5f30b0i {
  d: path("M15.25 17.25V16a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1v1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xviek2b0y {
  d: path("M11.453 17.345q-.464.155-.953.155h-5q-.147 0-.294-.014t-.291-.044q-.145-.028-.286-.071t-.277-.099q-.136-.057-.266-.126q-.13-.07-.253-.152q-.122-.081-.236-.175t-.218-.198t-.198-.218t-.175-.236q-.082-.123-.152-.253t-.126-.266t-.099-.277t-.071-.286t-.044-.291Q2.5 14.647 2.5 14.5V8h11v5.1m0-3.6h8M6 5.5V4m4 1.5V4m4.25 17.5V18a1 1 0 0 1 2 0v1h3.5v-1a1 1 0 0 1 2 0v3.5Z");
}

</style>
