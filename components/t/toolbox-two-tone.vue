<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w72bo_4bl"/><path class="cim34cb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toolbox-two-tone" /></template>
<style>
.cim34cb-n {
  d: path("M4.4142 8.5858C4.7893 8.2107 5.298 8 5.8284 8L18.1716 8C18.702 8 19.2107 8.2107 19.5858 8.5858L21.4142 10.4142C21.7893 10.7893 22 11.298 22 11.8284L22 18C22 19.6569 20.6569 21 19 21L5 21C3.3431 21 2 19.6569 2 18L2 11.8284C2 11.298 2.2107 10.7893 2.5858 10.4142L4.4142 8.5858ZM2 14H22M8 12V16M16 12V16M8 8V5C8 3.8954 8.8954 3 10 3H14C15.1046 3 16 3.8954 16 5V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w72bo_4bl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.7071 7.8787C4.2697 7.3161 5.0328 7 5.8284 7L18.1716 7C18.9672 7 19.7303 7.3161 20.2929 7.8787L22.1213 9.7071C22.6839 10.2697 23 11.0328 23 11.8284L23 18C23 20.2091 21.2091 22 19 22L5 22C2.7909 22 1 20.2091 1 18L1 11.8284C1 11.0328 1.3161 10.2697 1.8787 9.7071L3.7071 7.8787Z");
  stroke: none;
}

</style>
