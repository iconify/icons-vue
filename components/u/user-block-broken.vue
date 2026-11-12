<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><path class="nuv1qz_2q"/><path class="pk7jetbvs"/><circle class="xjh3njbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-block-broken" /></template>
<style>
.dtl23o_xq {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nuv1qz_2q {
  d: path("M15.5 13.5351C14.4704 13.1948 13.275 13 12 13C8.13401 13 5 14.7909 5 17C5 17.3453 5 17.6804 5.02673 18M13 20.9867C12.6836 20.9955 12.3506 21 12 21C10.2776 21 8.97906 20.8916 8 20.6952");
}

.pk7jetbvs {
  d: path("M19.9492 17.0498L16.0492 20.9497");
}

.xjh3njbok {
  cx: 18px;
  cy: 19px;
  r: 3px;
}

</style>
