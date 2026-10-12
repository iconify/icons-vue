<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jwm307bpc"/><path class="k4k1943po"/><path class="yxl_vybyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shirt-sharp" /></template>
<style>
.jwm307bpc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.25h6l.89.45l2.72 1.35l.89.45l.16.99l.93 5.52l.16.99l-.87.25l-.88.25l-.45-.89l-.85-1.72l-.45-.89v10.75H6.25V10l-.45.89l-.85 1.72l-.45.89l-.87-.25l-.88-.25l.16-.99l.93-5.52L4 5.5l.89-.45L7.61 3.7l.89-.45z");
}

.k4k1943po {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.83 3.63l2.84 3.24l.33.38l-.35.35l-1.55 1.55l-.35.35l-.24-.44l-2.02-3.62L7.25 5l.29-.41l.67-.93l.29-.41zm6.34 0l-2.84 3.24l-.33.38l.35.35l1.55 1.55l.35.35l.24-.44l2.02-3.62l.24-.44l-.29-.41l-.67-.93l-.29-.41z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yxl_vybyn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.5h.01M12 16.25h.01");
}

</style>
