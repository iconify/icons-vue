<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="scqdy3iir"/><path clip-rule="evenodd" class="qem6z52uk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:signpost-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qem6z52uk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.021 3H18.543C18.91 3 19.271 3.101 19.584 3.293L22.042 4.793C22.68 5.182 23 5.847 23 6.5C23 7.153 22.68 7.818 22.042 8.207L19.585 9.707C19.271 9.899 18.91 10 18.543 10H7.5C6.119 10 5 8.881 5 7.5V5.5C5 4.119 6.119 3 7.5 3H13.021ZM10.979 19H5.457C5.09 19 4.729 18.899 4.416 18.707L1.958 17.207C1.32 16.818 1 16.153 1 15.5C1 14.847 1.32 14.182 1.958 13.793L4.415 12.293C4.729 12.101 5.09 12 5.457 12H16.5C17.881 12 19 13.119 19 14.5V16.5C19 17.881 17.881 19 16.5 19H10.979Z");
  stroke: none;
}

.scqdy3iir {
  stroke-opacity: 0.4;
  d: path("M12 2V4M12 9V13M12 18V22M8 22H16");
}

</style>
