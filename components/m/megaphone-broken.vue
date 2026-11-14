<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d0qehwbph"/><path class="sdgciib0w"/><path class="is8f0uwob"/><path class="nq5ru3tgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:megaphone-broken" /></template>
<style>
.d0qehwbph {
  d: path("M11.0772 6.65141C12.122 5.69461 13.0431 4.59221 13.8407 3.36301C14.4234 2.39321 15.9027 2.53961 16.2172 3.80101L18.9268 14.6683C19.2412 15.9297 18.0038 16.7536 17.034 16.1709C13.4458 14.1798 9.4686 13.5224 5.2963 14.5627C3.7438 14.9498 2.9681 14.3187 2.6294 12.9603C2.2907 11.6019 2.6794 10.6805 4.2319 10.2934C5.7249 9.92111 7.0937 9.36871 8.3385 8.65491");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is8f0uwob {
  d: path("M7.56689 14.1597C7.86619 17.0137 7.57359 19.5602 8.49449 20.7734C9.24569 21.7198 11.0893 21.2601 11.454 19.8294C11.7459 18.5199 11.1652 16.1912 10.866 14.1644");
}

.nq5ru3tgl {
  d: path("M19.5908 5.3999C21.4908 6.7999 22.0908 10.0999 20.7908 12.0999");
}

.sdgciib0w {
  d: path("M6.42627 9.58301L7.56727 14.1596");
}

</style>
