<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k3jus_bsc"/><path class="k_7t36omx"/><path class="jt9wyzbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ransomware-sharp" /></template>
<style>
.jt9wyzbdh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.25h.01");
}

.k_7t36omx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12.5h7V18h-7zm1.5 0V6.75h4v3");
}

.k3jus_bsc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.75H14L19.25 8v13.25H4.75V2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
