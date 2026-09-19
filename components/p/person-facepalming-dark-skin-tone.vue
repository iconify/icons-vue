<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qq5sy0m9h"/><path class="k-7imtbay"/><path class="y15pvou7f"/><ellipse class="qquwyp1rc"/><path class="m7aajibpa"/><path class="r_i79xbru"/><path class="m937d3bev"/><path class="u-w49-mnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:person-facepalming-dark-skin-tone" /></template>
<style>
.k-7imtbay {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M21 52.2h25.2V62H21z");
}

.m7aajibpa {
  d: path("M13.7 17.3s2.9 1.4 3.9 5.3c.6 2.3.9 2.4 2 3.2l6.2-12c.6-1.1 1.9-1.5 2.9-.9s1.4 1.9.8 3l.7-1.4c.7-1.3 2.3-1.8 3.5-1.1s1.7 2.2 1 3.5l-.5 1c.6-1.1 2-1.6 3-1c1.1.6 1.4 1.9.8 3.1l-1.2 2.3c.6-1 1.8-1.5 2.8-.9c1 .5 1.6 1.9 1 2.9c-10.1 18.1-10.7 19.2-15.3 19.8c0 0-3.9 4.4-7 17.9l1.6-25.1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.m937d3bev {
  fill: var(--svg-color--8a6859, #8a6859);
  d: path("M11.4 17.3c1.5-1 3.9.3 4.8 4.2c.6 2.3.7 3.2 1.8 4l7-12.8c1.8-3 4.9-1.1 3.5 1.9l-5.1 10l6.4-10.8c1.6-3 5.8-1.6 4.1 2l-6.2 10.7l6-9.2c2.1-3.2 5-.9 3.5 1.6l-5.1 9.7l4.8-7c1.6-2.5 4.3-.5 3 1.8c0 0-8 15.5-11.3 18c-4.8 3.7-16.6-.9-15.7-11.1c.2-2-.6-4-1-6.2c-.3-2.8-2.2-5.7-.5-6.8");
}

.qq5sy0m9h {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M33.6 2C52 2 62 13.4 62 28.3V62H5.3V28.3C5.3 6.1 20.6 6.5 20.6 6.5S21.8 2 33.6 2");
}

.qquwyp1rc {
  cx: 33.6px;
  cy: 55.2px;
  fill: var(--svg-color--574137, #574137);
  rx: 4px;
  ry: 3px;
}

.r_i79xbru {
  fill: var(--svg-color--b386e2, #b386e2);
  d: path("m23.9 42l-8.7-4.7S7.8 47.3 2 61.9h16.3c0 .1.1-11.2 5.6-19.9");
}

.u-w49-mnw {
  fill: var(--svg-color--574137, #574137);
  d: path("M38.4 40.8c2.7 5.1 8.2 5.1 10.9 0c.1-.3-.2-.4-.7-.7c-2.7 2.1-7.2 2-9.6 0c-.4.4-.8.5-.6.7");
}

.y15pvou7f {
  fill: var(--svg-color--8a6859, #8a6859);
  d: path("M54.1 44.8s4.1-1 4.1-7.1c0-4.8-3.1-5.6-3.1-5.6c-19.1 0-29.3-9.4-29.3-9.4s-6.9 7.7-13.5 9.4c0 0-3.2.6-3.2 5.6c0 6.1 4.3 7.1 4.3 7.1c0 3.8 12.7 16.2 20.3 16.2c7.6.1 20.4-12.3 20.4-16.2");
}

</style>
