<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#is8A71c)"><path fill="url(#i1Ziqji)" class="w4at-nmde"/></g><g filter="url(#ia1RUIb)"><path class="r-qj0zbll"/></g><g filter="url(#iKkFNqb)"><path fill="url(#iPcgFgb)" class="ehw9s33wb"/><path fill="url(#ibJGXEd)" class="ehw9s33wb"/></g><g filter="url(#iIiXJBc)"><path fill="url(#i3oD9ed)" class="s93ihqupv"/></g><g filter="url(#iImsIOe)"><path fill="url(#irJlEdt)" class="ccve35bwx"/><path fill="url(#i2vD1ou)" class="ccve35bwx"/><path fill="url(#ikNU1Zc)" class="ccve35bwx"/><path fill="url(#ixK7ylc)" class="ccve35bwx"/><path fill="url(#i1174fd)" class="ccve35bwx"/><path fill="url(#iwcOpEd)" class="ccve35bwx"/></g><path fill="url(#itPDonZ)" class="ccve35bwx"/><path fill="url(#ifkLKkI)" class="ccve35bwx"/><g filter="url(#i5LxQzc)"><path class="qej4nqb-w"/></g><g filter="url(#iPdTqiH)"><path class="u-i_plbnv"/><path fill="url(#ikV01jb)" class="es7hf-lqk"/><path fill="url(#iHf6jed)" class="es7hf-lqk"/><path fill="url(#isRbSXb)" class="es7hf-lqk"/><path fill="url(#iSzFL3c)" class="es7hf-lqk"/></g><g filter="url(#i3PUhEd)"><path stroke="url(#i8aYgWy)" class="e59fxp8pd"/></g><path class="fi_mguelk"/><g filter="url(#i2nROFi)"><path class="na308hdee"/></g><g filter="url(#imuGtRV)"><path class="b70y7cbhs"/></g><path class="gshv_3b1z"/><path fill="url(#i9kSRjb)" class="a6vpq7btd"/><path class="txtilz4qi"/><g filter="url(#iZ49yTc)"><path fill="url(#iyePzRb)" class="os_3e5bbe"/></g><g filter="url(#iUOGNQd)"><ellipse transform="rotate(-27.914 11.424 16.625)" class="c11nbobko"/><ellipse fill="url(#iEafxoe)" transform="rotate(-27.914 11.424 16.625)" class="gm7kgk-gj"/></g><path class="ny0mkhbjo"/><path fill="url(#iaXfdDD)" class="u061qd38p"/><path class="uirztmbng"/><g filter="url(#ityx1Jb)"><path class="hcrsaurqs"/><path fill="url(#iMpq7ZC)" class="w2e71zbmc"/></g><g filter="url(#iyaG1kc)"><path fill="url(#iwIAFSb)" class="mv2_wkbfd"/></g><g filter="url(#iZ4Hobd)"><path class="mtg26p_dv"/></g><g filter="url(#izLRtgU)"><path class="ge-cfvbhz"/></g><defs><filter id="is8A71c" width="6" height="6.2" x="4" y="14.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.47451 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2072"/></filter><filter id="ia1RUIb" width="4.132" height="4.132" x="4.934" y="15.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".125"/></filter><filter id="iKkFNqb" width="6.2" height="6.2" x="22" y="14.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.568627 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2072"/></filter><filter id="iIiXJBc" width="4.632" height="4.632" x="22.887" y="15.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".25"/></filter><filter id="iImsIOe" width="20.485" height="26.25" x="6.262" y="4.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.619608 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2072"/></filter><filter id="i5LxQzc" width="4.5" height="5.836" x="13.512" y="16.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".25"/></filter><filter id="iPdTqiH" width="3.7" height="5.2" x="14.15" y="16.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".05"/></filter><filter id="i3PUhEd" width="6.719" height="2.64" x="12.641" y="22.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".075"/></filter><filter id="i2nROFi" width="4.424" height="2.097" x="18.963" y="11.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.235294 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2072"/></filter><filter id="imuGtRV" width="4.424" height="2.069" x="9.163" y="11.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.235294 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2072"/></filter><filter id="iZ49yTc" width="1.512" height="1.614" x="12.169" y="16.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".1"/></filter><filter id="iUOGNQd" width="1.552" height="1.157" x="10.648" y="16.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".05"/></filter><filter id="ityx1Jb" width="1.294" height="1.125" x="18.786" y="16.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".05"/></filter><filter id="iyaG1kc" width="1.316" height="1.357" x="20.438" y="16.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".1"/></filter><filter id="iZ4Hobd" width="3.77" height="1.518" x="9.365" y="12.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".125"/></filter><filter id="izLRtgU" width="3.77" height="1.537" x="19.211" y="12.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2072" stdDeviation=".125"/></filter><radialGradient id="i1Ziqji" cx="0" cy="0" r="1" gradientTransform="matrix(3.15625 0 0 5.09375 3.59 18.232)" gradientUnits="userSpaceOnUse"><stop class="i3uk3tynl"/><stop offset="1" class="vg_9_b7fg"/></radialGradient><radialGradient id="ibJGXEd" cx="0" cy="0" r="1" gradientTransform="rotate(-50.244 31.317 -18.074)scale(2.29666 2.22246)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="xdicuaccu"/><stop offset="1" class="ffe_f4sac"/></radialGradient><radialGradient id="irJlEdt" cx="0" cy="0" r="1" gradientTransform="matrix(-5.13152 18.00003 -16.21274 -4.622 20.605 10.145)" gradientUnits="userSpaceOnUse"><stop class="xd40nlb3w"/><stop offset="1" class="ktbtxoblq"/></radialGradient><radialGradient id="i2vD1ou" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.17105 -8.57064 0 22.026 19.303)" gradientUnits="userSpaceOnUse"><stop class="e75m1hn2r"/><stop offset="1" class="ne5gs0bou"/></radialGradient><radialGradient id="ikNU1Zc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 -8.75 7.37907 -.6852 9.56 28.013)" gradientUnits="userSpaceOnUse"><stop class="glxz1zb2b"/><stop offset="1" class="u-z3ug7bf"/></radialGradient><radialGradient id="ixK7ylc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05461 19.43755 -18.9858 -2.98362 19.059 10.762)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="g0s_ijbld"/><stop offset=".985" class="d9amjacrm"/></radialGradient><radialGradient id="i1174fd" cx="0" cy="0" r="1" gradientTransform="matrix(.56248 -3.4375 3.84375 .62896 11.966 15.951)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="ak2f56b_u"/><stop offset="1" class="kx4j32bkm"/></radialGradient><radialGradient id="iwcOpEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.28125 3.61306 0 20.434 15.888)" gradientUnits="userSpaceOnUse"><stop class="gwvh7z1xy"/><stop offset="1" class="ggi3xh-2a"/></radialGradient><radialGradient id="itPDonZ" cx="0" cy="0" r="1" gradientTransform="rotate(138.468 11.212 8.226)scale(5.84434 7.70645)" gradientUnits="userSpaceOnUse"><stop class="u7id6gble"/><stop offset="1" class="ydn9dmb6d"/></radialGradient><radialGradient id="ifkLKkI" cx="0" cy="0" r="1" gradientTransform="rotate(122.282 8.558 11.25)scale(22.8315 17.1751)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="qzxblgbul"/><stop offset="1" class="zn3wyl27v"/></radialGradient><radialGradient id="iHf6jed" cx="0" cy="0" r="1" gradientTransform="matrix(-.87499 -4.34375 1.5682 -.31589 17.34 20.7)" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></radialGradient><radialGradient id="i9kSRjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53876 -2.44757 0 11.938 16.806)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iEafxoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.01467 -.93704 1.12636 -.01764 11.395 17.222)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaXfdDD" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.068 16.8)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iMpq7ZC" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.974 3.668)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iPcgFgb" x1="27.09" x2="25" y1="15.544" y2="20.607" gradientUnits="userSpaceOnUse"><stop class="lq923bbnc"/><stop offset="1" class="h9hgczbri"/></linearGradient><linearGradient id="i3oD9ed" x1="26.497" x2="25.203" y1="16.638" y2="19.829" gradientUnits="userSpaceOnUse"><stop class="fm06gfyta"/><stop offset="1" class="xykughmpx"/></linearGradient><linearGradient id="ikV01jb" x1="13.809" x2="15.591" y1="20.576" y2="20.888" gradientUnits="userSpaceOnUse"><stop class="dwloy0ztq"/><stop offset="1" class="plpgejhue"/></linearGradient><linearGradient id="isRbSXb" x1="16" x2="16" y1="22.201" y2="20.732" gradientUnits="userSpaceOnUse"><stop class="bdc0qbr7e"/><stop offset="1" class="kwrw6415v"/></linearGradient><linearGradient id="iSzFL3c" x1="16" x2="16" y1="16.669" y2="18.263" gradientUnits="userSpaceOnUse"><stop class="p9_y12brr"/><stop offset="1" class="vjmdqeb6f"/></linearGradient><linearGradient id="i8aYgWy" x1="14.762" x2="15.294" y1="25.283" y2="23.935" gradientUnits="userSpaceOnUse"><stop class="t0col0s6f"/><stop offset="1" class="oso-z4buh"/></linearGradient><linearGradient id="iyePzRb" x1="13.349" x2="12.754" y1="16.908" y2="17.275" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwIAFSb" x1="21.519" x2="20.934" y1="16.9" y2="17.261" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bald" /></template>
<style>
.a6vpq7btd {
  d: path("M11.934 15.901a1.693 1.693 0 0 0-1.63 2.14h3.27c.038-.147.06-.293.06-.447a1.704 1.704 0 0 0-1.7-1.693");
}

.ak2f56b_u {
  stop-color: var(--svg-color--ee952f, #EE952F);
}

.b70y7cbhs {
  fill: var(--svg-color--be424b, #BE424B);
  d: path("M9.64 12.75a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.026a4.14 4.14 0 0 0-2.585.53l-.14.09l-.031.022l-.005.004a.517.517 0 0 1-.633-.818z");
}

.bdc0qbr7e {
  stop-color: var(--svg-color--f09338, #F09338);
}

.c11nbobko {
  cx: 11.424px;
  cy: 16.625px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.739px;
  ry: 0.374px;
}

.ccve35bwx {
  d: path("M18.066 4.125h-4.147c-5.57 0-8.018 3.75-7.614 8.71l.7 10.69a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35l.67-10.69c.53-4.703-2.115-8.71-7.615-8.71");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d9amjacrm {
  stop-color: var(--svg-color--d67971, #D67971);
}

.dwloy0ztq {
  stop-color: var(--svg-color--ec9a24, #EC9A24);
}

.e59fxp8pd {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.4 23.21a.366.366 0 0 0-.436.076a.335.335 0 0 0-.036.43A3.68 3.68 0 0 0 16 25.359c1.29 0 2.422-.657 3.073-1.642a.34.34 0 0 0-.038-.434a.37.37 0 0 0-.435-.072a5.6 5.6 0 0 1-2.6.617a5.64 5.64 0 0 1-2.6-.616Z");
}

.e75m1hn2r {
  stop-color: var(--svg-color--ffe840, #FFE840);
}

.ehw9s33wb {
  d: path("M25 21.013a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.es7hf-lqk {
  d: path("m15.287 17.54l-.99 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-1.203-.701-1.426 0");
}

.ffe_f4sac {
  stop-color: var(--svg-color--ec9512, #EC9512);
  stop-opacity: 0;
}

.fgz6lbb_q {
  stop-color: var(--svg-color--ffe948, #FFE948);
}

.fi_mguelk {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16 23.902a5.7 5.7 0 0 1-2.634-.625c-.26-.132-.54.161-.376.397A3.6 3.6 0 0 0 16 25.283a3.6 3.6 0 0 0 3.01-1.609c.164-.245-.116-.53-.376-.397a5.7 5.7 0 0 1-2.634.625");
}

.fm06gfyta {
  stop-color: var(--svg-color--ffc633, #FFC633);
}

.ft5dv1b6b {
  fill: none;
}

.g0s_ijbld {
  stop-color: var(--svg-color--d67971, #D67971);
  stop-opacity: 0;
}

.ge-cfvbhz {
  stroke: var(--svg-color--d26957, #D26957);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.606 13.283c-.5-.484-1.695-.918-3.02-.75");
}

.ggi3xh-2a {
  stop-color: var(--svg-color--ffbb37, #FFBB37);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glxz1zb2b {
  stop-color: var(--svg-color--e99530, #E99530);
}

.gm7kgk-gj {
  cx: 11.424px;
  cy: 16.625px;
  rx: 0.739px;
  ry: 0.374px;
}

.gshv_3b1z {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.542 15.386a2.65 2.65 0 0 0-2.57 2.008a.52.52 0 0 0 .508.646h4.232a.436.436 0 0 0 .43-.515a2.66 2.66 0 0 0-2.6-2.14");
}

.gwvh7z1xy {
  stop-color: var(--svg-color--ffbb37, #FFBB37);
}

.h9hgczbri {
  stop-color: var(--svg-color--ffc335, #FFC335);
}

.hcrsaurqs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.95 16.262c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.i3uk3tynl {
  stop-color: var(--svg-color--e49827, #E49827);
}

.ktbtxoblq {
  stop-color: var(--svg-color--f8a12d, #F8A12D);
}

.kwrw6415v {
  stop-color: var(--svg-color--f09338, #F09338);
  stop-opacity: 0;
}

.kx4j32bkm {
  stop-color: var(--svg-color--ee952f, #EE952F);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lq923bbnc {
  stop-color: var(--svg-color--ffe547, #FFE547);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mtg26p_dv {
  stroke: var(--svg-color--d26957, #D26957);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.74 13.283c.408-.303 1.583-.876 3.02-.75");
}

.mv2_wkbfd {
  d: path("M21.554 17.355a1.57 1.57 0 0 0-.431-.862l-.485.532l.219.425z");
}

.na308hdee {
  fill: var(--svg-color--be424b, #BE424B);
  d: path("M22.96 12.953c-.327-.285-.707-.586-1.282-.767c-.567-.179-1.278-.227-2.26-.107a.517.517 0 0 0 .125 1.027c.897-.11 1.446-.053 1.824.066c.37.117.62.305.913.56a.517.517 0 1 0 .68-.78");
}

.ne5gs0bou {
  stop-color: var(--svg-color--ffe840, #FFE840);
  stop-opacity: 0;
}

.ny0mkhbjo {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.458 15.404c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.159a.43.43 0 0 1-.424-.507a2.606 2.606 0 0 1 2.557-2.102");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.os_3e5bbe {
  d: path("M13.48 17.395c0-.547-.444-.911-.564-1.022l-.547.53l.336.685z");
}

.oso-z4buh {
  stop-color: var(--svg-color--ffb537, #FFB537);
  stop-opacity: 0;
}

.p9_y12brr {
  stop-color: var(--svg-color--fed33e, #FED33E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plpgejhue {
  stop-color: var(--svg-color--ec9a24, #EC9A24);
  stop-opacity: 0;
}

.qej4nqb-w {
  fill: var(--svg-color--f0912a, #F0912A);
  d: path("m15.262 17.977l-1.204 3.005a1.005 1.005 0 0 0 .97 1.304h1.467c.687 0 1.173-.662.97-1.304l-1.125-3.005c-.213-.703-.855-.703-1.078 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzxblgbul {
  stop-color: var(--svg-color--d87b7a, #D87B7A);
  stop-opacity: 0;
}

.r-qj0zbll {
  fill: var(--svg-color--e08726, #E08726);
  d: path("M7 19.829a1.816 1.816 0 1 0 0-3.632a1.816 1.816 0 0 0 0 3.632");
}

.s93ihqupv {
  d: path("M25.203 19.829a1.816 1.816 0 1 0 0-3.632a1.816 1.816 0 0 0 0 3.632");
}

.t0col0s6f {
  stop-color: var(--svg-color--ffb537, #FFB537);
}

.txtilz4qi {
  fill: var(--svg-color--000, #000);
  d: path("M12.904 17.594c0-.539-.431-.97-.97-.97s-.969.431-.969.97c0 .162.039.316.108.446h1.715a.96.96 0 0 0 .116-.446");
}

.u-i_plbnv {
  fill: var(--svg-color--ffce33, #FFCE33);
  d: path("m15.287 17.54l-.99 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-1.203-.701-1.426 0");
}

.u-z3ug7bf {
  stop-color: var(--svg-color--e99530, #E99530);
  stop-opacity: 0;
}

.u061qd38p {
  d: path("M20.072 15.91a1.664 1.664 0 0 1 1.604 2.103H18.46a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.u7id6gble {
  stop-color: var(--svg-color--ffe945, #FFE945);
}

.uirztmbng {
  fill: var(--svg-color--000, #000);
  d: path("M19.12 17.575c0-.53.423-.953.952-.953c.53 0 .953.423.953.953c0 .158-.038.31-.106.438h-1.686a.86.86 0 0 1-.114-.439");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vg_9_b7fg {
  stop-color: var(--svg-color--d98c20, #D98C20);
}

.vjmdqeb6f {
  stop-color: var(--svg-color--fed33e, #FED33E);
  stop-opacity: 0;
}

.w2e71zbmc {
  d: path("M19.95 16.262c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.w4at-nmde {
  d: path("M7 21.013a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.x9idaudaq {
  stop-color: var(--svg-color--ffe948, #FFE948);
  stop-opacity: 0;
}

.xd40nlb3w {
  stop-color: var(--svg-color--ffec49, #FFEC49);
}

.xdicuaccu {
  stop-color: var(--svg-color--ec9512, #EC9512);
}

.xykughmpx {
  stop-color: var(--svg-color--ffc832, #FFC832);
}

.ydn9dmb6d {
  stop-color: var(--svg-color--ffe945, #FFE945);
  stop-opacity: 0;
}

.zn3wyl27v {
  stop-color: var(--svg-color--d87b7a, #D87B7A);
}

</style>
