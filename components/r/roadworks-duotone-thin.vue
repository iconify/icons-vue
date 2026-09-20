<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bcockwbin"/><path class="lrvpbmynw"/><path class="r8vbx7bdh"/><path class="z475fobui"/><path class="cvoxr1bie"/><path class="swh_ykb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:roadworks-duotone-thin" /></template>
<style>
.bcockwbin {
  fill: currentColor;
  d: path("M5 9a7 7 0 1 0 14 0A7 7 0 1 0 5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cvoxr1bie {
  d: path("M12 4.5V9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrvpbmynw {
  fill: currentColor;
  d: path("M9.5 9v3.5h5V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r8vbx7bdh {
  d: path("M5 9a7 7 0 1 0 14 0A7 7 0 1 0 5 9");
}

.swh_ykb_p {
  d: path("M9.5 9v3.5h5V9Z");
}

.z475fobui {
  d: path("M12 16v6");
}

</style>
