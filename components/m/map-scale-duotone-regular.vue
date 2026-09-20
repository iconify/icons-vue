<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="digwvcbca"/><path class="l9q4-o2vn"/><path class="qyu-vobur"/><path class="za--46bps"/><path class="o_dpikbpd"/><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:map-scale-duotone-regular" /></template>
<style>
.d8abqfbpc {
  d: path("M3 11h18");
}

.digwvcbca {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gjmq94baq {
  d: path("M15 11v4");
}

.h_c4fk0bb {
  d: path("M3 11v6");
}

.l3hfq7bhw {
  d: path("M9 11v4");
}

.l9q4-o2vn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lfyekl_xx {
  d: path("M21 11v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_dpikbpd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qyu-vobur {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.za--46bps {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
