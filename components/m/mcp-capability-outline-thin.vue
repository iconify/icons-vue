<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b4bbhnb2u"/><path class="li19mgbhm"/><path class="t0-mwc0xy"/><path class="neq20cckj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-capability-outline-thin" /></template>
<style>
.b4bbhnb2u {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7l3 -3h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.li19mgbhm {
  d: path("M9 10v6");
}

.neq20cckj {
  d: path("M15 10v6");
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

</style>
