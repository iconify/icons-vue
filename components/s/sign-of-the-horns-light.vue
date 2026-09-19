<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ik5mEce)"><path fill="url(#iNMlPSc)" class="fx20ikysy"/><path fill="url(#i0cqHlU)" class="fx20ikysy"/><path fill="url(#iS2ug3b)" class="fx20ikysy"/><path fill="url(#iVTC4Gx)" class="fx20ikysy"/></g><g filter="url(#il7tokb)" class="t7qq93bwt"><path class="mw5256byx"/></g><g filter="url(#ix9xiud)"><path class="nah882brh"/></g><rect fill="url(#ifh5FtL)" class="rnw81cc0v"/><rect fill="url(#iBKvOfe)" class="rnw81cc0v"/><rect fill="url(#iFdOzZd)" class="k9xaoqqep"/><g filter="url(#iJfjfqH)"><rect fill="url(#irIPyCe)" class="o74wf0bdl"/><rect fill="url(#iIz1j6b)" class="o74wf0bdl"/></g><rect fill="url(#iPqi6ge)" class="o74wf0bdl"/><rect fill="url(#ivXxtac)" class="o74wf0bdl"/><rect fill="url(#iQLrOtc)" class="o74wf0bdl"/><g filter="url(#iUIUiHd)"><rect fill="url(#iT5zC1c)" class="ihvytccoe"/></g><rect fill="url(#iQuFMrk)" class="ihvytccoe"/><g filter="url(#i1FXF7d)"><path class="uqcd75xin"/></g><path fill="url(#ibzlxLc)" class="d_pkq3bkr"/><path fill="url(#i8pOX0b)" class="d_pkq3bkr"/><path fill="url(#ibzlxLc)" class="hkklrdbbe"/><path fill="url(#i8pOX0b)" class="hkklrdbbe"/><path fill="url(#iDa0xJb)" class="d_pkq3bkr"/><path fill="url(#iDa0xJb)" class="hkklrdbbe"/><g filter="url(#ivy3G2c)"><path stroke="url(#iTEGFSg)" class="fzv5-oq4u"/></g><path fill="url(#iT5BLOd)" class="pncxy9tbj"/><path fill="url(#i97vpPd)" class="pncxy9tbj"/><path fill="url(#iTS3pBk)" class="pncxy9tbj"/><path fill="url(#iWu44ue)" class="pncxy9tbj"/><g filter="url(#iYV9zhe)"><path stroke="url(#i8jC4fb)" class="ow0g1di2k"/></g><g filter="url(#ifttvCB)"><rect class="rfqk4rykl"/></g><g filter="url(#iEp2tDc)"><rect class="ny9qkoimi"/></g><defs><radialGradient id="i0cqHlU" cx="0" cy="0" r="1" gradientTransform="matrix(1.40994 -4.40607 5.09243 1.62958 21.174 16.563)" gradientUnits="userSpaceOnUse"><stop class="x737ewbjk"/><stop offset="1" class="vred56_vg"/></radialGradient><radialGradient id="iS2ug3b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26865 0 0 -4.94397 21.72 20.944)" gradientUnits="userSpaceOnUse"><stop class="g1gul2bhb"/><stop offset="1" class="lw3r6mbby"/></radialGradient><radialGradient id="iVTC4Gx" cx="0" cy="0" r="1" gradientTransform="matrix(-7.59133 6.41699 -6.71794 -7.94735 11.579 16)" gradientUnits="userSpaceOnUse"><stop class="d710g-wsf"/><stop offset="1" class="b9ek7cchb"/></radialGradient><radialGradient id="ifh5FtL" cx="0" cy="0" r="1" gradientTransform="matrix(-3.39062 3.59376 -2.77814 -2.6211 12.745 12.664)" gradientUnits="userSpaceOnUse"><stop class="kxqcu196q"/><stop offset="1" class="h769wz7hg"/></radialGradient><radialGradient id="iBKvOfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.85935 0 0 1.79633 10.211 7.683)" gradientUnits="userSpaceOnUse"><stop class="sknwj3o9v"/><stop offset="1" class="efokhbbkj"/></radialGradient><radialGradient id="iFdOzZd" cx="0" cy="0" r="1" gradientTransform="matrix(2.97373 0 0 2.63918 24.11 4.063)" gradientUnits="userSpaceOnUse"><stop class="l9oj6kntc"/><stop offset="1" class="t4pwfjbte"/></radialGradient><radialGradient id="iIz1j6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31357 .85703 -1.14666 -1.7575 16.283 9.946)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="qyh91unxm"/><stop offset="1" class="vsjej0bzx"/></radialGradient><radialGradient id="iPqi6ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.11578 6.51664 0 13.237 17.207)" gradientUnits="userSpaceOnUse"><stop class="n273pkerh"/><stop offset="1" class="pd3ue799u"/></radialGradient><radialGradient id="iQLrOtc" cx="0" cy="0" r="1" gradientTransform="rotate(160.412 8.808 7.726)scale(9.71985 13.8653)" gradientUnits="userSpaceOnUse"><stop offset=".889" class="x0_03k5tq"/><stop offset="1" class="bdz4vacbp"/></radialGradient><radialGradient id="ibzlxLc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.30916 5.18888 -15.9384 -7.0929 22.944 15.185)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="c3i7elbzy"/><stop offset="1" class="ucdwi7b0t"/></radialGradient><radialGradient id="iDa0xJb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.05883 0 0 -12.0286 20.946 16.795)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="xn4jh245c"/><stop offset="1" class="mwjg5o1vq"/></radialGradient><radialGradient id="i97vpPd" cx="0" cy="0" r="1" gradientTransform="matrix(22.82617 10.50104 -11.16142 24.26165 3.886 11.694)" gradientUnits="userSpaceOnUse"><stop offset=".946" class="i6m4rfbpm"/><stop offset="1" class="ia-ch9hoc"/></radialGradient><radialGradient id="iWu44ue" cx="0" cy="0" r="1" gradientTransform="rotate(100.422 4.614 12.8)scale(19.7254 14.941)" gradientUnits="userSpaceOnUse"><stop offset=".916" class="b9pf4ubst"/><stop offset="1" class="zfl5jnbrp"/></radialGradient><linearGradient id="iNMlPSc" x1="12.988" x2="16" y1="2.023" y2="29.977" gradientUnits="userSpaceOnUse"><stop class="x_tczgbgo"/><stop offset="1" class="pol1z3dyp"/></linearGradient><linearGradient id="irIPyCe" x1="11.844" x2="14.864" y1="11.551" y2="11.561" gradientUnits="userSpaceOnUse"><stop class="sr30qxboo"/><stop offset="1" class="x8b1wqnsh"/></linearGradient><linearGradient id="ivXxtac" x1="15.398" x2="15.028" y1="12.906" y2="12.906" gradientUnits="userSpaceOnUse"><stop class="h_54g4thh"/><stop offset="1" class="xltkdm73r"/></linearGradient><linearGradient id="iT5zC1c" x1="16.302" x2="20.739" y1="10.638" y2="10.638" gradientUnits="userSpaceOnUse"><stop class="p2nyy8bsn"/><stop offset="1" class="h1c3298fx"/></linearGradient><linearGradient id="iQuFMrk" x1="21.593" x2="17.527" y1="11.495" y2="11.495" gradientUnits="userSpaceOnUse"><stop class="d9jmjybry"/><stop offset="1" class="wseic249b"/></linearGradient><linearGradient id="i8pOX0b" x1="24.642" x2="21.636" y1="22.688" y2="20.179" gradientUnits="userSpaceOnUse"><stop offset=".249" class="l6jy8ydog"/><stop offset="1" class="ox6wrrbld"/></linearGradient><linearGradient id="iTEGFSg" x1="18.073" x2="25.419" y1="16.241" y2="18.953" gradientUnits="userSpaceOnUse"><stop class="y28tgx-in"/><stop offset="1" class="h0vjas8xq"/></linearGradient><linearGradient id="iT5BLOd" x1="26.12" x2="23.557" y1="16.723" y2="16.723" gradientUnits="userSpaceOnUse"><stop class="icd8fhbfu"/><stop offset="1" class="uh7nbdb2t"/></linearGradient><linearGradient id="iTS3pBk" x1="6.006" x2="6.834" y1="16.752" y2="16.752" gradientUnits="userSpaceOnUse"><stop class="mj53yxbln"/><stop offset="1" class="uu3v-ebtf"/></linearGradient><linearGradient id="i8jC4fb" x1="10.164" x2="10.164" y1="4.082" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></linearGradient><filter id="ik5mEce" width="20.413" height="28.703" x="6.169" y="1.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.592157 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2564"/></filter><filter id="il7tokb" width="14.875" height="9.703" x="11.52" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2564" stdDeviation="1"/></filter><filter id="ix9xiud" width="10.099" height="10.995" x="7.835" y="8.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2564" stdDeviation="1"/></filter><filter id="iJfjfqH" width="6.145" height="8.953" x="10.54" y="8.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.654902 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2564"/></filter><filter id="iUIUiHd" width="6.082" height="11.031" x="15.407" y="6.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.627451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2564"/></filter><filter id="i1FXF7d" width="5.5" height="19.063" x="20.777" y="1.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2564" stdDeviation="1"/></filter><filter id="ivy3G2c" width="11.654" height="8.746" x="15.623" y="13.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2564" stdDeviation=".85"/></filter><filter id="iYV9zhe" width="3" height="9.736" x="7.983" y="7.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2564" stdDeviation=".5"/></filter><filter id="ifttvCB" width="2.851" height="5.453" x="12.812" y="10.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2564" stdDeviation=".5"/></filter><filter id="iEp2tDc" width="4.738" height="7.958" x="16.726" y="7.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2564" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sign-of-the-horns-light" /></template>
<style>
.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b9ek7cchb {
  stop-color: var(--svg-color--d7a190, #D7A190);
  stop-opacity: 0;
}

.b9pf4ubst {
  stop-color: var(--svg-color--bd7f96, #BD7F96);
  stop-opacity: 0;
}

.bdz4vacbp {
  stop-color: var(--svg-color--e3a896, #E3A896);
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.c3i7elbzy {
  stop-color: var(--svg-color--ffdab8, #FFDAB8);
}

.d_pkq3bkr {
  d: path("M17.739 14.117a2.852 2.852 0 1 0 0 5.703h1.624a1 1 0 0 1 .743.441l2.471 3.652a1 1 0 0 0 1.745-.16l.937-2.142c.332-.759.543-1.586.38-2.398a6.346 6.346 0 0 0-6.213-5.096");
}

.d710g-wsf {
  stop-color: var(--svg-color--d7a190, #D7A190);
}

.d9jmjybry {
  stop-color: var(--svg-color--bisque, bisque);
}

.efokhbbkj {
  stop-color: var(--svg-color--ffdfc1, #FFDFC1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx20ikysy {
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a94 94 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.fzv5-oq4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.073 16.241h2.834a3 3 0 0 1 2.613 1.527l1.307 2.319");
}

.g1gul2bhb {
  stop-color: var(--svg-color--f8c2b5, #F8C2B5);
}

.h_54g4thh {
  stop-color: var(--svg-color--da9d79, #DA9D79);
}

.h0vjas8xq {
  stop-color: var(--svg-color--ffe1c6, #FFE1C6);
  stop-opacity: 0;
}

.h1c3298fx {
  stop-color: var(--svg-color--ffd4b5, #FFD4B5);
}

.h769wz7hg {
  stop-color: var(--svg-color--c8846e, #C8846E);
  stop-opacity: 0;
}

.hkklrdbbe {
  d: path("M17.739 14.117h1.68Z");
}

.i6m4rfbpm {
  stop-color: var(--svg-color--f6c4b2, #F6C4B2);
  stop-opacity: 0;
}

.ia-ch9hoc {
  stop-color: var(--svg-color--f6c4b2, #F6C4B2);
}

.icd8fhbfu {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
}

.ihvytccoe {
  width: 5.332px;
  height: 10.281px;
  x: 15.407px;
  y: 7.195px;
  rx: 2.666px;
}

.k9xaoqqep {
  width: 5.332px;
  height: 15.453px;
  x: 20.094px;
  y: 2.023px;
  rx: 2.666px;
}

.kxqcu196q {
  stop-color: var(--svg-color--c8846e, #C8846E);
}

.l6jy8ydog {
  stop-color: var(--svg-color--e3ada1, #E3ADA1);
}

.l9oj6kntc {
  stop-color: var(--svg-color--ffe4c7, #FFE4C7);
}

.lw3r6mbby {
  stop-color: var(--svg-color--f8c2b5, #F8C2B5);
  stop-opacity: 0;
}

.mj53yxbln {
  stop-color: var(--svg-color--efb39b, #EFB39B);
}

.mw5256byx {
  d: path("M16.372 15.252a2.852 2.852 0 1 0 0 5.703h1.624c3.034 0 4.127 0 6.399-.256c0-3.5-2.836-5.443-6.336-5.447m-1.687 0h1.68Z");
}

.mwjg5o1vq {
  stop-color: var(--svg-color--dca18f, #DCA18F);
}

.n273pkerh {
  stop-color: var(--svg-color--c48488, #C48488);
}

.nah882brh {
  fill: var(--svg-color--bb7b77, #BB7B77);
  d: path("M9.835 10.959h6.099v6.995H9.835z");
}

.ny9qkoimi {
  width: 1.738px;
  height: 4.959px;
  x: 18.226px;
  y: 8.574px;
  fill: var(--svg-color--ffe2c3, #FFE2C3);
  rx: 0.869px;
}

.o74wf0bdl {
  width: 5.395px;
  height: 8.203px;
  x: 10.54px;
  y: 8.805px;
  rx: 2.697px;
}

.ow0g1di2k {
  stroke-linecap: round;
  d: path("M9.483 8.574v6.737");
}

.ox6wrrbld {
  stop-color: var(--svg-color--e3ada1, #E3ADA1);
  stop-opacity: 0;
}

.p2nyy8bsn {
  stop-color: var(--svg-color--dfab8f, #DFAB8F);
}

.pd3ue799u {
  stop-color: var(--svg-color--c48488, #C48488);
  stop-opacity: 0;
}

.pncxy9tbj {
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v3.434c.402.467.645 1.074.645 1.738v4.95a2.666 2.666 0 0 1-5.184.879a2.697 2.697 0 0 1-5.016-1.38v-2.808c0-.828.374-1.57.962-2.064V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a94 94 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.pol1z3dyp {
  stop-color: var(--svg-color--e2ada0, #E2ADA0);
}

.qyh91unxm {
  stop-color: var(--svg-color--c08767, #C08767);
}

.rfqk4rykl {
  width: 0.851px;
  height: 3.453px;
  x: 13.812px;
  y: 11.395px;
  fill: var(--svg-color--ffd4bd, #FFD4BD);
  rx: 0.426px;
}

.rnw81cc0v {
  width: 5.332px;
  height: 11.813px;
  x: 6.169px;
  y: 5.664px;
  rx: 2.666px;
}

.sknwj3o9v {
  stop-color: var(--svg-color--ffdfc1, #FFDFC1);
}

.sr30qxboo {
  stop-color: var(--svg-color--e0ad90, #E0AD90);
}

.t4pwfjbte {
  stop-color: var(--svg-color--ffe4c7, #FFE4C7);
  stop-opacity: 0;
}

.t7qq93bwt {
  fill: var(--svg-color--bb7b77, #BB7B77);
}

.ucdwi7b0t {
  stop-color: var(--svg-color--c2838a, #C2838A);
}

.uh7nbdb2t {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
  stop-opacity: 0;
}

.uqcd75xin {
  stroke: var(--svg-color--ffe3c6, #FFE3C6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M23.527 4.602v13.562");
}

.uu3v-ebtf {
  stop-color: var(--svg-color--efb39b, #EFB39B);
  stop-opacity: 0;
}

.vred56_vg {
  stop-color: var(--svg-color--ffe3c3, #FFE3C3);
  stop-opacity: 0;
}

.vsjej0bzx {
  stop-color: var(--svg-color--c08767, #C08767);
  stop-opacity: 0;
}

.wseic249b {
  stop-color: var(--svg-color--bisque, bisque);
  stop-opacity: 0;
}

.x_tczgbgo {
  stop-color: var(--svg-color--f8c5aa, #F8C5AA);
}

.x0_03k5tq {
  stop-color: var(--svg-color--e3a896, #E3A896);
  stop-opacity: 0;
}

.x737ewbjk {
  stop-color: var(--svg-color--ffe3c3, #FFE3C3);
}

.x8b1wqnsh {
  stop-color: var(--svg-color--f6c6ab, #F6C6AB);
}

.xltkdm73r {
  stop-color: var(--svg-color--da9d79, #DA9D79);
  stop-opacity: 0;
}

.xn4jh245c {
  stop-color: var(--svg-color--dca18f, #DCA18F);
  stop-opacity: 0;
}

.y28tgx-in {
  stop-color: var(--svg-color--ffe1c6, #FFE1C6);
}

.zfl5jnbrp {
  stop-color: var(--svg-color--bd7f96, #BD7F96);
}

</style>
