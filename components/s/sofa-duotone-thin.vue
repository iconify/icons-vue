<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zyaro_brf"/><path class="zrasp8b3z"/><path class="psjx1r07k"/><path class="vsyw0vqqg"/><path class="gvxpcrbdq"/><path class="v6idbfb-b"/><path class="oqj-o0b2r"/><path class="owfn5sxxm"/><path class="x7yzkkbqs"/><path class="xroalcbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sofa-duotone-thin" /></template>
<style>
.gvxpcrbdq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M22 19v-5h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqj-o0b2r {
  d: path("M5 14h14");
}

.owfn5sxxm {
  d: path("M12 8v6");
}

.psjx1r07k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v6idbfb-b {
  d: path("M5 19V8h14v11");
}

.vsyw0vqqg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19v-5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7yzkkbqs {
  d: path("M2 19v-5h3");
}

.xroalcbzh {
  d: path("M22 19v-5h-3");
}

.zrasp8b3z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zyaro_brf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 19V8h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
