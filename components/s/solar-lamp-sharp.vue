<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="he3o7ybsl"/><path class="zrnuaslnh"/><path class="d_yq-uzsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:solar-lamp-sharp" /></template>
<style>
.d_yq-uzsg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.25v8m-3.5 0h7");
}

.he3o7ybsl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h10v2.5H7zm2 5h7l-.18.98l-.64 3.54l-.18.98H9l-.18-.98l-.64-3.54L8 7.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zrnuaslnh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.5h.01");
}

</style>
