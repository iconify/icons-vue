<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i5fk6Kb)" class="vi_4d-bfd"/><path fill="url(#i0lbOtd)" class="vi_4d-bfd"/><path fill="url(#iMa81PW)" class="vi_4d-bfd"/><path fill="url(#iCA61wd)" class="vi_4d-bfd"/><path fill="url(#icj1Hkd)" class="vi_4d-bfd"/><defs><radialGradient id="i5fk6Kb" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 9.936 9.935)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="g7hbbolkd"/><stop offset="1" class="uv396o51u"/></radialGradient><radialGradient id="iMa81PW" cx="0" cy="0" r="1" gradientTransform="rotate(136.38 10.067 10.264)scale(14.6767 15.816)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="iur0wl0vl"/><stop offset="1" class="vv7exubhs"/></radialGradient><radialGradient id="iCA61wd" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.249 16)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="or-mjwrof"/><stop offset=".951" class="m-r16ybxv"/></radialGradient><radialGradient id="icj1Hkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 21 -23.3208 0 15.757 9)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="rzq18p6pr"/><stop offset="1" class="j73k17bgg"/></radialGradient><linearGradient id="i0lbOtd" x1="15.757" x2="15.757" y1="2" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="ztbux8bpx"/><stop offset="1" class="g7o0d0bbp"/><stop offset="1" class="irdrfnf8i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:orange-circle" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g7hbbolkd {
  stop-color: var(--svg-color--ff8c46, #FF8C46);
}

.g7o0d0bbp {
  stop-color: var(--svg-color--ef4b5e, #EF4B5E);
  stop-opacity: 0;
}

.irdrfnf8i {
  stop-color: var(--svg-color--ff7e51, #FF7E51);
  stop-opacity: 0;
}

.iur0wl0vl {
  stop-color: var(--svg-color--ffa35f, #FFA35F);
}

.j73k17bgg {
  stop-color: var(--svg-color--ec5b84, #EC5B84);
}

.m-r16ybxv {
  stop-color: var(--svg-color--ffa693, #FFA693);
}

.or-mjwrof {
  stop-color: var(--svg-color--e77049, #E77049);
  stop-opacity: 0;
}

.rzq18p6pr {
  stop-color: var(--svg-color--ee4c57, #EE4C57);
  stop-opacity: 0;
}

.uv396o51u {
  stop-color: var(--svg-color--ee534a, #EE534A);
}

.vi_4d-bfd {
  d: path("M29.757 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.vv7exubhs {
  stop-color: var(--svg-color--ff8544, #FF8544);
  stop-opacity: 0;
}

.ztbux8bpx {
  stop-color: var(--svg-color--ff7e51, #FF7E51);
}

</style>
