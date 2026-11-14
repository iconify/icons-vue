<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ihgubzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:water-network-map" /></template>
<style>
.w1ihgubzl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.927 2.016q.041-.048.089-.089q.056-.047.121-.083q.064-.036.135-.058q.07-.023.143-.031q.074-.009.147-.002q.074.006.145.026t.137.054t.123.08t.106.103Q9.489 4.872 9.911 6.75h4.919q.196-.874.871-1.549q.952-.953 2.299-.953t2.299.953t.951 2.298q.001 1.347-.951 2.3T18 10.752t-2.299-.953q-.675-.675-.871-1.549H9.955q-.076.59-.278 1.053l6.581 5.944q.768-.499 1.742-.499q1.347 0 2.299.953t.951 2.298q.001 1.347-.951 2.3T18 21.252t-2.299-.953q-.952-.952-.951-2.298v-.002q0-.934.458-1.679l-6.492-5.864q-.595.387-1.466.499v3.844q2.5.351 2.5 3.201q0 3.25-3.25 3.25T3.25 18q0-2.85 2.5-3.201v-3.844Q3 10.602 3 7.5q0-2.025 2.927-5.484");
}

</style>
