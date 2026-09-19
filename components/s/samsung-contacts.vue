<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="py6m_nbpq"/><circle class="ljti_cb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-contacts" /></template>
<style>
.ljti_cb7g {
  cx: 24px;
  cy: 12.702px;
  r: 7.202px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.py6m_nbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5c6.08 0 11.512-2.764 15.115-7.102c-1.338-7.136-7.59-12.54-15.115-12.54s-13.777 5.404-15.115 12.54C12.488 39.736 17.92 42.5 24 42.5");
}

</style>
