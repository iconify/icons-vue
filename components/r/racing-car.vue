<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibXqMAB)" class="eqprnbzlf"/><path class="jj46m8jyo"/><path class="ssffyobsk"/><path fill="url(#ijaNiyc)" class="sg8-gnfsq"/><path fill="url(#icVGlFb)" class="obc77bcdb"/><path fill="url(#i39Vqtc)" clip-rule="evenodd" class="a92nykb_h"/><path fill="url(#i0mUljc)" class="x25bb6uoy"/><path fill="url(#icYKBkc)" class="x25bb6uoy"/><path fill="url(#iKuVZtc)" class="j9sqdmbbi"/><path fill="url(#i93pMhm)" class="u2uea3_he"/><path fill="url(#i0Xwuxb)" class="u2uea3_he"/><path fill="url(#i5S0Cyd)" class="a4zdlacov"/><path fill="url(#iZX4JfX)" class="a4zdlacov"/><path fill="url(#ixWY9Ib)" class="a4zdlacov"/><path class="t7sc8g-1r"/><path fill="url(#icIUIZE)" class="gtqkm865q"/><path fill="url(#iSc7JGc)" class="gtqkm865q"/><path fill="url(#i9HTohe)" class="ynrvk3bbp"/><path fill="url(#iJwIL8b)" class="ynrvk3bbp"/><path fill="url(#iK55IIe)" class="ynrvk3bbp"/><path fill="url(#iH6RZre)" class="ynrvk3bbp"/><path fill="url(#iaOTBPF)" class="ynrvk3bbp"/><path fill="url(#isWsSKc)" class="sad_exnxk"/><path fill="url(#iwzCivc)" class="qrlq7sb0g"/><path fill="url(#iZZt0Mm)" class="qrlq7sb0g"/><path fill="url(#ioUr5Ie)" class="qrlq7sb0g"/><path fill="url(#ituOVNM)" class="bnapsmbnn"/><path fill="url(#icwbrTb)" class="bnapsmbnn"/><g filter="url(#ia4Hjae)"><path fill="url(#izJpNME)" class="c_yykqrbo"/><path fill="url(#iEa2BFe)" class="c_yykqrbo"/><path fill="url(#ibHnGkc)" class="c_yykqrbo"/></g><g filter="url(#i1ZoMQy)"><path class="s6gko0bbb"/></g><path fill="url(#iZ9jN6c)" clip-rule="evenodd" class="wyiacvbxc"/><path fill="url(#ixTlpYR)" clip-rule="evenodd" class="wyiacvbxc"/><g filter="url(#iZUCaYd)"><path fill="url(#ifFCX1d)" class="anntnoawq"/><path fill="url(#iiUobee)" class="anntnoawq"/><path fill="url(#iVRLFab)" class="anntnoawq"/></g><g filter="url(#icq3ePe)"><path class="e11ihuj0t"/></g><g filter="url(#i4FwjWc)"><circle stroke="url(#iLqeDCe)" class="egmt-il0r"/></g><g filter="url(#ijuzJzd)"><circle stroke="url(#icqtduE)" class="ybkf3ib0v"/></g><defs><linearGradient id="icVGlFb" x1="4.054" x2="17.076" y1="27.018" y2="27.018" gradientUnits="userSpaceOnUse"><stop class="dk-rjqbpr"/><stop offset="1" class="kw7e3obkk"/></linearGradient><linearGradient id="i39Vqtc" x1="16.581" x2="16.581" y1="23.535" y2="27.018" gradientUnits="userSpaceOnUse"><stop class="q5vo533cp"/><stop offset="1" class="g56m3kd5d"/></linearGradient><linearGradient id="i0mUljc" x1="8.324" x2="18.72" y1="25.531" y2="25.531" gradientUnits="userSpaceOnUse"><stop class="mkuu8sbkl"/><stop offset="1" class="otj27nb0n"/></linearGradient><linearGradient id="icYKBkc" x1="23.652" x2="22.027" y1="25.767" y2="25.767" gradientUnits="userSpaceOnUse"><stop class="dg_-cpwbq"/><stop offset="1" class="e1g-r4b-r"/></linearGradient><linearGradient id="i93pMhm" x1="26.021" x2="29.997" y1="21.555" y2="21.555" gradientUnits="userSpaceOnUse"><stop class="d483j9tby"/><stop offset="1" class="i5-01cczj"/><stop offset="1" class="e46-wltzd"/></linearGradient><linearGradient id="i0Xwuxb" x1="25.705" x2="26.775" y1="21.734" y2="21.734" gradientUnits="userSpaceOnUse"><stop class="enz8m7bow"/><stop offset="1" class="agj7w9o8w"/></linearGradient><linearGradient id="i5S0Cyd" x1="26.024" x2="30" y1="19.562" y2="19.562" gradientUnits="userSpaceOnUse"><stop class="txr80jb5b"/><stop offset=".693" class="wavr1wban"/><stop offset="1" class="l2o2npbma"/></linearGradient><linearGradient id="iZX4JfX" x1="25.918" x2="26.847" y1="20.059" y2="20.059" gradientUnits="userSpaceOnUse"><stop class="zpqlvek8p"/><stop offset="1" class="id4ihzb6u"/></linearGradient><linearGradient id="ixWY9Ib" x1="30.136" x2="29.855" y1="20.059" y2="20.059" gradientUnits="userSpaceOnUse"><stop class="zpqlvek8p"/><stop offset="1" class="id4ihzb6u"/></linearGradient><linearGradient id="iSc7JGc" x1="23.927" x2="23.927" y1="27.018" y2="27.11" gradientUnits="userSpaceOnUse"><stop class="s1h_msbjs"/><stop offset="1" class="tw1ikubtf"/></linearGradient><linearGradient id="i9HTohe" x1="3.401" x2="20.428" y1="29.006" y2="29.006" gradientUnits="userSpaceOnUse"><stop class="mkym74h1p"/><stop offset="1" class="d0bhlkble"/></linearGradient><linearGradient id="iJwIL8b" x1="16.808" x2="15.134" y1="29.423" y2="28.848" gradientUnits="userSpaceOnUse"><stop class="vevytfvfi"/><stop offset="1" class="pzubzqbfg"/></linearGradient><linearGradient id="iK55IIe" x1="15.183" x2="15.183" y1="29.485" y2="28.204" gradientUnits="userSpaceOnUse"><stop class="vevytfvfi"/><stop offset="1" class="pzubzqbfg"/></linearGradient><linearGradient id="iaOTBPF" x1="12.558" x2="12.558" y1="27.018" y2="27.11" gradientUnits="userSpaceOnUse"><stop class="mcprfhk0r"/><stop offset="1" class="wa77cew4c"/></linearGradient><linearGradient id="ioUr5Ie" x1="19.058" x2="19.058" y1="29.954" y2="28.173" gradientUnits="userSpaceOnUse"><stop class="cmfkkdbjm"/><stop offset=".93" class="vjw476bfi"/></linearGradient><linearGradient id="ituOVNM" x1="17.574" x2="17.574" y1="26.023" y2="27.515" gradientUnits="userSpaceOnUse"><stop class="fpxc153qz"/><stop offset="1" class="q2ff9ebmh"/></linearGradient><linearGradient id="icwbrTb" x1="18.071" x2="18.071" y1="29.006" y2="26.845" gradientUnits="userSpaceOnUse"><stop class="on7570bcv"/><stop offset="1" class="yr3g70-va"/></linearGradient><linearGradient id="izJpNME" x1="7.022" x2="12.248" y1="25.646" y2="25.646" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="ifFCX1d" x1="24.916" x2="30.142" y1="25.646" y2="25.646" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iLqeDCe" x1="10.666" x2="7.145" y1="24.035" y2="28.191" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="icqtduE" x1="28.541" x2="25.02" y1="24.035" y2="28.191" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><radialGradient id="ibXqMAB" cx="0" cy="0" r="1" gradientTransform="scale(2.24513 2.67188)rotate(90 .373 8.52)" gradientUnits="userSpaceOnUse"><stop class="mr6ws7hsg"/><stop offset="1" class="nq_fkdtqm"/></radialGradient><radialGradient id="ijaNiyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -2.18104 23.37 27.018)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jodficbfl"/><stop offset="1" class="nuqd9bctn"/></radialGradient><radialGradient id="iKuVZtc" cx="0" cy="0" r="1" gradientTransform="matrix(.14952 -4.78674 11.96636 .37378 28.012 23.267)" gradientUnits="userSpaceOnUse"><stop class="fx2boib7q"/><stop offset="1" class="h7tiq_b0v"/></radialGradient><radialGradient id="icIUIZE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03125 0 0 -2.78041 24.37 28.012)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="rihlq8duv"/><stop offset="1" class="bminzebdp"/></radialGradient><radialGradient id="iH6RZre" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 .50496 -.35787 -2.19258 7.214 28.012)" gradientUnits="userSpaceOnUse"><stop class="vevytfvfi"/><stop offset="1" class="pzubzqbfg"/></radialGradient><radialGradient id="isWsSKc" cx="0" cy="0" r="1" gradientTransform="rotate(-68.122 28.102 -3.256)scale(3.52226 7.52437)" gradientUnits="userSpaceOnUse"><stop class="an4ypctma"/><stop offset="1" class="m4aun1b4u"/></radialGradient><radialGradient id="iwzCivc" cx="0" cy="0" r="1" gradientTransform="matrix(3.6139 0 0 2.4375 18.433 26.267)" gradientUnits="userSpaceOnUse"><stop class="k0q84mbob"/><stop offset="1" class="ykv05epaa"/></radialGradient><radialGradient id="iZZt0Mm" cx="0" cy="0" r="1" gradientTransform="matrix(3.73755 0 0 3.11637 18.07 27.515)" gradientUnits="userSpaceOnUse"><stop offset=".749" class="u2sefxb9c"/><stop offset="1" class="azb-nm6il"/></radialGradient><radialGradient id="iEa2BFe" cx="0" cy="0" r="1" gradientTransform="matrix(.78617 -1.72802 1.80486 .82113 8.627 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="ibHnGkc" cx="0" cy="0" r="1" gradientTransform="matrix(.6425 .42504 -.4776 .72196 9.576 26.761)" gradientUnits="userSpaceOnUse"><stop class="f6-f-cyvv"/><stop offset="1" class="qdmn3ybao"/></radialGradient><radialGradient id="iZ9jN6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 1 -.64922 1.2173 22.074 22.595)" gradientUnits="userSpaceOnUse"><stop class="dq092hitm"/><stop offset="1" class="ty6hfkb4j"/></radialGradient><radialGradient id="ixTlpYR" cx="0" cy="0" r="1" gradientTransform="rotate(-52.409 36.507 -11.31)scale(2.48457 4.389)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="oc9ns8wqt"/><stop offset="1" class="r8slnyeds"/></radialGradient><radialGradient id="iiUobee" cx="0" cy="0" r="1" gradientTransform="matrix(.78617 -1.72802 1.80486 .82113 26.52 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iVRLFab" cx="0" cy="0" r="1" gradientTransform="matrix(.6425 .42504 -.4776 .72196 27.47 26.761)" gradientUnits="userSpaceOnUse"><stop class="f6-f-cyvv"/><stop offset="1" class="qdmn3ybao"/></radialGradient><filter id="ia4Hjae" width="6.959" height="7.109" x="5.147" y="23.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10979"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10979" result="effect2_innerShadow_18_10979"/></filter><filter id="i1ZoMQy" width="2.671" height="2.671" x="7.291" y="25.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10979"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10979" result="effect2_innerShadow_18_10979"/></filter><filter id="iZUCaYd" width="6.959" height="7.109" x="23.041" y="23.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10979"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10979" result="effect2_innerShadow_18_10979"/></filter><filter id="icq3ePe" width="2.671" height="2.671" x="25.185" y="25.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10979"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10979" result="effect2_innerShadow_18_10979"/></filter><filter id="i4FwjWc" width="7.169" height="7.169" x="5.339" y="22.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10979" stdDeviation=".375"/></filter><filter id="ijuzJzd" width="7.169" height="7.169" x="23.214" y="22.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10979" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:racing-car" /></template>
<style>
.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.a4zdlacov {
  d: path("M26.024 20.059H30v-.994h-3.976z");
}

.a92nykb_h {
  fill-rule: evenodd;
  d: path("M16.086 27.018v-3.974l.99.991v2.983z");
}

.agj7w9o8w {
  stop-color: var(--svg-color--b58b2c, #B58B2C);
  stop-opacity: 0;
}

.an4ypctma {
  stop-color: var(--svg-color--ff5a56, #FF5A56);
}

.anntnoawq {
  d: path("M26.52 30a3.48 3.48 0 1 0 0-6.959a3.48 3.48 0 0 0 0 6.959");
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.azb-nm6il {
  stop-color: var(--svg-color--e57a14, #E57A14);
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bminzebdp {
  stop-color: var(--svg-color--620b25, #620B25);
  stop-opacity: 0;
}

.bnapsmbnn {
  d: path("M18.07 26.024h-.994v2.982h.995z");
}

.c_yykqrbo {
  d: path("M8.627 30a3.48 3.48 0 1 0 0-6.959a3.48 3.48 0 0 0 0 6.959");
}

.cmfkkdbjm {
  stop-color: var(--svg-color--97594d, #97594D);
}

.d0bhlkble {
  stop-color: var(--svg-color--c8494e, #C8494E);
}

.d483j9tby {
  stop-color: var(--svg-color--e4aa2d, #E4AA2D);
}

.dg_-cpwbq {
  stop-color: var(--svg-color--b9b3ba, #B9B3BA);
}

.dk-rjqbpr {
  stop-color: var(--svg-color--c03131, #C03131);
}

.dq092hitm {
  stop-color: var(--svg-color--f8f2f5, #F8F2F5);
}

.e11ihuj0t {
  fill: var(--svg-color--d2cbe1, #D2CBE1);
  d: path("M26.52 27.806a1.286 1.286 0 1 0 0-2.571a1.286 1.286 0 0 0 0 2.571");
}

.e1g-r4b-r {
  stop-color: var(--svg-color--b9b3ba, #B9B3BA);
  stop-opacity: 0;
}

.e46-wltzd {
  stop-color: var(--svg-color--f38320, #F38320);
}

.egmt-il0r {
  cx: 8.923px;
  cy: 26.37px;
  r: 2.334px;
}

.enz8m7bow {
  stop-color: var(--svg-color--b58b2c, #B58B2C);
}

.eqprnbzlf {
  d: path("M20.059 24.035h-.994v-1.988c0-.547.447-.994.994-.994z");
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.f6-f-cyvv {
  stop-color: var(--svg-color--392a49, #392A49);
}

.fpxc153qz {
  stop-color: var(--svg-color--626162, #626162);
}

.ft5dv1b6b {
  fill: none;
}

.fx2boib7q {
  stop-color: var(--svg-color--ed4c48, #ED4C48);
}

.g56m3kd5d {
  stop-color: var(--svg-color--ff5752, #FF5752);
  stop-opacity: 0;
}

.gtqkm865q {
  d: path("M28.012 27.018H18.07v1.988h9.94z");
}

.h7tiq_b0v {
  stop-color: var(--svg-color--b5312d, #B5312D);
}

.i5-01cczj {
  stop-color: var(--svg-color--ff8213, #FF8213);
}

.id4ihzb6u {
  stop-color: var(--svg-color--94858a, #94858A);
  stop-opacity: 0;
}

.j9sqdmbbi {
  d: path("M26.024 26.498H30v-6.462h-3.976z");
}

.jj46m8jyo {
  fill: var(--svg-color--ee3124, #EE3124);
  d: path("M28.012 24.035h-8.947v2.983h8.947z");
}

.jodficbfl {
  stop-color: var(--svg-color--aa2e30, #AA2E30);
}

.k0q84mbob {
  stop-color: var(--svg-color--ffe042, #FFE042);
}

.kw7e3obkk {
  stop-color: var(--svg-color--fc443f, #FC443F);
}

.l2o2npbma {
  stop-color: var(--svg-color--c7c5cc, #C7C5CC);
}

.m4aun1b4u {
  stop-color: var(--svg-color--ff4940, #FF4940);
}

.mcprfhk0r {
  stop-color: var(--svg-color--bf212e, #BF212E);
}

.mkuu8sbkl {
  stop-color: var(--svg-color--c5c5c7, #C5C5C7);
}

.mkym74h1p {
  stop-color: var(--svg-color--ab3138, #AB3138);
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mr6ws7hsg {
  stop-color: var(--svg-color--727273, #727273);
}

.nq_fkdtqm {
  stop-color: var(--svg-color--4e2a2a, #4E2A2A);
}

.nuqd9bctn {
  stop-color: var(--svg-color--aa2e30, #AA2E30);
  stop-opacity: 0;
}

.obc77bcdb {
  d: path("M14.094 23.041c-2.614 0-5.19.607-7.535 1.78l-4.394 2.197h14.911v-2.983l-.994-.994z");
}

.oc9ns8wqt {
  stop-color: var(--svg-color--c8bbba, #C8BBBA);
  stop-opacity: 0;
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.on7570bcv {
  stop-color: var(--svg-color--2b1b41, #2B1B41);
}

.otj27nb0n {
  stop-color: var(--svg-color--f0ebed, #F0EBED);
}

.pzubzqbfg {
  stop-color: var(--svg-color--722026, #722026);
  stop-opacity: 0;
}

.q2ff9ebmh {
  stop-color: var(--svg-color--646367, #646367);
}

.q5vo533cp {
  stop-color: var(--svg-color--ff5752, #FF5752);
}

.qdmn3ybao {
  stop-color: var(--svg-color--392a49, #392A49);
  stop-opacity: 0;
}

.qrlq7sb0g {
  d: path("M20.556 29.006h-2.485v-2.983h2.485a1.49 1.49 0 0 1 1.491 1.492a1.49 1.49 0 0 1-1.491 1.49");
}

.r8slnyeds {
  stop-color: var(--svg-color--c8bbba, #C8BBBA);
}

.rihlq8duv {
  stop-color: var(--svg-color--620b25, #620B25);
}

.s1h_msbjs {
  stop-color: var(--svg-color--b11b27, #B11B27);
}

.s6gko0bbb {
  fill: var(--svg-color--d9d2e8, #D9D2E8);
  d: path("M8.627 27.806a1.286 1.286 0 1 0 0-2.571a1.286 1.286 0 0 0 0 2.571");
}

.sad_exnxk {
  d: path("M26.024 24.035h-5.965v-2.982c1.909 0 3.738.755 5.09 2.107z");
}

.sg8-gnfsq {
  d: path("M28.012 24.035H13.1v2.983h14.912z");
}

.ssffyobsk {
  fill: var(--svg-color--ee3124, #EE3124);
  d: path("M28.012 24.035H13.1v2.983h14.912z");
}

.t7sc8g-1r {
  fill: var(--svg-color--a0393e, #A0393E);
  d: path("M28.012 27.018H18.07v1.988h9.94z");
}

.tw1ikubtf {
  stop-color: var(--svg-color--b11b27, #B11B27);
  stop-opacity: 0;
}

.txr80jb5b {
  stop-color: var(--svg-color--b9aab5, #B9AAB5);
}

.ty6hfkb4j {
  stop-color: var(--svg-color--f2dee2, #F2DEE2);
}

.u2sefxb9c {
  stop-color: var(--svg-color--e57a14, #E57A14);
  stop-opacity: 0;
}

.u2uea3_he {
  d: path("M26.024 22.047H30v-.994h-3.976z");
}

.vevytfvfi {
  stop-color: var(--svg-color--722026, #722026);
}

.vjw476bfi {
  stop-color: var(--svg-color--97594d, #97594D);
  stop-opacity: 0;
}

.wa77cew4c {
  stop-color: var(--svg-color--bf212e, #BF212E);
  stop-opacity: 0;
}

.wavr1wban {
  stop-color: var(--svg-color--d8d4e0, #D8D4E0);
}

.wyiacvbxc {
  fill-rule: evenodd;
  d: path("m23.28 21.813l-2.226 2.222h4.97l-.875-.875a7.2 7.2 0 0 0-1.87-1.347");
}

.x25bb6uoy {
  d: path("M28.012 25.03H6.142l-1.989.993h23.859z");
}

.ybkf3ib0v {
  cx: 26.798px;
  cy: 26.37px;
  r: 2.334px;
}

.ykv05epaa {
  stop-color: var(--svg-color--dc8b38, #DC8B38);
}

.ynrvk3bbp {
  d: path("M19.808 27.018H2.165v1.988h17.643z");
}

.yr3g70-va {
  stop-color: var(--svg-color--2b1b41, #2B1B41);
  stop-opacity: 0;
}

.zpqlvek8p {
  stop-color: var(--svg-color--94858a, #94858A);
}

</style>
