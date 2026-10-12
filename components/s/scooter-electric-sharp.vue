<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="adm1albkh"/><path class="nvgqe6zou"/><circle class="iaji0abaq"/><circle class="nbxv73-5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scooter-electric-sharp" /></template>
<style>
.adm1albkh {
  d: path("m2.95 14.77l.6-3.79l.2-1.23h6.75l.38 1.19l1.24 3.87l.38 1.19H2.75z");
}

.iaji0abaq {
  cx: 6.5px;
  cy: 18.5px;
  r: 2.25px;
}

.nbxv73-5j {
  cx: 18.75px;
  cy: 18.5px;
  r: 2.25px;
}

.nvgqe6zou {
  d: path("M8.25 11.25L6.75 13h2.5l-1.5 1.75M12.5 16h5.75m.03.3L16 5.5m-2 0h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
