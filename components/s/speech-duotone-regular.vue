<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pygpyvjpl"/><path class="h3f5lcksx"/><path class="ewy1wiqaa"/><path class="xc3-x_h_p"/><path class="ghzzdessy"/><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="h7bcztycq"/><path class="cg-q-7bgo"/><path class="om2raabrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-duotone-regular" /></template>
<style>
.cg-q-7bgo {
  d: path("M16 3v18");
}

.el0n_ccnv {
  d: path("M8 5v14");
}

.ewy1wiqaa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ghzzdessy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h3f5lcksx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7bcztycq {
  d: path("M12 8v8");
}

.lbz2yq5no {
  d: path("M4 9v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.om2raabrv {
  d: path("M20 10v4");
}

.pygpyvjpl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xc3-x_h_p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
