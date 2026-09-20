<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sk3-upbdr"/><path class="exchjjbzd"/><path class="ok6fpacim"/><path class="s994z3b0d"/><path class="ubojtpbkq"/><path class="vhf3_kexp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pin-duotone-thin" /></template>
<style>
.exchjjbzd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 5v8l3 3 3 -3V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ok6fpacim {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s994z3b0d {
  d: path("M6 5h12");
}

.sk3-upbdr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ubojtpbkq {
  d: path("M9 5v8l3 3 3 -3V5");
}

.vhf3_kexp {
  d: path("M12 16v5");
}

</style>
