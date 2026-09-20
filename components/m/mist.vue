<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGXXnrUcxJ" x1="253.534%" x2="-6.886%" y1="253.575%" y2="-.904%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="p7h75kbpj"/></linearGradient><linearGradient id="SVGNTFQtcwB" x1="209.797%" x2="-1.083%" y1="223.263%" y2="-3.113%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="pifzxxbnj"/></linearGradient><linearGradient id="SVGXc348nhG" x1="271.964%" x2="7.716%" y1="334.363%" y2="-9.063%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="hv2dprbyh"/></linearGradient></defs><circle class="j1j-q9bzd"/><path fill="url(#SVGXXnrUcxJ)" class="cfyg2uoij"/><path fill="url(#SVGNTFQtcwB)" class="hi6npgbfz"/><path fill="url(#SVGXc348nhG)" class="mwotxybxc"/><path class="g9r3ilbqo"/><path class="wl9e_ubos"/><path class="pdel1g7vb"/><path class="v63auwc8l"/><path class="lp27vcche"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:mist" /></template>
<style>
.cfyg2uoij {
  d: path("M166.056 207.918c-74.05-6.013-37.626-10.137-144.322-32.129c29.38 22.68 77.144 78.862 144.322 32.129");
}

.g9r3ilbqo {
  fill: var(--svg-color--a4a4a4, #a4a4a4);
  d: path("M235.297 81.808C194.234 51.569 142.69-3.067 95.613 47.274C153 54.318 160.558 63.768 235.297 81.808");
}

.hi6npgbfz {
  d: path("M242.34 118.06c-70.27-13.917-139.167-61.852-211.5-46.389c-1.03.344-2.233.515-1.718 1.03c46.218 8.076 143.12 77.316 213.219 45.36");
}

.hv2dprbyh {
  stop-color: var(--svg-color--b3b3b3, #b3b3b3);
}

.j1j-q9bzd {
  cx: 128px;
  cy: 128px;
  r: 128px;
  fill: var(--svg-color--e9e9e9, #e9e9e9);
}

.lp27vcche {
  fill: var(--svg-color--010101, #010101);
  d: path("M84.102 219.945c51.028-.172 93.81-45.015 140.027-36.253c-37.799 21.649-83.844 66.32-140.027 36.253");
}

.mwotxybxc {
  d: path("M223.098 183.692c-36.94-7.903-117.863-69.583-208.752-44.843c79.55 18.213 151.195 62.54 208.752 44.843");
}

.p7h75kbpj {
  stop-color: var(--svg-color--c2c1c1, #c2c1c1);
}

.pdel1g7vb {
  fill: var(--svg-color--171717, #171717);
  d: path("M235.125 81.808c-85.734-6.873-130.406 62.368-221.466 57.385C48.193 123.558 150.078 31.64 235.125 81.808");
}

.pifzxxbnj {
  stop-color: var(--svg-color--a2a2a1, #a2a2a1);
}

.v63auwc8l {
  fill: var(--svg-color--212121, #212121);
  d: path("M172.242 36.621c-49.139-1.718-99.136 41.922-143.463 36.253C60.736 53.459 120.01 4.492 172.242 36.62");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wl9e_ubos {
  fill: var(--svg-color--121212, #121212);
  d: path("M20.875 175.445c85.047.172 133.67-64.773 221.466-57.385c-70.1 35.909-155.834 103.775-221.466 57.385");
}

</style>
