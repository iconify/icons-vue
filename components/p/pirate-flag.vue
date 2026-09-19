<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#izci3rd)" class="rt91qb_nw"/><rect fill="url(#izESu2i)" class="f9hp74h9u"/><rect fill="url(#isP58wX)" class="rt91qb_nw"/><path fill="url(#i5z7hfc)" class="ou1e38bwp"/><defs><linearGradient id="izci3rd" x1="2.875" x2="30.127" y1="6.625" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="pe8-g7dze"/><stop offset="1" class="ahozow9sg"/></linearGradient><linearGradient id="izESu2i" x1="30.297" x2="29.5" y1="19.332" y2="19.332" gradientUnits="userSpaceOnUse"><stop class="l_mseccqr"/><stop offset="1" class="ybfvvwb3h"/></linearGradient><linearGradient id="isP58wX" x1="8.752" x2="8.752" y1="26.281" y2="25.406" gradientUnits="userSpaceOnUse"><stop offset=".015" class="ig81ne7ta"/><stop offset="1" class="yb0d54efj"/></linearGradient><radialGradient id="i5z7hfc" cx="0" cy="0" r="1" gradientTransform="rotate(-90 18.131 1.931)scale(10.25)" gradientUnits="userSpaceOnUse"><stop class="h4xzwac8i"/><stop offset="1" class="r3zkp6bse"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pirate-flag" /></template>
<style>
.ahozow9sg {
  stop-color: var(--svg-color--402f4d, #402F4D);
}

.f9hp74h9u {
  width: 27.875px;
  height: 19.914px;
  x: 2.252px;
  y: 6.043px;
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  rx: 0.6px;
}

.ft5dv1b6b {
  fill: none;
}

.h4xzwac8i {
  stop-color: var(--svg-color--f2e3fc, #F2E3FC);
}

.ig81ne7ta {
  stop-color: var(--svg-color--693ca6, #693CA6);
}

.l_mseccqr {
  stop-color: var(--svg-color--fbf2ff, #FBF2FF);
}

.ou1e38bwp {
  d: path("M11.96 10.75a1 1 0 1 0-1.707-.707a1 1 0 1 0 .706 1.707l1.116 1.116a.25.25 0 0 0 .354 0l.646-.646a.25.25 0 0 0 0-.354zm0 10.482a1 1 0 1 1-1.707.707a1 1 0 1 1 .706-1.707l1.116-1.116a.25.25 0 0 1 .354 0l.646.647a.25.25 0 0 1 0 .353zm8.189-11.189c0 .276.112.526.293.707l-1.117 1.116a.25.25 0 0 0 0 .354l.647.646a.25.25 0 0 0 .353 0l1.117-1.116a1 1 0 1 0 .707-1.707a1 1 0 1 0-2 0m.293 11.19a1 1 0 1 0 1.707.707a1 1 0 1 0-.707-1.708l-1.117-1.116a.25.25 0 0 0-.353 0l-.647.647a.25.25 0 0 0 0 .353zm-.44-6.19c0-1.933-1.679-3.5-3.75-3.5s-3.75 1.567-3.75 3.5c0 .442.088.864.248 1.254l-.274.41a1.5 1.5 0 0 0 .934 2.298l.342.074v.714a.75.75 0 0 0 1.5 0v-.5h.25v.5a.75.75 0 0 0 1.5 0v-.5h.25v.5a.75.75 0 0 0 1.5 0v-.714l.342-.074a1.5 1.5 0 0 0 .934-2.298l-.273-.41c.16-.39.247-.812.247-1.254m-4.82 1.582c-.48.482-1.184.558-1.57.172c-.322-.323-.27-1.3.074-1.645c.344-.343 1.396-.369 1.668-.097c.386.386.31 1.09-.171 1.57m3.7.172c-.387.386-1.09.31-1.571-.172c-.481-.48-.558-1.184-.172-1.57c.272-.272 1.325-.246 1.669.097c.343.344.396 1.322.073 1.645m-2.847.126a.25.25 0 0 1 .434 0l.57.996a.25.25 0 0 1-.218.374h-1.138a.25.25 0 0 1-.217-.374z");
}

.pe8-g7dze {
  stop-color: var(--svg-color--221f25, #221F25);
}

.r3zkp6bse {
  stop-color: var(--svg-color--f4e8fd, #F4E8FD);
}

.rt91qb_nw {
  width: 27.875px;
  height: 19.914px;
  x: 2.252px;
  y: 6.043px;
  rx: 0.6px;
}

.yb0d54efj {
  stop-color: var(--svg-color--693ca6, #693CA6);
  stop-opacity: 0;
}

.ybfvvwb3h {
  stop-color: var(--svg-color--fbf2ff, #FBF2FF);
  stop-opacity: 0;
}

</style>
