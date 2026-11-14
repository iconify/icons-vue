<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xaynzxzjt"/><path class="dhisxz2yo"/><path class="im-zsp8zw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paragraph-line-duotone" /></template>
<style>
.dhisxz2yo {
  d: path("M19.5 2H10C6.9624 2 4.5 4.4624 4.5 7.5C4.5 10.5376 6.9624 13 10 13H12.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.im-zsp8zw {
  d: path("M12.5 2V22");
}

.xaynzxzjt {
  d: path("M17 2V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
