<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jhfmphbrh"/><path class="i-vmawbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tablet-broken" /></template>
<style>
.i-vmawbvn {
  d: path("M15 17H9");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhfmphbrh {
  d: path("M12 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.11466 19.7715 5.52043 19.9554 8 19.9913M16 4.00869C18.4796 4.04456 19.8853 4.22849 20.8284 5.17157C22 6.34315 22 8.22876 22 12V12C22 15.7712 22 17.6569 20.8284 18.8284C19.6569 20 17.7712 20 14 20H12");
}

</style>
