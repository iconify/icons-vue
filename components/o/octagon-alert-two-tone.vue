<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sz2gx2bvd"/><path class="rs99zlbon"/><path class="e0u3qtbzv"/><path class="zs843lqwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-alert-two-tone" /></template>
<style>
.e0u3qtbzv {
  d: path("M12 8V12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rs99zlbon {
  d: path("M3 9.43553V14.5645C3 15.2275 3.26339 15.8634 3.73223 16.3322L7.66777 20.2678C8.13661 20.7366 8.77249 21 9.43553 21H14.5645C15.2275 21 15.8634 20.7366 16.3322 20.2678L20.2678 16.3322C20.7366 15.8634 21 15.2275 21 14.5645V9.43553C21 8.77249 20.7366 8.13661 20.2678 7.66777L16.3322 3.73223C15.8634 3.26339 15.2275 3 14.5645 3H9.43553C8.77249 3 8.13661 3.26339 7.66777 3.73223L3.73223 7.66777C3.26339 8.13661 3 8.77249 3 9.43553Z");
}

.sz2gx2bvd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.5645 2C15.4927 2 16.3827 2.36902 17.0391 3.02539L20.9746 6.96094C21.631 7.61731 22 8.50729 22 9.43555V14.5645C22 15.4927 21.631 16.3827 20.9746 17.0391L17.0391 20.9746C16.3827 21.631 15.4927 22 14.5645 22H9.43555C8.50729 22 7.61731 21.631 6.96094 20.9746L3.02539 17.0391C2.36902 16.3827 2 15.4927 2 14.5645V9.43555C2 8.50729 2.36902 7.61731 3.02539 6.96094L6.96094 3.02539C7.61731 2.36902 8.50729 2 9.43555 2H14.5645Z");
  stroke: none;
}

.zs843lqwx {
  fill: currentColor;
  d: path("M13 16C13 16.5523 12.5523 17 12 17C11.4477 17 11 16.5523 11 16C11 15.4477 11.4477 15 12 15C12.5523 15 13 15.4477 13 16Z");
  stroke: none;
}

</style>
