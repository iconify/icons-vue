<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="munnnfbtg"/><path class="nsperen5y"/><path class="cvkofmywl"/><path class="qt84w9byp"/><path class="t1kkvgdjg"/><path class="oakk4fbrw"/><path class="ifv_d4f9e"/><path class="d1zyr9bfc"/><path class="iyj_k-bwo"/><path class="jnf_2db5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:runway-duotone-regular" /></template>
<style>
.cvkofmywl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d1zyr9bfc {
  d: path("M12 4v4");
}

.ifv_d4f9e {
  d: path("M17 2v20");
}

.iyj_k-bwo {
  d: path("M12 11v4");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.munnnfbtg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nsperen5y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oakk4fbrw {
  d: path("M7 2v20");
}

.qt84w9byp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t1kkvgdjg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 18v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
