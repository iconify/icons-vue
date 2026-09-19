<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="o3xs745zd"/><path class="drkuebb8u"/></g><path class="tdw_o5e8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-pharmacy" /></template>
<style>
.drkuebb8u {
  d: path("M24 14.6v6.974h-.176h0c-1.43 0-2.58 1.082-2.58 2.425s1.15 2.425 2.58 2.425l.176.001V33.4");
}

.o3xs745zd {
  d: path("M13.79 14.6h20.42a9.274 9.274 0 0 1 9.29 9.3v.2a9.274 9.274 0 0 1-9.29 9.3H13.79a9.274 9.274 0 0 1-9.29-9.3v-.2a9.274 9.274 0 0 1 9.29-9.299");
}

.tdw_o5e8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.866 27.85c-1.757 1.134-4.25 1.78-6.866 1.78s-5.11-.646-6.867-1.78m9.74-7.995c.443-.78 1.325-1.27 2.288-1.27s1.846.49 2.289 1.272m-14.9-.002c.443-.78 1.325-1.27 2.288-1.27s1.846.49 2.289 1.272");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
