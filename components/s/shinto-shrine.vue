<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r7v_jnmxr"/><path class="zjzxttbns"/><path class="rrxnp5ctz"/><path class="fs322ib5t"/><path class="gfjqm7bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:shinto-shrine" /></template>
<style>
.fs322ib5t {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M20 15a2 2 0 0 1-4 0V9a2 2 0 0 1 4 0z");
}

.gfjqm7bcf {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M11 34a2 2 0 0 1-2 2H5a2 2 0 0 1 0-4h4a2 2 0 0 1 2 2m22 0a2 2 0 0 1-2 2h-4a2 2 0 0 1 0-4h4a2 2 0 0 1 2 2");
}

.r7v_jnmxr {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M9 9a2 2 0 0 0-4 0v24a2 2 0 0 0 4 0zm22 0a2 2 0 0 0-4 0v24a2 2 0 0 0 4 0z");
}

.rrxnp5ctz {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M35.906 4c0 1.104-.659 1.797-1.908 2c0 0-4 1-15.999 1C6.001 7 2.002 6 2.002 6C.831 5.812.109 5.114.109 4.01S-.102 1 1.002 1c0 0 3.999 2 16.997 2s16.998-2 16.998-2c1.105 0 .909 1.895.909 3");
}

.zjzxttbns {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M36 16a2 2 0 0 1-2 2H2a2 2 0 0 1 0-4h32a2 2 0 0 1 2 2m-1-9c0 1.104-.781 1.719-2 2c0 0-3 1-15 1S3 9 3 9c-1.266-.266-2-.896-2-2s.896-2 2-2h30a2 2 0 0 1 2 2");
}

</style>
