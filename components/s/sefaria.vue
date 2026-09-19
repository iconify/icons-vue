<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nonxbkb3v"/><ellipse transform="rotate(-85.09 38.466 8.985)" class="b0wlije0c"/><path class="mvx1rgbrs"/><ellipse transform="rotate(-4.908 9.535 8.985)" class="vzuaxxaix"/><path class="oy6d8qbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sefaria" /></template>
<style>
.b0wlije0c {
  cx: 38.465px;
  cy: 8.986px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.267px;
  ry: 4.048px;
}

.mvx1rgbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.984 38.618c-.06.697-1.915 1.107-4.142.916s-3.985-.911-3.925-1.608m6.575-29.26l.234-2.724m-3.101 36.116l.191-2.227m-19.733-1.905L13.569 8.639M8.016 38.618L5.502 9.332");
}

.nonxbkb3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.744 17.959a44.9 44.9 0 0 0 13.812 0c.002 18.674-12.016 18.16-12.018 2.824M34.431 8.639l-2.514 29.287M42.498 9.332l-2.514 29.286");
}

.oy6d8qbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.083 37.926c.06.697-1.697 1.417-3.925 1.608s-4.082-.219-4.142-.916M9.274 5.942l.234 2.724m2.676 31.165l.191 2.227m1.679-31.155a21.8 21.8 0 0 0 10.028 2.161a21.8 21.8 0 0 0 10.027-2.16M15.933 36.185a21.8 21.8 0 0 0 8.149 1.36a21.8 21.8 0 0 0 8.008-1.308");
}

.vzuaxxaix {
  cx: 9.535px;
  cy: 8.986px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.048px;
  ry: 1.267px;
}

</style>
