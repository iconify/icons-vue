<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tfwrjg2_f"/><g class="y9tr6bcfx"><path class="zl-97bcdl"/><path class="u0foekbrl"/><path class="nyru16mgy"/><path class="y0t3sdg6c"/></g><g class="y9tr6bcfx"><path class="x9ld7zbdq"/><path class="k2iqodxgo"/></g><path class="bpr36f21j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smashy-road-wanted" /></template>
<style>
.bpr36f21j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.747 28.687l9.448 2.228m-9.448 1.644l9.448 2.228m1.864-3.681v-1.957M6.044 28.037V26.08m13.404 8.28v-.368M5.655 31.07v-.368m17.524-6.839l-6.575 2.674v1.219l-1.27.516v.6m2.389-6.274l-6.575 2.675v1.219l-1.232.501v.602");
}

.k2iqodxgo {
  d: path("m13.397 16.404l14.357 3.325l13.707-5.576");
}

.nyru16mgy {
  d: path("M39.584 30.09v-3.372l1.846-.785v3.373zm-10.969 4.652v2.027l-4.874 2.07l-2.483-.575v-.903");
}

.tfwrjg2_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 25.717l.702.164v-1.568l16.07 3.789v1.57l1.092.258v7.69L4.5 33.426zm8.897-4.737l-8.195 3.333m22.553 1.152l-6.483 2.637");
}

.u0foekbrl {
  d: path("m22.364 30.106l6.052-2.463l.923.212v6.58l-.725.307m14.161-5.983l.001 2.026l-4.875 2.07l-2.482-.574v-1.16");
}

.x9ld7zbdq {
  d: path("M13.397 14.737v6.86m14.357 3.325v-6.86m13.707 1.285l-13.707 5.575l-14.357-3.325m28.064-9.111v6.86m0-6.86L27.104 9.16l-13.707 5.576l14.357 3.325z");
}

.y0t3sdg6c {
  d: path("M27.27 31.917v3.372l-1.847.785V32.7zM5.65 33.696v.904l2.481.575l1.358-.577");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zl-97bcdl {
  d: path("M42.576 21.658v-2.42l-1.115-.258M29.338 33.593l7.188-2.923v-6.547l6.05-2.464l.924.212v6.58l-.725.308");
}

</style>
