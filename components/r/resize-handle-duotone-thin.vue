<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="encdkxb_m"/><path class="g_uiugb1x"/><path class="jx94tacen"/><path class="htx64eiti"/><path class="j0xsopbwy"/><path class="dq5olwsrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:resize-handle-duotone-thin" /></template>
<style>
.dq5olwsrs {
  d: path("m21.5 18.5 -3 3");
}

.encdkxb_m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21.5 5.5 -16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g_uiugb1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21.5 12.5 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htx64eiti {
  d: path("m21.5 5.5 -16 16");
}

.j0xsopbwy {
  d: path("m21.5 12.5 -9 9");
}

.jx94tacen {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21.5 18.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
