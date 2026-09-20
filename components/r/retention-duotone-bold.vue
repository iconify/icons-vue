<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="ln_5yacac"/><path class="qnqxdbb_t"/><path class="nkqguac9f"/><path class="g91uwsb-i"/><path class="r3faxubne"/><path class="ler50rfbf"/><path class="siun7_bal"/><path class="cub64ac5a"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retention-duotone-bold" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.cub64ac5a {
  d: path("M19 13v7");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g91uwsb-i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ler50rfbf {
  d: path("M9 8v12");
}

.ln_5yacac {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nkqguac9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnqxdbb_t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.siun7_bal {
  d: path("M14 11v9");
}

</style>
