<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="t9n42ac1e"/><path class="p9760fzsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-check-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9760fzsb {
  d: path("M14.2929 14.2929L21.2929 21.2929");
}

.t9n42ac1e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 10C18 14.4183 14.4183 18 10 18C5.5817 18 2 14.4183 2 10C2 5.5817 5.5817 2 10 2C14.4183 2 18 5.5817 18 10ZM6.8672 10.8185L8.8115 12.8184C8.9998 13.012 9.2584 13.1213 9.5285 13.1213C9.8769 13.1213 10.2001 12.94 10.3818 12.6428L13.2669 7.9216L11.5604 6.8787L9.3472 10.5002L8.3012 9.4243L6.8672 10.8185Z");
  stroke: none;
}

</style>
