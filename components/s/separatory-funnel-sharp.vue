<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpz-3q__h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:separatory-funnel-sharp" /></template>
<style>
.fpz-3q__h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c4.5 0 6.75 2.75 6.75 6S15.5 15 13.25 17.5h-2.5c-2.25-2.5-5.5-5-5.5-8.25s2.25-6 6.75-6Zm-6.2 8.3h12.4M12 17.5v3.75M9.25 19.5h5.5");
}

</style>
