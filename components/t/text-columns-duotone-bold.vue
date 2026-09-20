<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s5i_7quve"/><path class="c3qjvtbje"/><path class="b6e35tlvq"/><path class="f114hzb2m"/><path class="p4xo-obtz"/><path class="sjde2nyhb"/><path class="vd0jm7r_j"/><path class="r7xk8o29f"/><path class="gsl5knvuq"/><path class="p0o5ir5ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-columns-duotone-bold" /></template>
<style>
.b6e35tlvq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c3qjvtbje {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f114hzb2m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gsl5knvuq {
  d: path("M15 8h6");
}

.p0o5ir5ue {
  d: path("M15 16h6");
}

.p4xo-obtz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s5i_7quve {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sjde2nyhb {
  d: path("M3 8h6");
}

.vd0jm7r_j {
  d: path("M3 16h6");
}

</style>
