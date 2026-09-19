<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibpcnEb)"><path class="b86dahbou"/><path fill="url(#izp9Ujd)" class="y1sj7ubrw"/></g><g filter="url(#ibg81Nb)"><path class="d64vuzb5y"/></g><g filter="url(#iUNnDJc)"><path class="v792z-4ox"/></g><rect transform="rotate(-8.494 4.508 12.006)" class="mwbrjjrvz"/><rect fill="url(#iK3DIRb)" transform="rotate(-8.494 4.508 12.006)" class="tqux4qpga"/><rect fill="url(#iYWlLIx)" transform="rotate(-8.494 4.508 12.006)" class="tqux4qpga"/><rect fill="url(#iS4gqnc)" transform="rotate(-8.494 4.508 12.006)" class="tqux4qpga"/><rect fill="url(#iWvIh5b)" transform="rotate(-8.494 4.508 12.006)" class="tqux4qpga"/><path fill="url(#i1YXN8z)" class="ib_dhmb-l"/><path fill="url(#ifWxg0c)" class="ib_dhmb-l"/><path fill="url(#iuX3GBc)" class="ib_dhmb-l"/><path fill="url(#iIfh6zb)" class="ib_dhmb-l"/><path fill="url(#iaZznxd)" class="ib_dhmb-l"/><path fill="url(#iJa0Vbb)" class="a_f3fh8ja"/><path fill="url(#ic5uNve)" class="a_f3fh8ja"/><path fill="url(#iynJj6e)" class="a_f3fh8ja"/><path fill="url(#i5pot8T)" class="y1sj7ubrw"/><g filter="url(#izYoLFc)"><rect transform="rotate(-8.139 8.277 12.536)" class="gxf44y0xl"/></g><rect transform="rotate(-8.494 8.367 10.437)" class="rpyo5pbzk"/><rect fill="url(#iWmxeod)" transform="rotate(-8.494 8.367 10.437)" class="f2glsth4z"/><rect fill="url(#iEc9L5D)" transform="rotate(-8.494 8.367 10.437)" class="f2glsth4z"/><rect fill="url(#iw4GOJe)" transform="rotate(-8.494 8.367 10.437)" class="f2glsth4z"/><rect fill="url(#ix8U5gb)" transform="rotate(-8.494 8.367 10.437)" class="f2glsth4z"/><g filter="url(#i6HnDGb)" class="mc2zb0bvp"><rect fill="url(#iyhoOJc)" transform="rotate(-8.33 7.508 13.432)" class="awki8cbqd"/></g><g filter="url(#ivataMb)" class="mc2zb0bvp"><rect fill="url(#iZoLhrd)" transform="rotate(-8.33 10.947 11.114)" class="aefwyj94t"/></g><g filter="url(#ii0196G)"><path class="wpcv8-bgo"/></g><g filter="url(#iA7rWvb)"><path class="nm-nwzbjj"/></g><path class="u74bk4b9n"/><path fill="url(#iD8mp0b)" class="t75p2db6y"/><path fill="url(#iHx2tdb)" class="t75p2db6y"/><path fill="url(#iw2Ulwd)" class="t75p2db6y"/><g filter="url(#ije9eBe)"><path stroke="url(#iloGmQb)" class="g94328b_p"/></g><path fill="url(#i9UhzMb)" clip-rule="evenodd" class="idh-vc29e"/><path fill="url(#iB7f3vd)" clip-rule="evenodd" class="idh-vc29e"/><path fill="url(#iYbLIud)" clip-rule="evenodd" class="idh-vc29e"/><defs><radialGradient id="izp9Ujd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.82482 3.27838 -2.93875 -3.42858 20.002 20.252)" gradientUnits="userSpaceOnUse"><stop class="nbb38-bgo"/><stop offset="1" class="a0k-rnbnj"/></radialGradient><radialGradient id="iS4gqnc" cx="0" cy="0" r="1" gradientTransform="matrix(.4219 -2.82514 3.82124 .57066 6.535 19.498)" gradientUnits="userSpaceOnUse"><stop class="clbpnubbb"/><stop offset="1" class="oglfs1byf"/></radialGradient><radialGradient id="iWvIh5b" cx="0" cy="0" r="1" gradientTransform="rotate(112.53 .547 8.804)scale(3.35002 3.96464)" gradientUnits="userSpaceOnUse"><stop class="q0c72xbor"/><stop offset="1" class="wtm1ced1u"/></radialGradient><radialGradient id="iaZznxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 2.76387 -3.1065 -.281 14.944 2.205)" gradientUnits="userSpaceOnUse"><stop class="esjqqiyof"/><stop offset="1" class="zlb7k-x-q"/></radialGradient><radialGradient id="iynJj6e" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4311 3.6085 -3.13139 -1.24189 23.05 3.218)" gradientUnits="userSpaceOnUse"><stop class="esjqqiyof"/><stop offset="1" class="zlb7k-x-q"/></radialGradient><radialGradient id="i5pot8T" cx="0" cy="0" r="1" gradientTransform="rotate(-167.551 12.818 6.96)scale(11.1157 8.78497)" gradientUnits="userSpaceOnUse"><stop class="vyi22ldxx"/><stop offset="1" class="ekhlrrbxz"/></radialGradient><radialGradient id="iw4GOJe" cx="0" cy="0" r="1" gradientTransform="matrix(.4323 -3.3024 3.93523 .51513 10.444 19.195)" gradientUnits="userSpaceOnUse"><stop class="clbpnubbb"/><stop offset="1" class="oglfs1byf"/></radialGradient><radialGradient id="ix8U5gb" cx="0" cy="0" r="1" gradientTransform="matrix(1.40377 2.86343 -3.075 1.5075 9.923 9.877)" gradientUnits="userSpaceOnUse"><stop class="q0c72xbor"/><stop offset="1" class="wtm1ced1u"/></radialGradient><radialGradient id="iD8mp0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.20125 -9.81935 13.13623 4.2826 18.23 24.58)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="pwvlzbc-w"/><stop offset="1" class="ggwu9gzpf"/></radialGradient><radialGradient id="iHx2tdb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0638 1.7944 -2.84171 4.85204 14.664 15)" gradientUnits="userSpaceOnUse"><stop class="im4yj9h_p"/><stop offset="1" class="ys7ct9ewc"/></radialGradient><radialGradient id="iw2Ulwd" cx="0" cy="0" r="1" gradientTransform="rotate(96.583 .384 18.863)scale(2.99005 6.10541)" gradientUnits="userSpaceOnUse"><stop class="r9f-6_ftc"/><stop offset="1" class="a590uwbio"/></radialGradient><radialGradient id="i9UhzMb" cx="0" cy="0" r="1" gradientTransform="rotate(11.85 -91.42 66.3)scale(14.3049 25.7029)" gradientUnits="userSpaceOnUse"><stop offset=".865" class="dydcj5d2k"/><stop offset="1" class="ra6zuebyu"/></radialGradient><radialGradient id="iB7f3vd" cx="0" cy="0" r="1" gradientTransform="rotate(39.598 -16.757 21.904)scale(16.5663 20.5917)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="x4dfu9bqm"/><stop offset="1" class="jyzlcxbbj"/></radialGradient><radialGradient id="iYbLIud" cx="0" cy="0" r="1" gradientTransform="matrix(-13.45914 4.22765 -5.63551 -17.94123 19.905 18.15)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="ll8qulb7z"/><stop offset="1" class="aomvlhbbn"/></radialGradient><linearGradient id="iK3DIRb" x1="4.769" x2="6.627" y1="16.431" y2="16.388" gradientUnits="userSpaceOnUse"><stop class="zbmk2_bod"/><stop offset="1" class="wdfolpbqp"/></linearGradient><linearGradient id="iYWlLIx" x1="4.62" x2="5.314" y1="16.419" y2="16.39" gradientUnits="userSpaceOnUse"><stop class="n020c5bwi"/><stop offset="1" class="zs8stybtp"/></linearGradient><linearGradient id="i1YXN8z" x1="12.557" x2="15.518" y1="8.675" y2="7.934" gradientUnits="userSpaceOnUse"><stop class="kpzra2bsh"/><stop offset="1" class="oad41r0vf"/></linearGradient><linearGradient id="ifWxg0c" x1="12.124" x2="13.141" y1="8.686" y2="8.538" gradientUnits="userSpaceOnUse"><stop class="bllir2bya"/><stop offset="1" class="mm-v1nbql"/></linearGradient><linearGradient id="iuX3GBc" x1="18.444" x2="17.206" y1="9.75" y2="10.087" gradientUnits="userSpaceOnUse"><stop class="u7_fp84-r"/><stop offset="1" class="iuc0-d97m"/></linearGradient><linearGradient id="iIfh6zb" x1="16.166" x2="15.651" y1="15.217" y2="11.28" gradientUnits="userSpaceOnUse"><stop offset=".307" class="hnvwo41ut"/><stop offset="1" class="iugp1lw5d"/></linearGradient><linearGradient id="iJa0Vbb" x1="17.675" x2="20.804" y1="7.92" y2="8.092" gradientUnits="userSpaceOnUse"><stop class="iyk5xpb6y"/><stop offset="1" class="btyea4buz"/></linearGradient><linearGradient id="ic5uNve" x1="20.867" x2="20.965" y1="12.604" y2="11.109" gradientUnits="userSpaceOnUse"><stop class="mj4pu2bgz"/><stop offset="1" class="cm_hntbvk"/></linearGradient><linearGradient id="iWmxeod" x1="8.634" x2="10.538" y1="15.61" y2="15.572" gradientUnits="userSpaceOnUse"><stop class="gg-3_1lxr"/><stop offset="1" class="o1y2prbvy"/></linearGradient><linearGradient id="iEc9L5D" x1="14.377" x2="11.34" y1="15.788" y2="15.674" gradientUnits="userSpaceOnUse"><stop class="d2_rir6tr"/><stop offset="1" class="szt2fobcj"/></linearGradient><linearGradient id="iyhoOJc" x1="8.222" x2="8.246" y1="16.413" y2="12.579" gradientUnits="userSpaceOnUse"><stop class="onxszmfdr"/><stop offset="1" class="g3im_y09y"/></linearGradient><linearGradient id="iZoLhrd" x1="12.539" x2="12.461" y1="15.25" y2="8.411" gradientUnits="userSpaceOnUse"><stop class="pnzigcbnm"/><stop offset="1" class="v9nre5tkm"/></linearGradient><linearGradient id="iloGmQb" x1="18.711" x2="24.177" y1="17.16" y2="20.134" gradientUnits="userSpaceOnUse"><stop class="o3hi5-pfv"/><stop offset="1" class="pjwjqfcmo"/></linearGradient><filter id="ibpcnEb" width="20.456" height="28.462" x="5.091" y="1.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.439216 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2119"/></filter><filter id="ibg81Nb" width="10.247" height="11.456" x="5.041" y="10.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation="1"/></filter><filter id="iUNnDJc" width="13.44" height="9.077" x="12.656" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation="1"/></filter><filter id="izYoLFc" width="3.501" height="7.258" x="7.334" y="11.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation=".5"/></filter><filter id="i6HnDGb" width="2.901" height="5.126" x="6.827" y="12.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation=".375"/></filter><filter id="ivataMb" width="4.752" height="7.553" x="10.099" y="9.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation=".5"/></filter><filter id="ii0196G" width="6.515" height="12.042" x="12.743" y="2.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation=".75"/></filter><filter id="iA7rWvb" width="4.826" height="12.521" x="19.526" y="2.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation=".75"/></filter><filter id="ije9eBe" width="9.691" height="8.199" x="16.106" y="14.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2119" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:victory-hand-medium-light" /></template>
<style>
.a_f3fh8ja {
  d: path("M18.476 5.814a2.636 2.636 0 0 1 2.675-2.596c1.455.022 2.666 1.22 2.644 2.675l-.086 5.766c-.021 1.455-1.103 1.798-2.558 1.777c-1.456-.022-2.697-.387-2.675-1.843z");
}

.a0k-rnbnj {
  stop-color: var(--svg-color--e7ac9e, #E7AC9E);
  stop-opacity: 0;
}

.a590uwbio {
  stop-color: var(--svg-color--ba7377, #BA7377);
  stop-opacity: 0;
}

.aefwyj94t {
  width: 2.272px;
  height: 5.588px;
  x: 10.947px;
  y: 11.114px;
  rx: 1.136px;
}

.aomvlhbbn {
  stop-color: var(--svg-color--dc9f88, #DC9F88);
}

.awki8cbqd {
  width: 1.019px;
  height: 3.653px;
  x: 7.508px;
  y: 13.432px;
  rx: 0.51px;
}

.b86dahbou {
  fill: var(--svg-color--e0a494, #E0A494);
  d: path("M11.73 5.458c-.326-1.419.59-2.858 2.009-3.185c1.418-.326 2.85.542 3.177 1.96l1.528 6.993l.08-5.412a2.636 2.636 0 0 1 5.271.08l-.112 7.47a6 6 0 0 0 .199 1.623l.499 1.888c.346 1.087 1.029 3.863.428 5.91c-.612 2.65-2.772 4.77-4.647 5.83s-3.944 1.58-6.971 1.152c-3.903-.836-6.115-3.577-6.9-7.124c-.668-2.74-1.04-5.634-1.2-6.76l8.586-2.116z");
}

.bllir2bya {
  stop-color: var(--svg-color--dd9e79, #DD9E79);
}

.btyea4buz {
  stop-color: var(--svg-color--c58560, #C58560);
  stop-opacity: 0;
}

.clbpnubbb {
  stop-color: var(--svg-color--c27580, #C27580);
}

.cm_hntbvk {
  stop-color: var(--svg-color--e0a495, #E0A495);
  stop-opacity: 0;
}

.d2_rir6tr {
  stop-color: var(--svg-color--f8c095, #F8C095);
}

.d64vuzb5y {
  fill: var(--svg-color--8f4f46, #8F4F46);
  d: path("m7.041 13.32l5.25-.784l.997 6.672l-5.25.784z");
}

.dydcj5d2k {
  stop-color: var(--svg-color--a47f71, #A47F71);
  stop-opacity: 0;
}

.ekhlrrbxz {
  stop-color: var(--svg-color--ffcfa7, #FFCFA7);
  stop-opacity: 0;
}

.esjqqiyof {
  stop-color: var(--svg-color--ddb28e, #DDB28E);
}

.f2glsth4z {
  width: 5.309px;
  height: 8.693px;
  x: 8.367px;
  y: 10.437px;
  rx: 2.591px;
}

.ft5dv1b6b {
  fill: none;
}

.g3im_y09y {
  stop-color: var(--svg-color--e8af98, #E8AF98);
  stop-opacity: 0;
}

.g94328b_p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.356 17.16h1.807c1.194 0 2.43.401 2.924 1.489c.26.575.46 1.31.46 2.21");
}

.gg-3_1lxr {
  stop-color: var(--svg-color--bb815d, #BB815D);
}

.ggwu9gzpf {
  stop-color: var(--svg-color--e6b186, #E6B186);
}

.gxf44y0xl {
  width: 0.874px;
  height: 5.303px;
  x: 8.277px;
  y: 12.536px;
  fill: var(--svg-color--bc7f5b, #BC7F5B);
  rx: 0.437px;
}

.hnvwo41ut {
  stop-color: var(--svg-color--e0a594, #E0A594);
}

.ib_dhmb-l {
  d: path("M11.73 5.458c-.326-1.419.59-2.858 2.009-3.185c1.418-.326 2.85.542 3.177 1.96l1.72 7.734c.326 1.419-1.188 1.438-2.313 1.75s-2.643.366-2.969-1.052z");
}

.idh-vc29e {
  fill-rule: evenodd;
  d: path("M13.739 2.274c-1.419.326-2.335 1.765-2.009 3.184l1.947 8.309l-3.537.872l.208 1.395a2.59 2.59 0 0 1-5.124.765l-.073-.487c.185 1.325.545 3.89 1.14 6.331c.786 3.547 2.997 6.288 6.9 7.124c3.027.428 5.095-.092 6.97-1.152s4.036-3.18 4.648-5.83c.601-2.047-.082-4.823-.428-5.91l-.5-1.888a6 6 0 0 1-.198-1.622l.112-7.472a2.636 2.636 0 1 0-5.27-.079l-.081 5.412l-1.528-6.993c-.326-1.418-1.758-2.286-3.177-1.96");
}

.im4yj9h_p {
  stop-color: var(--svg-color--ca8d63, #CA8D63);
}

.iuc0-d97m {
  stop-color: var(--svg-color--bd8668, #BD8668);
  stop-opacity: 0;
}

.iugp1lw5d {
  stop-color: var(--svg-color--e0a594, #E0A594);
  stop-opacity: 0;
}

.iyk5xpb6y {
  stop-color: var(--svg-color--c3825b, #C3825B);
}

.jyzlcxbbj {
  stop-color: var(--svg-color--e0a494, #E0A494);
}

.kpzra2bsh {
  stop-color: var(--svg-color--cf8b61, #CF8B61);
}

.ll8qulb7z {
  stop-color: var(--svg-color--dc9f88, #DC9F88);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mj4pu2bgz {
  stop-color: var(--svg-color--e0a495, #E0A495);
}

.mm-v1nbql {
  stop-color: var(--svg-color--dd9e79, #DD9E79);
  stop-opacity: 0;
}

.mwbrjjrvz {
  width: 5.182px;
  height: 7.437px;
  x: 4.508px;
  y: 12.006px;
  fill: var(--svg-color--dba583, #DBA583);
  rx: 2.591px;
}

.n020c5bwi {
  stop-color: var(--svg-color--dfa589, #DFA589);
}

.nbb38-bgo {
  stop-color: var(--svg-color--e7ac9e, #E7AC9E);
}

.nm-nwzbjj {
  stroke: var(--svg-color--ffd0aa, #FFD0AA);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m22.077 5.159l-.275 7.97");
}

.o1y2prbvy {
  stop-color: var(--svg-color--bb815d, #BB815D);
  stop-opacity: 0;
}

.o3hi5-pfv {
  stop-color: var(--svg-color--fcc9a9, #FCC9A9);
}

.oad41r0vf {
  stop-color: var(--svg-color--cf8b61, #CF8B61);
  stop-opacity: 0;
}

.oglfs1byf {
  stop-color: var(--svg-color--c27580, #C27580);
  stop-opacity: 0;
}

.onxszmfdr {
  stop-color: var(--svg-color--e8af98, #E8AF98);
}

.pjwjqfcmo {
  stop-color: var(--svg-color--fcc9a9, #FCC9A9);
  stop-opacity: 0;
}

.pnzigcbnm {
  stop-color: var(--svg-color--ffd5b6, #FFD5B6);
}

.pwvlzbc-w {
  stop-color: var(--svg-color--e6b186, #E6B186);
  stop-opacity: 0;
}

.q0c72xbor {
  stop-color: var(--svg-color--bb8b6a, #BB8B6A);
}

.r9f-6_ftc {
  stop-color: var(--svg-color--ba7377, #BA7377);
}

.ra6zuebyu {
  stop-color: var(--svg-color--d1a88c, #D1A88C);
}

.rpyo5pbzk {
  width: 5.309px;
  height: 8.693px;
  x: 8.367px;
  y: 10.437px;
  fill: var(--svg-color--dba583, #DBA583);
  rx: 2.591px;
}

.szt2fobcj {
  stop-color: var(--svg-color--f8c095, #F8C095);
  stop-opacity: 0;
}

.t75p2db6y {
  d: path("M24.993 19.848c.096.982.082 2.031-.184 2.938c-.394 1.705-1.43 3.191-2.617 4.316l-1.497-2.332c.147-2.29-.16-3.456-.54-3.892c-.427-.49-.682-.49-1.752-.49a5.4 5.4 0 0 1-1.095-.106a3 3 0 0 1-.226-.053a2 2 0 0 1-.413-.15l.001-.005A2.665 2.665 0 0 1 17.801 15h1.916c1.14 0 4.553.854 5.276 4.848");
}

.tqux4qpga {
  width: 5.182px;
  height: 7.437px;
  x: 4.508px;
  y: 12.006px;
  rx: 2.591px;
}

.u7_fp84-r {
  stop-color: var(--svg-color--bd8668, #BD8668);
}

.u74bk4b9n {
  fill: var(--svg-color--e0a494, #E0A494);
  d: path("M24.993 19.848c.096.982.082 2.031-.184 2.938c-.394 1.705-1.43 3.191-2.617 4.316l-1.497-2.332c.147-2.29-.16-3.456-.54-3.892c-.427-.49-.682-.49-1.752-.49a5.4 5.4 0 0 1-1.095-.106a3 3 0 0 1-.226-.053a2 2 0 0 1-.413-.15l.001-.005A2.665 2.665 0 0 1 17.801 15h1.916c1.14 0 4.553.854 5.276 4.848");
}

.v792z-4ox {
  fill: var(--svg-color--8f4f46, #8F4F46);
  d: path("M24.096 21.066a11 11 0 0 0-.039-.498A5.38 5.38 0 0 0 19.02 16h-1.83c-1.4.005-2.534 1.127-2.534 2.51a2.51 2.51 0 0 0 1.454 2.27v.005c.08.042.214.094.393.142q.106.03.217.05c.277.057.63.1 1.045.1h.088v-.01z");
}

.v9nre5tkm {
  stop-color: var(--svg-color--ffd5b6, #FFD5B6);
  stop-opacity: 0;
}

.vyi22ldxx {
  stop-color: var(--svg-color--ffcfa7, #FFCFA7);
}

.wdfolpbqp {
  stop-color: var(--svg-color--cb9a78, #CB9A78);
  stop-opacity: 0;
}

.wpcv8-bgo {
  stroke: var(--svg-color--ffcda6, #FFCDA6);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.145 4.487l1.71 7.237");
}

.wtm1ced1u {
  stop-color: var(--svg-color--bb8b6a, #BB8B6A);
  stop-opacity: 0;
}

.x4dfu9bqm {
  stop-color: var(--svg-color--e0a494, #E0A494);
  stop-opacity: 0;
}

.y1sj7ubrw {
  d: path("M11.73 5.458c-.326-1.419.59-2.858 2.009-3.185c1.418-.326 2.85.542 3.177 1.96l1.528 6.993l.08-5.412a2.636 2.636 0 0 1 5.271.08l-.112 7.47a6 6 0 0 0 .199 1.623l.499 1.888c.346 1.087 1.029 3.863.428 5.91c-.612 2.65-2.772 4.77-4.647 5.83s-3.944 1.58-6.971 1.152c-3.903-.836-6.115-3.577-6.9-7.124c-.668-2.74-1.04-5.634-1.2-6.76l8.586-2.116z");
}

.ys7ct9ewc {
  stop-color: var(--svg-color--ca8d63, #CA8D63);
  stop-opacity: 0;
}

.zbmk2_bod {
  stop-color: var(--svg-color--cb9a78, #CB9A78);
}

.zlb7k-x-q {
  stop-color: var(--svg-color--ddb28e, #DDB28E);
  stop-opacity: 0;
}

.zs8stybtp {
  stop-color: var(--svg-color--dfa589, #DFA589);
  stop-opacity: 0;
}

</style>
