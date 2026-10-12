<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8bj16hrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plateau" /></template>
<style>
.e8bj16hrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.16 12.09l1.68-3.68q.41-.91 1.41-.91h11.5q1 0 1.41.91l1.68 3.68q.41.91-.59.91H3.75q-1 0-.59-.91m-.41 6.41c2-1.6 4.17-1.6 6.17 0s4.17 1.6 6.17 0s4.16-1.6 6.16 0");
}

</style>
