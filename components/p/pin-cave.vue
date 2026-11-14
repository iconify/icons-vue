<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cofz-vbcp"/><path class="k5emc87ol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-cave" /></template>
<style>
.cofz-vbcp {
  d: path("M13.313 16.5H2.5L5 9l3.5-4l3 1.5l2.5-3L17.5 8l.921 3.912");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5emc87ol {
  d: path("M7.5 16.5V13q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277q.057-.136.126-.266q.07-.13.152-.253q.081-.122.175-.236t.198-.218q.104-.105.218-.198t.236-.175t.253-.152t.266-.126t.277-.099t.286-.071t.291-.044Q10.353 10 10.5 10t.294.014q.147.015.291.044q.145.028.286.071t.277.099t.266.126t.253.152q.122.081.236.175t.218.198q.105.104.198.218t.175.236t.152.253t.126.266t.099.277t.071.286t.044.291q.014.147.014.294v3.116M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
