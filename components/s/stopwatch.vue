<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wxmowvb_e"/><path class="s-rq5hbxd"/><path class="fr3_z6dyi"/><path class="gi2006u3l"/><path class="wr_-_rbcv"/><path class="h40b2eybt"/><g class="w1ddu1bbx"><path class="rmk3sybmy"/><circle class="uvy88fb9g"/></g><circle class="kybxchb9g"/><circle class="md3l-l_1t"/><path class="cgiblww-p"/><g class="jeunsn1yj"><path class="suatd5boo"/><circle class="ljvys8bdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:stopwatch" /></template>
<style>
.cgiblww-p {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M52 39c0 5.5-2.2 10.5-5.8 14.1L32 39V19c11 0 20 9 20 20");
}

.fr3_z6dyi {
  fill: var(--svg-color--647a87, #647a87);
  d: path("M34.5 11.6h-5V5.9c0-1.5 5-1.5 5 0z");
}

.gi2006u3l {
  fill: var(--svg-color--4e5c66, #4e5c66);
  d: path("m10.737 20.686l2.969-2.97l2.97 2.969l-2.968 2.97z");
}

.h40b2eybt {
  fill: var(--svg-color--4e5c66, #4e5c66);
  d: path("m47.344 20.705l2.97-2.97l2.97 2.97l-2.97 2.97z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.kybxchb9g {
  cx: 32px;
  cy: 39px;
  r: 21.7px;
  fill: var(--svg-color--d2d3d5, #d2d3d5);
}

.ljvys8bdp {
  cx: 32px;
  cy: 39px;
  r: 2.8px;
}

.md3l-l_1t {
  cx: 32px;
  cy: 39px;
  r: 20px;
  fill: var(--svg-color--fff, #fff);
}

.rmk3sybmy {
  d: path("m53.4 22.6l-5-5l3.1-3.1c.6-.6 1.6-.6 2.2 0l2.8 2.8c.6.6.6 1.6 0 2.2z");
}

.s-rq5hbxd {
  fill: var(--svg-color--4e5c66, #4e5c66);
  d: path("M30.5 8.6h3v6.5h-3z");
}

.suatd5boo {
  d: path("M43.5 50.4L33.3 38.3l-2 2zM31.3 20.7h1.4v5.6h-1.4zm0 31h1.4v5.6h-1.4zM13.7 38.3h5.6v1.4h-5.6zm31 0h5.6v1.4h-5.6zM22.178 23.463l1.213-.7l1.4 2.425l-1.213.7zm-6.45 7l.7-1.212l2.425 1.4l-.7 1.213zm.033 17.149l2.424-1.402l.7 1.212l-2.423 1.402zm6.491 6.964l1.4-2.425l1.212.7l-1.4 2.425zm16.906-1.85l1.212-.7l1.4 2.425l-1.211.7zM45.1 47.43l.7-1.213l2.425 1.401l-.7 1.213zm-.074-16.802l2.424-1.4l.7 1.212l-2.424 1.4zm-5.89-5.478l1.401-2.424l1.212.7l-1.4 2.425z");
}

.uvy88fb9g {
  cx: 32px;
  cy: 39px;
  r: 25px;
}

.w1ddu1bbx {
  fill: var(--svg-color--647a87, #647a87);
}

.wr_-_rbcv {
  fill: var(--svg-color--647a87, #647a87);
  d: path("m15.6 17.6l-5 5l-3.1-3.1c-.6-.6-.6-1.6 0-2.2l2.8-2.8c.6-.6 1.6-.6 2.2 0z");
}

.wxmowvb_e {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M32 0c-3.3 0-6 2.7-6 6s2.7 6 6 6s6-2.7 6-6s-2.7-6-6-6m0 10.3c-2.4 0-4.3-1.9-4.3-4.3s1.9-4.3 4.3-4.3s4.3 1.9 4.3 4.3s-1.9 4.3-4.3 4.3");
}

</style>
