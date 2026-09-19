<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b6-rf_bvj"/><circle class="wkxyrxmoa"/><path class="zlfbtcbcj"/><circle class="e93ufabxb"/><path class="vraxcrb4j"/><path class="y_93tcbfb"/><g class="jeunsn1yj"><path class="eo_24ej8w"/><path class="lt0r8-b3m"/></g><circle class="rgb__h_9w"/><g class="jeunsn1yj"><circle class="syw3wzb3s"/><path class="l56wczu_m"/></g><circle class="ucjzp-bjj"/><circle class="l0l2cxr9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:panda-face" /></template>
<style>
.b6-rf_bvj {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M62 14c0 6.6-5.4 12-12 12s-12-5.4-12-12S43.4 2 50 2s12 5.4 12 12");
}

.e93ufabxb {
  cx: 14px;
  cy: 14px;
  r: 7.2px;
  fill: var(--svg-color--555e63, #555e63);
}

.eo_24ej8w {
  d: path("M31 50.1h2v5h-2z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.l0l2cxr9d {
  cx: 19.3px;
  cy: 34.4px;
  r: 2.5px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.l56wczu_m {
  d: path("M11.7 29.1c4.2-4.2 10.5-4.7 14.1-1.2c7.2 7.2-8 22.5-15.3 15.3c-3.6-3.6-3-9.9 1.2-14.1");
}

.lt0r8-b3m {
  d: path("M31.9 57c-4.1 0-7.9-1.3-7.9-2.7c0-.2.1-.3.2-.4s.4-.2.6-.2c.3 0 .6.1 1 .3c1 .4 2.9 1.1 6.1 1.1c3.1 0 5-.7 6.1-1.1c.5-.2.8-.3 1-.3c.4 0 .8.2.8.6c0 1.4-3.7 2.7-7.9 2.7M24 49.6c0-2.5 3.5-3 7.9-3s7.9.5 7.9 3c0 2-6.3 2.8-7.9 2.8s-7.9-.8-7.9-2.8m14.2-21.7c3.6-3.6 9.9-3 14.1 1.2s4.7 10.5 1.2 14.1c-7.2 7.2-22.5-8-15.3-15.3");
}

.rgb__h_9w {
  cx: 44.7px;
  cy: 34.4px;
  r: 5px;
  fill: var(--svg-color--42ade2, #42ade2);
}

.syw3wzb3s {
  cx: 44.7px;
  cy: 34.4px;
  r: 2.5px;
}

.ucjzp-bjj {
  cx: 19.3px;
  cy: 34.4px;
  r: 5px;
  fill: var(--svg-color--42ade2, #42ade2);
}

.vraxcrb4j {
  fill: var(--svg-color--d1dbe3, #d1dbe3);
  d: path("M31.9 8C18.7 8 4 17.9 4 36.4c0 7.7 2.5 9 5.3 14.3c7.8 15.1 37.4 15.1 45.2 0c2.8-5.3 5.5-6.6 5.5-14.3C60 17.9 45 8 31.9 8");
}

.wkxyrxmoa {
  cx: 50px;
  cy: 14px;
  r: 7.2px;
  fill: var(--svg-color--555e63, #555e63);
}

.y_93tcbfb {
  fill: var(--svg-color--e4eef7, #e4eef7);
  d: path("M19 50.2c0-6.8 8.8-9.4 13-9.4s13 2.6 13 9.4c0 8.6-4.8 10.6-13 10.6c-8.3 0-13-2-13-10.6");
}

.zlfbtcbcj {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M26 14c0 6.6-5.4 12-12 12S2 20.6 2 14S7.4 2 14 2s12 5.4 12 12");
}

</style>
