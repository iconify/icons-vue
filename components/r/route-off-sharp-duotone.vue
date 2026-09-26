<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t2738o-ud"/><path class="iyd5ldb9t"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.iyd5ldb9t {
  stroke-opacity: 0.4;
  d: path("M18 13.3431L18 3M14.7071 6.2929L18 3L21.2929 6.2929");
}

.t2738o-ud {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.873 17L18 17L18 19L9.873 19C9.3694 20.9503 7.4942 22.2219 5.496 21.9681C3.4978 21.7143 2 20.0143 2 18C2 15.9857 3.4978 14.2857 5.496 14.0319C7.4942 13.7781 9.3694 15.0497 9.873 17Z");
  stroke: none;
}

</style>
