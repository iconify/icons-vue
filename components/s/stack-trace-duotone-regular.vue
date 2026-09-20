<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q-d5hlpgk"/><path class="wvyvslb8j"/><path class="ztgridc7i"/><path class="hpy_80lju"/><path class="kgzfjfb2m"/><path class="mglly3fuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stack-trace-duotone-regular" /></template>
<style>
.hpy_80lju {
  d: path("M3 3v18h8");
}

.kgzfjfb2m {
  d: path("M9 7v10h6");
}

.mglly3fuq {
  d: path("M15 10v3h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-d5hlpgk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wvyvslb8j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 7v10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ztgridc7i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 10v3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
