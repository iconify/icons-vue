<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny5873gkz"/><path class="r3py1ki2n"/><path class="lnp3epnpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-electric-moped" /></template>
<style>
.lnp3epnpq {
  fill: currentColor;
  d: path("M5 4h5v2H5zm14 7c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3m0 4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1M7 20h4v-2l6 3h-4v2z");
}

.ny5873gkz {
  fill: currentColor;
  d: path("M4 11v1h4V9H6c-1.1 0-2 .9-2 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r3py1ki2n {
  fill: currentColor;
  d: path("M19 5c0-1.1-.9-2-2-2h-3v2h3v2.65L13.52 12H10V7H6c-2.21 0-4 1.79-4 4v3h2c0 1.66 1.34 3 3 3s3-1.34 3-3h4.48L19 8.35zM7 15c-.55 0-1-.45-1-1h2c0 .55-.45 1-1 1m1-3H4v-1c0-1.1.9-2 2-2h2z");
}

</style>
