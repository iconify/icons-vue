<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="fjscq_omc"/><path class="qqxvfgbxr"/><g class="n1mjunbsu"><path class="ux6d36b7n"/><path class="shxp7h1vy"/><path class="dsnk6yb9l"/><circle class="kv9pmmmlg"/><path class="f8032so8y"/><path class="pnoj4bcfv"/><path class="fldeonb-o"/></g><path class="ywvslyb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:no-pedestrians" /></template>
<style>
.dsnk6yb9l {
  d: path("m67.37 87.46l7.27 19.97a3.98 3.98 0 0 0 5.11 2.37a3.98 3.98 0 0 0 2.37-5.11l-7.27-19.97z");
}

.f8032so8y {
  d: path("m65.73 73.38l-.31.06c-3.97.75-7.84-1.88-8.59-5.86L53.1 47.86c-.75-3.97 1.88-7.84 5.86-8.59l.31-.06c3.97-.75 7.84 1.88 8.59 5.86l3.73 19.73c.74 3.97-1.89 7.83-5.86 8.58");
}

.fjscq_omc {
  cx: 63.3px;
  cy: 64.7px;
  r: 61.69px;
  fill: var(--svg-color--006ca2, #006ca2);
}

.fldeonb-o {
  d: path("m73.64 52.43l3 11.25a3.585 3.585 0 0 0 4.39 2.53a3.585 3.585 0 0 0 2.53-4.39l-3-11.25zm-15.82 2.59l-13.4 9.57a3.573 3.573 0 0 0-.82 4.99a3.573 3.573 0 0 0 4.99.82l13.4-9.57z");
}

.kv9pmmmlg {
  cx: 55.61px;
  cy: 26.93px;
  r: 9.5px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.pnoj4bcfv {
  d: path("m60.64 46.31l14.69 8.27c1.72.97 3.91.36 4.87-1.37c.97-1.72.36-3.91-1.37-4.87l-14.69-8.27z");
}

.qqxvfgbxr {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M64 128C28.71 128 0 99.29 0 64S28.71 0 64 0s64 28.71 64 64s-28.71 64-64 64m0-117.11c-29.29 0-53.11 23.83-53.11 53.11c0 29.29 23.83 53.11 53.11 53.11S117.11 93.29 117.11 64S93.29 10.89 64 10.89");
}

.shxp7h1vy {
  d: path("m47.21 84.58l-1.52 21.19c-.15 2.2 1.5 4.1 3.7 4.26c2.2.15 4.1-1.5 4.26-3.7l1.52-21.19zM61.1 66.12L67.26 87a3.99 3.99 0 0 0 7.84-1.48l-3.9-20.88z");
}

.ux6d36b7n {
  d: path("M60.22 64.26L48.13 82.09c-1.41 1.69-1.17 4.21.52 5.62s4.21 1.17 5.62-.52l13.6-16.32z");
}

.ywvslyb_c {
  fill: var(--svg-color--db4437, #db4437);
  d: path("m111.37 102.73l-8.43 8.41l-86.31-85.73L25.06 17z");
}

</style>
