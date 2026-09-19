<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeogbabsk"/><path class="ea0at_btv"/><path class="r0hr0xiwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-type-specimen" /></template>
<style>
.ea0at_btv {
  fill: currentColor;
  d: path("M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-3.54 12.01l-.63-1.82H12.2l-.65 1.82a.725.725 0 1 1-1.36-.5l2.73-7.27c.16-.44.6-.74 1.08-.74s.92.3 1.09.75l2.73 7.27c.18.47-.17.98-.68.98c-.31 0-.58-.19-.68-.49");
}

.r0hr0xiwf {
  fill: currentColor;
  d: path("m13.96 7.17l-1.31 3.72h2.69l-1.3-3.72z");
}

.xeogbabsk {
  fill: currentColor;
  d: path("M3 6c-.55 0-1 .45-1 1v13c0 1.1.9 2 2 2h13c.55 0 1-.45 1-1s-.45-1-1-1H4V7c0-.55-.45-1-1-1");
}

</style>
