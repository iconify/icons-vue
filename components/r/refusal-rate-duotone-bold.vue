<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="b4zbcibzd"/><path class="y9eqb3b4r"/><path class="bzb9gabjj"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="u8oheccad"/><path class="mq159kbup"/><path class="m-y6zjb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:refusal-rate-duotone-bold" /></template>
<style>
.b4zbcibzd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bzb9gabjj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m-y6zjb5q {
  d: path("M16 15v3");
}

.mq159kbup {
  d: path("M12 15v3");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u8oheccad {
  d: path("M8 15v3");
}

.y9eqb3b4r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
