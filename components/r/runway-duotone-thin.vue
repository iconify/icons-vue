<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pk2fqc6zn"/><path class="s_umicbfq"/><path class="sigoiybyx"/><path class="iu3a-_cmb"/><path class="t3v_ptnwp"/><path class="oakk4fbrw"/><path class="ifv_d4f9e"/><path class="d1zyr9bfc"/><path class="iyj_k-bwo"/><path class="jnf_2db5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:runway-duotone-thin" /></template>
<style>
.d1zyr9bfc {
  d: path("M12 4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifv_d4f9e {
  d: path("M17 2v20");
}

.iu3a-_cmb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iyj_k-bwo {
  d: path("M12 11v4");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.oakk4fbrw {
  d: path("M7 2v20");
}

.pk2fqc6zn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s_umicbfq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sigoiybyx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t3v_ptnwp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
