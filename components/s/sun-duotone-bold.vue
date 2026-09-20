<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z8owzccti"/><path class="g01zyvbwi"/><path class="v5srdkbdr"/><path class="ysaawnbjv"/><path class="wriot4b8j"/><path class="cf8eb9bym"/><path class="j3rg9kqcf"/><path class="lk3noub5u"/><path class="azsxw4yri"/><path class="kg1t7rbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sun-duotone-bold" /></template>
<style>
.azsxw4yri {
  d: path("m5 19 2.5 -2.5");
}

.cf8eb9bym {
  d: path("M18.5 12H22");
}

.g01zyvbwi {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.j3rg9kqcf {
  d: path("m5 5 2.5 2.5");
}

.kg1t7rbnq {
  d: path("m19 19 -2.5 -2.5");
}

.lk3noub5u {
  d: path("m19 5 -2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v5srdkbdr {
  d: path("M12 2v3.5");
}

.wriot4b8j {
  d: path("M2 12h3.5");
}

.ysaawnbjv {
  d: path("M12 18.5V22");
}

.z8owzccti {
  fill: currentColor;
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
