<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="scdnpegfe"/><path class="sbzfdkqzv"/><path class="b3v1okb2h"/><path class="bo8u7q83r"/><path class="zrdou8b0n"/><path class="j8_8pdbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:margin-duotone-thin" /></template>
<style>
.b3v1okb2h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bo8u7q83r {
  d: path("M21 12a9 9 0 1 1 -9 -9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8_8pdbyc {
  d: path("M12 3v9");
}

.sbzfdkqzv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.scdnpegfe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 12a9 9 0 1 1 -9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
