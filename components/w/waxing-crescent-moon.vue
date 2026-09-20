<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="zef_6xa6v"/><path class="g-qibrbbq"/><circle class="y3nh7pbdf"/><circle class="gaxdcoavk"/><circle class="sv-7lmbxs"/><circle class="qx87bmbxr"/><circle class="sh9dxgbnn"/><circle class="rcfclhrgd"/><circle class="d5q9x0z-i"/><circle class="ajbif3kpb"/><circle class="i8yhjs4xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:waxing-crescent-moon" /></template>
<style>
.ajbif3kpb {
  cx: 32px;
  cy: 19px;
  r: 2px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.d5q9x0z-i {
  cx: 15px;
  cy: 31px;
  r: 1px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.g-qibrbbq {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M0 18c0 9.941 8.059 18 18 18c.295 0 .58-.029.87-.043C24.761 33.393 29 26.332 29 18C29 9.669 24.761 2.607 18.87.044C18.58.03 18.295 0 18 0C8.059 0 0 8.059 0 18");
}

.gaxdcoavk {
  cx: 20px;
  cy: 16px;
  r: 3px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.i8yhjs4xc {
  cx: 10px;
  cy: 23px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.qx87bmbxr {
  cx: 21px;
  cy: 6px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.rcfclhrgd {
  cx: 30px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.sh9dxgbnn {
  cx: 3px;
  cy: 18px;
  r: 1px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.sv-7lmbxs {
  cx: 21.5px;
  cy: 27.5px;
  r: 3.5px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.y3nh7pbdf {
  cx: 10.5px;
  cy: 8.5px;
  r: 3.5px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.zef_6xa6v {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffd983, #ffd983);
}

</style>
