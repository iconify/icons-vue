<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGAFLyucac)" class="ynpb6ltox"/><defs><linearGradient id="SVGAFLyucac" x1="12.013" x2="12.013" y1="2.985" y2="20.998" gradientUnits="userSpaceOnUse"><stop class="ut702abgz"/><stop offset=".36" class="znhwt_b9m"/><stop offset=".71" class="wgjwl5pci"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rxd" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ut702abgz {
  stop-color: var(--svg-color--4d8fb2, #4d8fb2);
}

.wgjwl5pci {
  stop-color: var(--svg-color--fff4c4, #fff4c4);
}

.ynpb6ltox {
  d: path("M18.065 18.662a9.008 9.008 0 0 0-3.047-15.136A9.01 9.01 0 0 0 4.977 6.362h-1.97L6.09 9.244a1.82 1.82 0 0 0 1.256.496h5.426c.822 0 1.492.585 1.492 1.407s-.839 1.407-1.66 1.407h-.592l2.81 2.815c1.862 0 3.382-1.689 3.382-4.222v-.079a4.706 4.706 0 0 0-4.7-4.706H5.568a8.556 8.556 0 1 1 12.21 11.945l.28.355zm-12.469-5.77l7.43 7.6a8.56 8.56 0 0 1-9.525-7.63a8.56 8.56 0 0 1 .727-4.417l-.32-.394a9.007 9.007 0 0 0 9.513 12.835l.112.107h5.798L9.368 10.865H6.44c-1.041 0-1.565 1.272-.833 2.02z");
}

.znhwt_b9m {
  stop-color: var(--svg-color--35c6f3, #35c6f3);
}

</style>
