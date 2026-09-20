<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkka-vwvt"/><path class="nzx-eixar"/><path class="yu92orbma"/><path class="icy6dnbvy"/><path class="kv9cthbyn"/><path class="t51i6hb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:synthesise-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icy6dnbvy {
  d: path("M12 8v5");
}

.jkka-vwvt {
  d: path("M3 5h6");
}

.kv9cthbyn {
  d: path("m9 10 3 3 3 -3");
}

.nzx-eixar {
  d: path("M12 5h3");
}

.t51i6hb9i {
  d: path("M6 17.5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.yu92orbma {
  d: path("M18 5h3");
}

</style>
