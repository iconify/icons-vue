<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow_4hqb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-escrow-release" /></template>
<style>
.ow_4hqb1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6v8.5m19-8.5v3.3m0-1.8h-3L14 5c-.6-.3-1.4-.25-2 .25L7.75 8c-.75.5-.75 1.5 0 2s1.5.5 2 0l1.75-1.5m-9-1h3l3-1.75m-6 7.75h2l5.25 4.75c.566.435 1.36.492 1.985.003M11.5 8.5l2.654 2.433m2.096 5.817h3.5a1.75 1.75 0 0 1 1.75 1.75V20a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 14.5 20v-1.5a1.75 1.75 0 0 1 1.75-1.75m.25-2.25V13a2 2 0 0 1 4 0v1.5");
}

</style>
