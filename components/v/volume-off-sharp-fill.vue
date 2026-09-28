<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qxmjeubgj"/><path class="n6hne6zhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n6hne6zhd {
  d: path("M15.0772 6.2227L15.8044 6.9091C17.2058 8.2316 18 10.0732 18 12C18 12.112 17.9973 12.2238 17.992 12.3351L17.9444 13.334M18.2608 3.7273L18.5498 4C20.7519 6.0782 22 8.9721 22 12C22 13.2746 21.7788 14.5254 21.3585 15.7016L21.022 16.6433M1.7071 1.7071L22.2929 22.2929");
}

.qxmjeubgj {
  fill: currentColor;
  d: path("M12 12L12 20C12 20.8909 10.9229 21.3371 10.2929 20.7071L5.5858 16L2 16C1.4477 16 1 15.5523 1 15L1 9C1 8.4477 1.4477 8 2 8L5.5858 8L6.7929 6.7929L12 12Z");
  stroke: none;
}

</style>
