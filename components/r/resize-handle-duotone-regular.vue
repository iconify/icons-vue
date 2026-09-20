<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v8mciz8zt"/><path class="zx-ql-bjg"/><path class="kuk4j5bxv"/><path class="htx64eiti"/><path class="j0xsopbwy"/><path class="dq5olwsrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:resize-handle-duotone-regular" /></template>
<style>
.dq5olwsrs {
  d: path("m21.5 18.5 -3 3");
}

.htx64eiti {
  d: path("m21.5 5.5 -16 16");
}

.j0xsopbwy {
  d: path("m21.5 12.5 -9 9");
}

.kuk4j5bxv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21.5 18.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v8mciz8zt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21.5 5.5 -16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zx-ql-bjg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21.5 12.5 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
