<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u2xpk9bpi"/><g class="ra_kpfz0x"><path class="graq2lbag"/><path class="i8apj7b9t"/><path class="pbm71rbpf"/><path class="ferya_bvd"/><path class="wl0ui3bsg"/></g><ellipse class="m1te-9b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:rosette" /></template>
<style>
.ferya_bvd {
  d: path("M37.8 56.5c-6-8.1-7.4-17.2-3-20.4c4.4-3.1 12.9.9 18.9 9s-3.3 7.6-5.4 9.1c-2.1 1.6-4.5 10.4-10.5 2.3");
}

.graq2lbag {
  d: path("M41.8 9.9c0 10-4.4 18.2-9.9 18.2S22 20 22 9.9s7.2-4.2 9.9-4.2s9.9-5.8 9.9 4.2");
}

.i8apj7b9t {
  d: path("M13 16.5c9.8 3.1 16.4 9.7 14.7 14.8s-11 6.6-20.8 3.5s-1.9-8-1.1-10.5c.8-2.4-2.6-10.9 7.2-7.8");
}

.m1te-9b3s {
  cx: 32px;
  cy: 32.4px;
  fill: var(--svg-color--ffce31, #ffce31);
  rx: 3.8px;
  ry: 3.7px;
}

.pbm71rbpf {
  d: path("M10.5 45.3c6-8.1 14.5-12.2 18.9-9c4.4 3.1 3.1 12.2-3 20.4c-6 8.1-8.4-.7-10.5-2.2c-2.1-1.6-11.5-1.1-5.4-9.2");
}

.ra_kpfz0x {
  fill: var(--svg-color--e84d88, #e84d88);
}

.u2xpk9bpi {
  fill: var(--svg-color--a01a5d, #a01a5d);
  d: path("m46.5 31.2l-2.8-8.3S52.2 10.6 49 8.3s-12.6 9.5-12.6 9.5h-9S18 6.1 14.8 8.3s5.3 14.6 5.3 14.6l-2.8 8.3S3 36.3 4.2 40s15.9-.4 15.9-.4l7.3 5.2s.5 14.9 4.5 14.9s4.5-14.9 4.5-14.9l7.3-5.2s14.7 4.1 15.9.4c1.3-3.7-13.1-8.8-13.1-8.8");
}

.wl0ui3bsg {
  d: path("M57.1 34.6c-9.8 3.1-19.1 1.5-20.8-3.5c-1.6-5.1 5-11.7 14.7-14.8c9.8-3.1 6.4 5.4 7.2 7.9c.8 2.4 8.7 7.3-1.1 10.4");
}

</style>
