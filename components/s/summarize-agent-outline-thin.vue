<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pxx-spbdi"/><path class="pi0o-3bfc"/><path class="ifhv18rgk"/><path class="t_kadbb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:summarize-agent-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifhv18rgk {
  d: path("M12 12h6");
}

.pi0o-3bfc {
  d: path("M12 7h9");
}

.pxx-spbdi {
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

.t_kadbb9f {
  d: path("M12 17h3");
}

</style>
