<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5xdm1bmj"/><path class="uyu701byu"/><g class="y9tr6bcfx"><ellipse class="mb6rhtbha"/><ellipse class="e42m9p9uw"/><path class="b9ipbdy0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:octotc" /></template>
<style>
.b9ipbdy0a {
  d: path("M27.862 21.427c.314-6.767 5.206-2.722 2.93.628m-10.263-.77c.228-4.15-4.923-4.515-3.184.688");
}

.e42m9p9uw {
  cx: 29.832px;
  cy: 17.442px;
  rx: 3.55px;
  ry: 4.79px;
}

.mb6rhtbha {
  cx: 18.437px;
  cy: 17.415px;
  rx: 3.55px;
  ry: 4.79px;
}

.uyu701byu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.68 34.744c10.743 9.862 20.66 8.701 18.857.953c-6.551 6.64-15.016-2.178-8.751-12.606C48.596.694-1.263.433 13.677 22.935c9.426 12.946-5.806 19.302-8.074 12.71c-.87 9.48 11.359 7.076 18.076-.901");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z5xdm1bmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.572 34.879c-18.623-2.932-9.416-19.66-3.509-10.408c-3.639-2.812-5.415 6.642 4.377 4.054m16.524 6.354c17.426-1.2 9.156-20.507 3.947-10.72c4.734-1.57 2.342 7.788-5.236 4.79");
}

</style>
