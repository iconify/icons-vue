<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i5ries6-b"/><g class="y9tr6bcfx"><path class="j9xaqjb3i"/><path class="xj7ojzbgr"/></g><path class="zcu7s637t"/><path class="lhm9f6nhp"/><path class="dgt859bbm"/><path class="y6oir4h0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:robotfindskitten" /></template>
<style>
.dgt859bbm {
  fill: currentColor;
  d: path("M7.606 31.556a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m4.711 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.i5ries6-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.873 21.466a1.282 1.282 0 0 0-.995 2.091l2.055 2.413l2.035-2.389l.01-.011l.01-.013a1.283 1.283 0 1 0-2.055-1.53a1.28 1.28 0 0 0-1.058-.56z");
}

.j9xaqjb3i {
  d: path("M37.855 22.76a.942.942 0 1 1-1.885 0a.942.942 0 0 1 1.885 0m-4.711 0a.942.942 0 1 1-1.885 0a.942.942 0 0 1 1.885 0");
}

.lhm9f6nhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.436 19.94a.942.942 0 1 1-1.885 0a.942.942 0 0 1 1.885 0m3.769 0a.942.942 0 1 1-1.885 0a.942.942 0 0 1 1.885 0m1.718 6.356h2.355m-2.355-1.413h2.355M4.5 22.292h9.422V30.3H4.5z");
}

.xj7ojzbgr {
  d: path("m29.375 16.164l3.769 3.769h2.826l3.77-3.77v12.25H29.374zm-1.178 10.364h2.355m-2.355-1.413h2.355m8.009 1.413h2.356m-2.356-1.413h2.356m-6.36.941v-1.23m0 1.23l-.744.923m-.333-1.599l1.077.676m0 0l.743.923m.334-1.599l-1.077.676m-3.77 5.056a.942.942 0 1 1 0-1.632m5.18 1.632a.942.942 0 1 1 0-1.632m-4.239 1.757h1.885m3.297 0h1.884m.941 0h1.885m.942-4.761s.938 1.067.938 2.38s-.938 2.38-.938 2.38");
}

.y6oir4h0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.775 26.21v.015c0 .69-.559 1.248-1.248 1.248h0c-.69 0-1.249-.559-1.249-1.248v-1.272c0-.69.559-1.249 1.249-1.249h0c.69 0 1.248.56 1.248 1.249v.015");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zcu7s637t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.907 16.457c2.86 0 5.012 2.288 5.012 5.11v.728H4.504v-.729c0-2.821 1.543-5.109 4.404-5.109zm4.472-.763l-1.47 1.708m-7.154-1.708l1.414 1.708");
}

</style>
