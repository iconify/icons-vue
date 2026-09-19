<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSZCAmb)"><path fill="url(#iDBLGBd)" class="g8wq_wx5x"/><path fill="url(#ivpqSgc)" class="g8wq_wx5x"/><path fill="url(#iUj6tzQ)" class="g8wq_wx5x"/></g><path fill="url(#i95TBSc)" class="g8wq_wx5x"/><path fill="url(#iHQ8lcd)" class="g8wq_wx5x"/><path fill="url(#iIRkMni)" class="g8wq_wx5x"/><g filter="url(#ijkAOAb)"><path class="kcyt6i89d"/></g><g filter="url(#i1yHjoc)"><path class="spwtymb_z"/></g><rect fill="url(#iSrI0ew)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#i0ChIIc)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#irZ0gEc)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#is5paLd)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#iIQ51Pc)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#i19ansd)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#iSCUf4b)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#imNNTbc)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#iXOlgDe)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#ipqWCBb)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#iOeIkMc)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#iN8PJFc)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#inIHzUb)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#i5DDYCe)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#iBxUWXb)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#iEB9M6c)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#iZX5EJc)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><defs><radialGradient id="ivpqSgc" cx="0" cy="0" r="1" gradientTransform="rotate(90.785 -3.306 18.257)scale(6.84439 2.83792)" gradientUnits="userSpaceOnUse"><stop class="j3l1q_b_r"/><stop offset="1" class="jz9sm-sgb"/></radialGradient><radialGradient id="iUj6tzQ" cx="0" cy="0" r="1" gradientTransform="rotate(-63.938 22.844 -6.436)scale(7.24207 13.4771)" gradientUnits="userSpaceOnUse"><stop class="q3ptg-9id"/><stop offset="1" class="c5_er6xyk"/></radialGradient><radialGradient id="i95TBSc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09874 3.46893 -3.9808 -6.99866 24.688 7.567)" gradientUnits="userSpaceOnUse"><stop class="scjo-lbpq"/><stop offset="1" class="r9hd54buy"/></radialGradient><radialGradient id="iHQ8lcd" cx="0" cy="0" r="1" gradientTransform="matrix(4.64396 0 0 9.96517 20.089 26.084)" gradientUnits="userSpaceOnUse"><stop class="kgy983hcw"/><stop offset="1" class="i5mazkbvy"/></radialGradient><radialGradient id="iIRkMni" cx="0" cy="0" r="1" gradientTransform="scale(12.9389 20.0228)rotate(90 .42 .93)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="fvdgo-bfr"/><stop offset="1" class="v8c05lb1w"/></radialGradient><radialGradient id="irZ0gEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58086 2.00356 0 10.449 28.655)" gradientUnits="userSpaceOnUse"><stop class="l7belu4jj"/><stop offset="1" class="nnrex01wt"/></radialGradient><radialGradient id="is5paLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17279 -7.31561 8.00204 -.189 9.788 28.327)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="gf8g_dblk"/><stop offset="1" class="i8znvkyin"/><stop offset="1" class="cmirm9awu"/></radialGradient><radialGradient id="iIQ51Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9313 0 0 -4.89838 11.409 24.948)" gradientUnits="userSpaceOnUse"><stop class="pt2rl6t7h"/><stop offset="1" class="hkdcwu4rc"/></radialGradient><radialGradient id="iSCUf4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.06838 0 0 4.40184 8.078 12.125)" gradientUnits="userSpaceOnUse"><stop class="hr-ph5-rz"/><stop offset="1" class="zpwaeg0ij"/><stop offset="1" class="zpwaeg0ij"/></radialGradient><radialGradient id="imNNTbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78495 2.38236 0 10.98 14.998)" gradientUnits="userSpaceOnUse"><stop class="o5c0-yfdz"/><stop offset="1" class="i_lmo07pj"/></radialGradient><radialGradient id="iXOlgDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.16817 -7.16786 7.78679 -.18269 10.01 14.978)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="tigzzwbic"/><stop offset="1" class="ejzd58azf"/></radialGradient><radialGradient id="iOeIkMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 5.04687 6.835 17.011)" gradientUnits="userSpaceOnUse"><stop class="wgk6rwb5g"/><stop offset="1" class="dcche5bsw"/></radialGradient><radialGradient id="iN8PJFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68226 2.10732 0 9.43 20.227)" gradientUnits="userSpaceOnUse"><stop class="bwp7pnbqb"/><stop offset="1" class="gib-zub8b"/></radialGradient><radialGradient id="inIHzUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17705 -8.21822 8.20018 -.17667 8.867 20.282)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="fepfuynka"/><stop offset="1" class="q8f32pqog"/></radialGradient><radialGradient id="iBxUWXb" cx="0" cy="0" r="1" gradientTransform="matrix(2.12523 .05058 -.2758 11.58802 5.949 19.98)" gradientUnits="userSpaceOnUse"><stop class="akn_5pbqu"/><stop offset="1" class="eruu9obvu"/></radialGradient><radialGradient id="iEB9M6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6702 2.06121 0 9.398 24.613)" gradientUnits="userSpaceOnUse"><stop class="wvi3rkbnz"/><stop offset="1" class="r85eo6qkm"/></radialGradient><radialGradient id="iZX5EJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17323 -8.18127 8.02085 -.16983 8.848 24.669)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="u39aekbxl"/><stop offset="1" class="p8072z6tw"/></radialGradient><linearGradient id="iDBLGBd" x1="26.78" x2="12.286" y1="8.105" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="xu-12ddzr"/><stop offset="1" class="lq0grutgs"/></linearGradient><linearGradient id="iSrI0ew" x1="9.788" x2="9.788" y1="21.013" y2="30" gradientUnits="userSpaceOnUse"><stop class="zk3ilob4y"/><stop offset="1" class="m6pt-81gf"/></linearGradient><linearGradient id="i0ChIIc" x1="6.543" x2="8.42" y1="25.506" y2="25.506" gradientUnits="userSpaceOnUse"><stop class="ta7rpcbti"/><stop offset="1" class="htf9efbnl"/></linearGradient><linearGradient id="i19ansd" x1="8.538" x2="10.883" y1="8.718" y2="15.823" gradientUnits="userSpaceOnUse"><stop class="j_xsmebon"/><stop offset="1" class="sknwj3o9v"/></linearGradient><linearGradient id="ipqWCBb" x1="7.319" x2="10.194" y1="13.105" y2="21.105" gradientUnits="userSpaceOnUse"><stop class="it_j7c_zw"/><stop offset="1" class="llarqs5rn"/></linearGradient><linearGradient id="i5DDYCe" x1="6.351" x2="9.497" y1="18.348" y2="26.233" gradientUnits="userSpaceOnUse"><stop class="r_mc8z3la"/><stop offset="1" class="v-_zx_bok"/></linearGradient><filter id="iSZCAmb" width="18.933" height="27.637" x="9.373" y="2.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.756863 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3088"/></filter><filter id="ijkAOAb" width="12.677" height="20.87" x="5.131" y="1.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3088" stdDeviation="1"/></filter><filter id="i1yHjoc" width="12.088" height="5.26" x="12.396" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3088" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-down-light" /></template>
<style>
.akn_5pbqu {
  stop-color: var(--svg-color--c88b90, #C88B90);
}

.bwp7pnbqb {
  stop-color: var(--svg-color--ffe6c9, #FFE6C9);
}

.c5_er6xyk {
  stop-color: var(--svg-color--eeaea3, #EEAEA3);
  stop-opacity: 0;
}

.cmirm9awu {
  stop-color: var(--svg-color--e8ae99, #E8AE99);
}

.dcche5bsw {
  stop-color: var(--svg-color--da9f82, #DA9F82);
  stop-opacity: 0;
}

.dmcp6rbjw {
  width: 5.784px;
  height: 8.988px;
  x: 6.896px;
  y: 21.013px;
  rx: 2.892px;
}

.dtv3nbcrv {
  width: 5.927px;
  height: 10.097px;
  x: 5.904px;
  y: 12.064px;
  rx: 2.91px;
}

.ejzd58azf {
  stop-color: var(--svg-color--ebb398, #EBB398);
}

.eruu9obvu {
  stop-color: var(--svg-color--c88b90, #C88B90);
  stop-opacity: 0;
}

.ezcfr6bsl {
  width: 5.629px;
  height: 8.806px;
  x: 7.194px;
  y: 7.81px;
  rx: 2.814px;
}

.fepfuynka {
  stop-color: var(--svg-color--ebb39a, #EBB39A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvdgo-bfr {
  stop-color: var(--svg-color--bd7e96, #BD7E96);
  stop-opacity: 0;
}

.g8wq_wx5x {
  d: path("M20.5 26.55a3.268 3.268 0 0 1-6.536 0v-3.76q-.001-.482.072-.96a6 6 0 0 0 .047-.35c.036-.369-.008-.85-.258-1.173l.598-.576a9.28 9.28 0 0 1-5.05-8.275c0-.979.15-1.922.43-2.808l.99-6.466h8.051v.002c4.973.107 8.962 3.35 8.962 9.272c0 3.481-1.667 6.284-4.189 7.864l.006.005c-.172.12-.374.24-.591.371l-.002.001c-.715.429-1.59.953-2.05 1.81c-.4.743-.478 1.949-.478 2.508l-.002-.001z");
}

.gf8g_dblk {
  stop-color: var(--svg-color--e8ae99, #E8AE99);
  stop-opacity: 0;
}

.gib-zub8b {
  stop-color: var(--svg-color--ffe6c9, #FFE6C9);
  stop-opacity: 0;
}

.hkdcwu4rc {
  stop-color: var(--svg-color--cb887c, #CB887C);
  stop-opacity: 0;
}

.hr-ph5-rz {
  stop-color: var(--svg-color--dda384, #DDA384);
}

.htf9efbnl {
  stop-color: var(--svg-color--ba7e93, #BA7E93);
  stop-opacity: 0;
}

.i_lmo07pj {
  stop-color: var(--svg-color--ffe7c9, #FFE7C9);
  stop-opacity: 0;
}

.i5mazkbvy {
  stop-color: var(--svg-color--ffdac4, #FFDAC4);
  stop-opacity: 0;
}

.i8znvkyin {
  stop-color: var(--svg-color--dba188, #DBA188);
}

.it_j7c_zw {
  stop-color: var(--svg-color--deac93, #DEAC93);
}

.j_xsmebon {
  stop-color: var(--svg-color--e5b39a, #E5B39A);
}

.j3l1q_b_r {
  stop-color: var(--svg-color--cf8b80, #CF8B80);
}

.jz9sm-sgb {
  stop-color: var(--svg-color--cf8b80, #CF8B80);
  stop-opacity: 0;
}

.kcyt6i89d {
  fill: var(--svg-color--e39f84, #E39F84);
  d: path("M8.24 5.919c0 .468.122.907.336 1.283c-.855.428-1.445 1.34-1.445 2.394c0 .82.356 1.553.917 2.04a2.64 2.64 0 0 0-.878 1.98c0 1.039.585 1.936 1.431 2.35a2.65 2.65 0 0 0-.618 1.71c0 1.431 1.113 2.591 2.486 2.591h2.753c1.373 0 2.485-1.16 2.485-2.59a2.63 2.63 0 0 0-.89-1.988a2.63 2.63 0 0 0 .99-2.073a2.64 2.64 0 0 0-.897-1.997a2.7 2.7 0 0 0 .898-2.023c0-.728-.281-1.387-.736-1.867c.454-.458.736-1.1.736-1.81c0-1.393-1.083-2.521-2.419-2.521h-2.73c-1.337 0-2.42 1.128-2.42 2.52");
}

.kgy983hcw {
  stop-color: var(--svg-color--ffdac4, #FFDAC4);
}

.l7belu4jj {
  stop-color: var(--svg-color--ffdbc5, #FFDBC5);
}

.llarqs5rn {
  stop-color: var(--svg-color--ffdbbb, #FFDBBB);
}

.lq0grutgs {
  stop-color: var(--svg-color--eab2a3, #EAB2A3);
}

.m6pt-81gf {
  stop-color: var(--svg-color--f4beb0, #F4BEB0);
}

.nnrex01wt {
  stop-color: var(--svg-color--ffdbc5, #FFDBC5);
  stop-opacity: 0;
}

.o5c0-yfdz {
  stop-color: var(--svg-color--ffe7c9, #FFE7C9);
}

.p8072z6tw {
  stop-color: var(--svg-color--ebb49b, #EBB49B);
}

.pt2rl6t7h {
  stop-color: var(--svg-color--cb887c, #CB887C);
}

.q3ptg-9id {
  stop-color: var(--svg-color--eeaea3, #EEAEA3);
}

.q8f32pqog {
  stop-color: var(--svg-color--ebb39a, #EBB39A);
}

.r_mc8z3la {
  stop-color: var(--svg-color--d8a392, #D8A392);
}

.r85eo6qkm {
  stop-color: var(--svg-color--ffe5cb, #FFE5CB);
  stop-opacity: 0;
}

.r9hd54buy {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
  stop-opacity: 0;
}

.s434mcboj {
  width: 5.797px;
  height: 10.051px;
  x: 5.949px;
  y: 16.486px;
  rx: 2.899px;
}

.scjo-lbpq {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
}

.sknwj3o9v {
  stop-color: var(--svg-color--ffdfc1, #FFDFC1);
}

.spwtymb_z {
  fill: var(--svg-color--e6a39a, #E6A39A);
  d: path("M22.984 18.984c-3.643-2.241-7.3-.668-8.247 0l-.84-1.082c5.38-2.562 8.246-.36 9.087 1.081");
}

.ta7rpcbti {
  stop-color: var(--svg-color--ba7e93, #BA7E93);
}

.tigzzwbic {
  stop-color: var(--svg-color--ebb398, #EBB398);
  stop-opacity: 0;
}

.u39aekbxl {
  stop-color: var(--svg-color--ebb49b, #EBB49B);
  stop-opacity: 0;
}

.v-_zx_bok {
  stop-color: var(--svg-color--ffdbbc, #FFDBBC);
}

.v8c05lb1w {
  stop-color: var(--svg-color--bd7e96, #BD7E96);
}

.wgk6rwb5g {
  stop-color: var(--svg-color--da9f82, #DA9F82);
}

.wvi3rkbnz {
  stop-color: var(--svg-color--ffe5cb, #FFE5CB);
}

.xu-12ddzr {
  stop-color: var(--svg-color--ffd8b8, #FFD8B8);
}

.zk3ilob4y {
  stop-color: var(--svg-color--d7a195, #D7A195);
}

.zpwaeg0ij {
  stop-color: var(--svg-color--dda384, #DDA384);
  stop-opacity: 0;
}

</style>
