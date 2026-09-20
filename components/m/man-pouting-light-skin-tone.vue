<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="g6h350bmq"/><path class="lr6xrsblt"/><path class="hossvnbah"/><circle class="tmyhg7rdh"/><path class="u34dir18u"/><path class="x1lu53b3w"/><path class="gnl3e-bsh"/><path class="r5y-17bti"/><path class="jmxtzjb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:man-pouting-light-skin-tone" /></template>
<style>
.g6h350bmq {
  fill: var(--svg-color--4289c1, #4289c1);
  d: path("M27 27H9a4 4 0 0 0-4 4v5h26v-5a4 4 0 0 0-4-4");
}

.gnl3e-bsh {
  fill: var(--svg-color--f7dece, #f7dece);
  d: path("M10.847 13.715c0 1.58-.8 2.861-1.788 2.861s-1.788-1.281-1.788-2.861s.801-2.861 1.788-2.861s1.788 1.281 1.788 2.861m17.882 0c0 1.58-.8 2.861-1.788 2.861s-1.788-1.281-1.788-2.861s.8-2.861 1.788-2.861s1.788 1.281 1.788 2.861");
}

.hossvnbah {
  fill: var(--svg-color--f7dece, #f7dece);
  d: path("M9 5.938V17c0 4.971 4.029 9 9 9s9-4.029 9-9V6.25z");
}

.jmxtzjb8q {
  fill: var(--svg-color--f7dece, #f7dece);
  d: path("M15 24v4a3 3 0 1 0 6 0v-4z");
}

.lr6xrsblt {
  fill: var(--svg-color--2a6797, #2a6797);
  d: path("M26 32h1v4h-1zM9 32h1v4H9z");
}

.r5y-17bti {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M18 .823c-7.019 0-10.139 4.684-10.139 8.588s1.343 4.986 1.56 3.903c.78-3.903 3.12-5.101 3.12-5.101c4.68 3.904 3.9.781 3.9.781c4.679 4.684 2.34 0 2.34 0c1.56 1.562 6.239 1.562 6.239 1.562s.78 1.198 1.559 2.759c.78 1.562 1.56 0 1.56-3.903c0-3.905-3.9-8.589-10.139-8.589");
}

.tmyhg7rdh {
  cx: 18px;
  cy: 23px;
  r: 1px;
  fill: var(--svg-color--c1694f, #c1694f);
}

.u34dir18u {
  fill: var(--svg-color--662113, #662113);
  d: path("M14 16a1 1 0 0 1-1-1v-1a1 1 0 0 1 2 0v1a1 1 0 0 1-1 1m8 0a1 1 0 0 1-1-1v-1a1 1 0 0 1 2 0v1a1 1 0 0 1-1 1");
}

.x1lu53b3w {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M19 19.5h-2a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1");
}

</style>
