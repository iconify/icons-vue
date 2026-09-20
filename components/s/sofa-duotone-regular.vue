<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sjxlp6rwh"/><path class="ni3lnewqa"/><path class="t5bd-xmqz"/><path class="atnxg8jtp"/><path class="es050-y4w"/><path class="v6idbfb-b"/><path class="oqj-o0b2r"/><path class="owfn5sxxm"/><path class="x7yzkkbqs"/><path class="xroalcbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sofa-duotone-regular" /></template>
<style>
.atnxg8jtp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19v-5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.es050-y4w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M22 19v-5h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ni3lnewqa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqj-o0b2r {
  d: path("M5 14h14");
}

.owfn5sxxm {
  d: path("M12 8v6");
}

.sjxlp6rwh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 19V8h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t5bd-xmqz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v6idbfb-b {
  d: path("M5 19V8h14v11");
}

.x7yzkkbqs {
  d: path("M2 19v-5h3");
}

.xroalcbzh {
  d: path("M22 19v-5h-3");
}

</style>
