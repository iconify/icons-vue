<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x404bcrec"/><path class="zp2a9sb8n"/><path class="uw099db1h"/><path class="yxxkvsbzs"/><path class="ymi7xlb0o"/><path class="sjde2nyhb"/><path class="vd0jm7r_j"/><path class="r7xk8o29f"/><path class="gsl5knvuq"/><path class="p0o5ir5ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-columns-duotone-regular" /></template>
<style>
.gsl5knvuq {
  d: path("M15 8h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p0o5ir5ue {
  d: path("M15 16h6");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.sjde2nyhb {
  d: path("M3 8h6");
}

.uw099db1h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vd0jm7r_j {
  d: path("M3 16h6");
}

.x404bcrec {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymi7xlb0o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yxxkvsbzs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zp2a9sb8n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
