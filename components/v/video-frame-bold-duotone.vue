<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlhsgv7mu"/><path class="crkxmswra"/><path class="y9mxc-j5y"/><path class="hze_7mdac"/><path class="kn5v83hml"/><path class="wskurvbix"/><path class="zma_p_bnf"/><path class="ohaeesjny"/><g class="xtpeb-edw"><path class="j1ig29b4m"/><path class="ayoh-_bxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-bold-duotone" /></template>
<style>
.ayoh-_bxl {
  d: path("M16.25 2.06874C15.0942 2 13.7004 2 12 2C10.2996 2 8.9058 2 7.75 2.06874V11.25H16.25V2.06874Z");
}

.crkxmswra {
  fill: currentColor;
  d: path("M2.0685 7.75004C2.01015 8.73121 2.00133 9.88386 2 11.25H6.24976V7.75004H2.0685Z");
}

.hze_7mdac {
  fill: currentColor;
  d: path("M2.2214 17.75C2.41566 18.9728 2.78019 19.8515 3.46423 20.5356C4.14826 21.2196 5.02703 21.5841 6.24976 21.7784V17.75H2.2214Z");
}

.j1ig29b4m {
  d: path("M7.75 21.9313C8.9058 22 10.2996 22 12 22C13.7004 22 15.0942 22 16.25 21.9313V12.75H7.75V21.9313Z");
}

.jlhsgv7mu {
  fill: currentColor;
  d: path("M6.24976 2.22168C5.02703 2.41594 4.14826 2.78047 3.46423 3.46451C2.78019 4.14854 2.41566 5.02731 2.2214 6.25004H6.24976V2.22168Z");
}

.kn5v83hml {
  fill: currentColor;
  d: path("M17.7498 21.7784C18.9725 21.5841 19.8513 21.2196 20.5353 20.5356C21.2193 19.8515 21.5839 18.9728 21.7781 17.75H17.7498V21.7784Z");
}

.ohaeesjny {
  fill: currentColor;
  d: path("M21.7781 6.25004C21.5839 5.02731 21.2193 4.14854 20.5353 3.46451C19.8513 2.78047 18.9725 2.41594 17.7498 2.22168V6.25004H21.7781Z");
}

.wskurvbix {
  fill: currentColor;
  d: path("M21.931 16.25C21.9894 15.2689 21.9982 14.1162 21.9995 12.75H17.7498V16.25H21.931Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y9mxc-j5y {
  fill: currentColor;
  d: path("M2 12.75C2.00133 14.1162 2.01015 15.2689 2.0685 16.25H6.24976V12.75H2Z");
}

.zma_p_bnf {
  fill: currentColor;
  d: path("M21.9995 11.25C21.9982 9.88386 21.9894 8.73121 21.931 7.75004H17.7498V11.25H21.9995Z");
}

</style>
