<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8q62k13p"/><path class="n49oq7__n"/><path class="kt4vswbcx"/><path class="u9ungwb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:voice-clone-outline-thin" /></template>
<style>
.g8q62k13p {
  d: path("M5.88 14.12a3 3 0 0 1 0 -4.24");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt4vswbcx {
  d: path("M18.12 9.88a3 3 0 0 1 0 4.24");
}

.n49oq7__n {
  d: path("M3.76 16.24a6 6 0 0 1 0 -8.5");
}

.u9ungwb-f {
  d: path("M20.24 7.76a6 6 0 0 1 0 8.5");
}

</style>
