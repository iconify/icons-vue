<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="nv_n5pb_p"><circle class="f97bvyy1m"/><circle class="fi-bbccoy"/></g><path class="jdzv6p5dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:smiling-face-with-smiling-eyes" /></template>
<style>
.f97bvyy1m {
  cx: 50.8px;
  cy: 36px;
  r: 8px;
  opacity: var(--svg-opacity--0-8, 0.8);
}

.fi-bbccoy {
  cx: 13.2px;
  cy: 36px;
  r: 8px;
  opacity: var(--svg-opacity--0-8, 0.8);
}

.jdzv6p5dq {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M44.6 40.3c-8.1 5.7-17.1 5.6-25.2 0c-1-.7-1.8.5-1.2 1.6c2.5 4 7.4 7.7 13.8 7.7s11.3-3.6 13.8-7.7c.6-1.1-.2-2.3-1.2-1.6M28.5 26.9c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.6.5 1.5-.4 1.3-.9m21.9 0c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.5.5 1.5-.4 1.3-.9");
}

.nv_n5pb_p {
  fill: var(--svg-color--ff717f, #ff717f);
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
