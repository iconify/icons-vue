<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tjb3_i1_o"/><path class="uwdg8ebwy"/><path class="scu5sqbgh"/><path class="m_z6macan"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parrot-sharp" /></template>
<style>
.m_z6macan {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 11.5l.392 3.132l2.608 1.118");
}

.scu5sqbgh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 7.5h.01");
}

.tjb3_i1_o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 3.25H17v8c0 3.75-2 6.5-5 7.75l-1.25 2.25h-2.5l1-3l-2.5-2.143V9a5.75 5.75 0 0 1 5.75-5.75Z");
}

.uwdg8ebwy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.85 6.6c2.6.4 4.4 2.4 4.4 4.9v1.662l-.95 1.188c-.45-1.4-1.6-2.35-3.3-3.1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
