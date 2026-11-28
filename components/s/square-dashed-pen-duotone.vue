<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bqfi6bbvy"/><path clip-rule="evenodd" class="iw_szvbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-dashed-pen-duotone" /></template>
<style>
.bqfi6bbvy {
  stroke-opacity: 0.4;
  d: path("M3 6C3 4.343 4.343 3 6 3M10.5 3H12.5M21 11.5V13.5M21 18C21 19.657 19.657 21 18 21M13.5 21H10.5M6 21C4.343 21 3 19.657 3 18M3 13.5V10.5");
}

.iw_szvbxh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.871 14.429L14.996 12.779C15.122 12.728 15.236 12.653 15.332 12.557L21.195 6.694C22.269 5.621 22.269 3.879 21.195 2.806C20.121 1.732 18.379 1.732 17.306 2.806L11.443 8.668C11.347 8.764 11.272 8.878 11.221 9.004L9.572 13.129C9.423 13.5 9.51 13.924 9.793 14.207C10.076 14.49 10.5 14.577 10.871 14.429Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
