<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l1gtnqygv"/><path class="enuzerbiy"/><path class="lzu41kjgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:member-only-offer" /></template>
<style>
.enuzerbiy {
  fill: currentColor;
  d: path("m8.75 6.25l1.176 2.882l3.104.227l-2.378 2.009l.743 3.023L8.75 12.75l-2.645 1.641l.743-3.023L4.47 9.359l3.104-.227Z");
}

.l1gtnqygv {
  d: path("M12.1 20H2.5V4h19v7.1");
}

.lzu41kjgq {
  d: path("m14.75 21.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
