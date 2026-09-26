<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gxsd7jucs"/><path class="yrcm1ibvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gxsd7jucs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.1716 2.2929L21.7071 5.8284C22.0976 6.219 22.0976 6.8521 21.7071 7.2426L7.2426 21.7071C6.8521 22.0976 6.219 22.0976 5.8284 21.7071L2.2929 18.1716C1.9024 17.781 1.9024 17.1479 2.2929 16.7574L16.7574 2.2929C17.1479 1.9024 17.781 1.9024 18.1716 2.2929Z");
  stroke: none;
}

.yrcm1ibvg {
  d: path("M17.4645 3L21 6.5355L6.5355 21L3 17.4645L17.4645 3ZM13.1251 7.3393L16.6607 10.8749");
}

</style>
