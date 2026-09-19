<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fr7uvi35z"/><path class="k08owpbvp"/><circle class="e285v2exz"/><path class="qdy6-qjsw"/><circle class="kqkzkcb7n"/><g class="i1_vehbic"><path class="gbnagrbff"/><path class="e8m1wwbah"/><path class="ayq09db4i"/></g><path class="y9ufnibpb"/><g class="i1_vehbic"><ellipse transform="rotate(-44.842 30.286 30.561)" class="pzjsbdcyz"/><ellipse transform="rotate(-44.716 32.004 32.294)" class="dud1kzmem"/><path class="torj2kygd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:squid" /></template>
<style>
.ayq09db4i {
  d: path("M61.1 8.3s-.3 5.5.8 10.4c1.2 5-13 5.6-17.9 8.8c0 0 11.1-14.1 17.1-19.2");
}

.dud1kzmem {
  cx: 32px;
  cy: 32.3px;
  rx: 4.6px;
  ry: 0.3px;
}

.e285v2exz {
  cx: 29.3px;
  cy: 23.1px;
  r: 1.5px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.e8m1wwbah {
  d: path("M44.5 30.5c.3-.5.7-1 1.1-1.5c-.5-.5-1.3-.8-2.7-.6c-2.5.3-4.5-.1-5.7-1.3s-1.6-3.2-1.3-5.7c.2-1.4-.1-2.2-.6-2.8c-.5.4-1 .8-1.5 1.1c.6.5 1 1.3.8 3c-.3 2.5.1 4.5 1.3 5.7s3.2 1.6 5.7 1.3c1.5-.2 2.4.2 2.9.8");
}

.fr7uvi35z {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M41.4 42.7c-1.3 1.9 5.5 2.3 2 5.8c-9.9 10-18.5-8.5-5.6-10.9c1.8-5.2 6.1-6 6.1-6c1.3-3.4 5.6-6.4 5.6-6.4L38.9 14.5s-3 4.4-6.3 5.7c0 5.5-6 6.2-6 6.2c-2.4 12.8-20.7 4.2-10.8-5.7c3.5-3.5 3.9 3.3 5.8 2c.9-.6 2.5-3.8-.1-6.4C18.2 13 5.7 19.2 8.3 30.8c.7 3.1 2.3 5.1 4.3 6.2C5.7 39.1-2 45.7 4.3 52c1.4 1.5 4.8 4.8 12.2.3s1.7-9.1-1.5-8.3s5.5 4.7-3.8 6.1c-4.6.7-6-6.6 3.7-9c3.7-.9 6.4-.8 8.7-1c-.8 2.1-1.3 4.4-1.6 6.9c-.9 9.5-11.9 13-15.4 14c-3.6 1 8.6 3.2 15.8-5.8c1.8-2.2 2.9-4.2 3.8-6.1c.7 3.3 2.9 6 7.2 7c11.6 2.6 17.7-9.9 14.4-13.2c-2.7-2.7-5.8-1.1-6.4-.2");
}

.gbnagrbff {
  d: path("M55.8 2.9s-5.5.3-10.3-.8c-5-1.2-5.5 13-8.7 18.1c-.1-.1 13.9-11.3 19-17.3M33.2 54.3c-6.9-4.2-4.9-10.5-4.9-10.5c-.7 1.7-1.3 3.5-2.1 5.3c.7 3.3 2.8 6 7.2 7c3.1.7 5.7.3 8-.7c-2 .6-5.5.5-8.2-1.1m-9.5-14.2c-.8 2.1-1.4 4.4-1.6 6.9c-1 9.5-12 13-15.5 14q-.6.15-.6.3c13.9-1.7 17-9.7 18.4-15.4c.7-2.9 1.8-5 2.6-6.3c-1.1.3-2.2.5-3.3.5M12.6 37c.6-.2 1.3-.3 1.9-.4s1.1-.2 1.7-.3c-2.6 0-5.5-.9-7.5-4.2c.8 2.4 2.2 4 3.9 4.9");
}

.i1_vehbic {
  fill: var(--svg-color--9c323c, #9c323c);
}

.k08owpbvp {
  fill: var(--svg-color--e8e8e8, #e8e8e8);
  d: path("M32.6 20.2c-.4.1-.7.3-1.1.3c-3.8.6-4.3 2.5-4.9 5.9v.1c1.4.5 3.3 0 4.7-1.3c1.5-1.6 1.9-3.5 1.3-5");
}

.kqkzkcb7n {
  cx: 41.1px;
  cy: 34.9px;
  r: 1.5px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.pzjsbdcyz {
  cx: 30.3px;
  cy: 30.6px;
  rx: 3.9px;
  ry: 0.4px;
}

.qdy6-qjsw {
  fill: var(--svg-color--e8e8e8, #e8e8e8);
  d: path("M37.7 37.6s.1 0 0 0c3.4-.6 5.3-1.1 5.9-4.9c.1-.4.2-.7.3-1.1c-1.5-.6-3.4-.2-4.9 1.3c-1.3 1.4-1.8 3.3-1.3 4.7");
}

.torj2kygd {
  d: path("M33.9 34.2c-1.5 1.5-2.8 2.6-2.9 2.4c-.1-.1.9-1.5 2.4-3s2.8-2.6 2.9-2.4c.2.2-.9 1.5-2.4 3");
}

.y9ufnibpb {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M56.7 17.8c5.4-6.7 5.8-11.9 3.6-14.1s-7.4-1.8-14 3.7c-7.4 6.1-13.4 5.2-14.1 8.3s4.2.8 3.6 5.7c-.3 2.5.1 4.5 1.3 5.7s3.2 1.6 5.7 1.3c4.9-.6 2.6 4.3 5.7 3.6s2.2-6.8 8.2-14.2");
}

</style>
