<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGkx6Ypejx)" class="strxq0bvy"/><path fill="url(#SVGe8gR0cWr)" class="jrwqtccvr"/><path fill="url(#SVGQNmOoeaZ)" class="phm-eimwf"/><defs><radialGradient id="SVGkx6Ypejx" cx="0" cy="0" r="1" gradientTransform="rotate(152.033 8.102 6.706)scale(11.246 9.68923)" gradientUnits="userSpaceOnUse"><stop class="afpelqb9f"/><stop offset=".359" class="p6v601beq"/><stop offset="1" class="at-izgb3d"/></radialGradient><radialGradient id="SVGe8gR0cWr" cx="0" cy="0" r="1" gradientTransform="rotate(135.115 4.847 5.285)scale(9.52642 11.0623)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="gy4hxcbsh"/><stop offset=".87" class="k6-r8961q"/></radialGradient><radialGradient id="SVGQNmOoeaZ" cx="0" cy="0" r="1" gradientTransform="rotate(-47.685 26.373 -4.382)scale(12.0539 7.71216)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="p_x1tz3ro"/><stop offset=".724" class="zf95fmijn"/><stop offset=".958" class="pl7-n92ft"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:soul" /></template>
<style>
.afpelqb9f {
  stop-color: var(--svg-color--ffd8b0, #ffd8b0);
}

.at-izgb3d {
  stop-color: var(--svg-color--ff87cd, #ff87cd);
}

.ft5dv1b6b {
  fill: none;
}

.gy4hxcbsh {
  stop-color: var(--svg-color--ff2e79, #ff2e79);
}

.jrwqtccvr {
  d: path("m9.746 3.933l-5.81 5.786a3.174 3.174 0 0 0 0 4.502a3.205 3.205 0 0 0 4.52 0l5.81-5.786a3.174 3.174 0 0 0 0-4.502a3.205 3.205 0 0 0-4.52 0");
}

.k6-r8961q {
  stop-color: var(--svg-color--ff8bd1, #ff8bd1);
}

.p_x1tz3ro {
  stop-color: var(--svg-color--ff2b9d, #ff2b9d);
}

.p6v601beq {
  stop-color: var(--svg-color--ffa3ac, #ffa3ac);
}

.phm-eimwf {
  d: path("m15.544 9.779l-5.81 5.787a3.174 3.174 0 0 0 0 4.501a3.205 3.205 0 0 0 4.52 0l5.81-5.786a3.175 3.175 0 0 0 0-4.502a3.205 3.205 0 0 0-4.52 0");
}

.pl7-n92ft {
  stop-color: var(--svg-color--fac7bd, #fac7bd);
}

.strxq0bvy {
  d: path("M17.81 8.849H6.215c-1.762 0-3.19 1.412-3.19 3.154s1.428 3.153 3.19 3.153h11.593c1.762 0 3.19-1.412 3.19-3.153s-1.428-3.154-3.19-3.154");
}

.zf95fmijn {
  stop-color: var(--svg-color--ff9bbf, #ff9bbf);
}

</style>
