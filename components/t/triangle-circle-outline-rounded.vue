<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj1-h3b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:triangle-circle-outline-rounded" /></template>
<style>
.jj1-h3b3s {
  fill: currentColor;
  d: path("M8.525 14.866h6.93q.46 0 .703-.407t0-.811l-3.462-5.761q-.242-.385-.696-.385t-.696.385l-3.481 5.742q-.242.404 0 .82q.243.417.702.417m.346-1L12 8.689l3.104 5.177zm-.377 6.433q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701M12 20q3.325 0 5.663-2.328T20 12q0-3.325-2.337-5.663T12 4Q8.656 4 6.328 6.338T4 12q0 3.344 2.328 5.672T12 20m0-8");
}

</style>
