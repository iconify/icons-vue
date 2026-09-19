<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibGjudE)" class="zjbdhlb3x"/><path fill="url(#isjeaSc)" class="zjbdhlb3x"/><path fill="url(#ibBNKfg)" class="zjbdhlb3x"/><path fill="url(#ihhxzEe)" class="zjbdhlb3x"/><path fill="url(#i52X6fc)" class="v34x4fbav"/><path fill="url(#irEBS9Q)" class="rnpuuxr3j"/><rect fill="url(#iyeHofQ)" class="mb0_zpgcf"/><rect fill="url(#iipBGde)" class="arw0app6k"/><path fill="url(#ixF4rtd)" class="ux8huh6ik"/><path fill="url(#iWYD7mc)" class="nb_hgpu6o"/><path fill="url(#ibQhUTd)" class="nb_hgpu6o"/><path fill="url(#iuBSo4b)" class="nb_hgpu6o"/><path fill="url(#iwZbqmb)" class="nb_hgpu6o"/><path fill="url(#iFT06Ge)" class="mkhv_um5d"/><path fill="url(#ilS0ixc)" class="mkhv_um5d"/><path fill="url(#i3BAbad)" class="mkhv_um5d"/><path fill="url(#i38eWrb)" class="mkhv_um5d"/><path fill="url(#iFT06Ge)" class="mkhv_um5d"/><path fill="url(#ilS0ixc)" class="mkhv_um5d"/><path fill="url(#i3BAbad)" class="mkhv_um5d"/><path fill="url(#idEPkVd)" class="mkhv_um5d"/><path fill="url(#i38eWrb)" class="mkhv_um5d"/><g filter="url(#iLJw6dR)"><ellipse fill="url(#ihmgCOe)" class="mn05pwbcx"/></g><ellipse fill="url(#iyLP2ib)" class="b6txprbja"/><ellipse fill="url(#ipon0Et)" class="af7upsbar"/><ellipse transform="matrix(-1 0 0 1 16 5.547)" class="eoghuuz8v"/><g filter="url(#iSKobyd)"><path stroke="url(#i3naAfc)" class="f8rygyvaf"/></g><defs><linearGradient id="isjeaSc" x1="7.144" x2="14.385" y1="14.563" y2="14.563" gradientUnits="userSpaceOnUse"><stop class="vzfimfmfw"/><stop offset="1" class="uarnkzbfs"/></linearGradient><linearGradient id="i52X6fc" x1="22.18" x2="22.18" y1="15.29" y2="28.303" gradientUnits="userSpaceOnUse"><stop class="j_55_wbtw"/><stop offset="1" class="mfjr9rbpg"/></linearGradient><linearGradient id="irEBS9Q" x1="7.673" x2="10.787" y1="24.221" y2="24.221" gradientUnits="userSpaceOnUse"><stop class="f8i1cfbfs"/><stop offset="1" class="b0bjv_bdm"/></linearGradient><linearGradient id="iyeHofQ" x1="9.505" x2="9.505" y1="6.912" y2="15.053" gradientUnits="userSpaceOnUse"><stop class="yffb1xb1n"/><stop offset="1" class="r-1867kdy"/></linearGradient><linearGradient id="iipBGde" x1="12.504" x2="12.504" y1="15.053" y2="21.147" gradientUnits="userSpaceOnUse"><stop class="i-s10ac-f"/><stop offset="1" class="fbpwgccty"/></linearGradient><linearGradient id="ixF4rtd" x1="21.499" x2="21.499" y1="23.451" y2="28.647" gradientUnits="userSpaceOnUse"><stop class="j8t4j8bck"/><stop offset="1" class="ti6tbhhrq"/></linearGradient><linearGradient id="iuBSo4b" x1="22.813" x2="23.797" y1="10.303" y2="11.365" gradientUnits="userSpaceOnUse"><stop class="q119r8h-x"/><stop offset="1" class="l8w3j0b0r"/></linearGradient><linearGradient id="iFT06Ge" x1="6.608" x2="9.005" y1="21.525" y2="18.971" gradientUnits="userSpaceOnUse"><stop class="trm2scc1b"/><stop offset="1" class="r4auhobfb"/></linearGradient><linearGradient id="ilS0ixc" x1="9.289" x2="8.516" y1="24.522" y2="23.091" gradientUnits="userSpaceOnUse"><stop class="i-kp2mfgm"/><stop offset="1" class="jnny6_d9s"/></linearGradient><linearGradient id="i3BAbad" x1="9.26" x2="8.116" y1="18.885" y2="20.316" gradientUnits="userSpaceOnUse"><stop class="jfr--m60t"/><stop offset="1" class="yiaw8duyh"/></linearGradient><linearGradient id="idEPkVd" x1="9.013" x2="8.799" y1="19.274" y2="19.478" gradientUnits="userSpaceOnUse"><stop class="wa78x0yvz"/><stop offset="1" class="cn-u07ymm"/></linearGradient><linearGradient id="ihmgCOe" x1="6.703" x2="21.277" y1="6.135" y2="6.135" gradientUnits="userSpaceOnUse"><stop class="v_csxszqc"/><stop offset="1" class="w1yhmodrn"/></linearGradient><linearGradient id="iyLP2ib" x1="21.587" x2="10.062" y1="5.68" y2="5.68" gradientUnits="userSpaceOnUse"><stop class="hdpf4f2gc"/><stop offset="1" class="o86-8183y"/></linearGradient><linearGradient id="ipon0Et" x1="12.625" x2="20.875" y1="4.428" y2="7.678" gradientUnits="userSpaceOnUse"><stop class="ldk8a5dcq"/><stop offset="1" class="yksknjbsu"/></linearGradient><linearGradient id="i3naAfc" x1="5.956" x2="11.274" y1="17.684" y2="23.078" gradientUnits="userSpaceOnUse"><stop class="ooollbb2r"/><stop offset="1" class="q_-yw4alu"/></linearGradient><radialGradient id="ibGjudE" cx="0" cy="0" r="1" gradientTransform="matrix(-8.0625 0 0 -20.2575 20.5 10.303)" gradientUnits="userSpaceOnUse"><stop class="t59ghgrwq"/><stop offset="1" class="u8ko9xqvi"/></radialGradient><radialGradient id="ibBNKfg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 -4.09375 1.37533 -.46194 9.219 21.084)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="b0vs5obln"/><stop offset="1" class="jwemecc9e"/></radialGradient><radialGradient id="ihhxzEe" cx="0" cy="0" r="1" gradientTransform="matrix(.9902 -3.25723 1.59378 .48451 22.711 12.665)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="noxpn2bpc"/><stop offset="1" class="tyabvdfxo"/></radialGradient><radialGradient id="iWYD7mc" cx="0" cy="0" r="1" gradientTransform="rotate(135.588 10.637 10.516)scale(8.61832 2.91075)" gradientUnits="userSpaceOnUse"><stop class="n7sj7xbpn"/><stop offset="1" class="xc7-btkmd"/></radialGradient><radialGradient id="ibQhUTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.97523 .86688 -1.25206 -1.40855 27.255 8.855)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="lepvdbbcr"/><stop offset="1" class="p2ucf3b0v"/></radialGradient><radialGradient id="iwZbqmb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8594 4.12497 -2.19268 -2.05152 25.125 11.24)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="r7-lzrb0u"/><stop offset=".961" class="jg6j2gjjx"/></radialGradient><radialGradient id="i38eWrb" cx="0" cy="0" r="1" gradientTransform="matrix(.91202 .87294 -2.07845 2.1715 5.031 17.408)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="ckjo_ouob"/><stop offset="1" class="o-x42hbzy"/></radialGradient><filter id="iLJw6dR" width="15.959" height="6.382" x="7.97" y="2.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.576471 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5727"/></filter><filter id="iSKobyd" width="7.807" height="7.878" x="4.499" y="16.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5727" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wood" /></template>
<style>
.af7upsbar {
  cx: 16px;
  cy: 5.701px;
  rx: 4.875px;
  ry: 1.638px;
}

.arw0app6k {
  width: 1.039px;
  height: 4.991px;
  x: 11.984px;
  y: 15.053px;
  rx: 0.52px;
}

.b0bjv_bdm {
  stop-color: var(--svg-color--644240, #644240);
}

.b0vs5obln {
  stop-color: var(--svg-color--42211c, #42211C);
}

.b6txprbja {
  cx: 16px;
  cy: 5.984px;
  rx: 7.015px;
  ry: 2.536px;
}

.ckjo_ouob {
  stop-color: var(--svg-color--634e48, #634E48);
}

.cn-u07ymm {
  stop-color: var(--svg-color--664336, #664336);
  stop-opacity: 0;
}

.eoghuuz8v {
  fill: var(--svg-color--e1a161, #E1A161);
  rx: 2.675px;
  ry: 0.703px;
}

.f8i1cfbfs {
  stop-color: var(--svg-color--584341, #584341);
}

.f8rygyvaf {
  stroke-linecap: round;
  d: path("m5.999 17.813l4.806 4.878");
}

.fbpwgccty {
  stop-color: var(--svg-color--ab685d, #AB685D);
}

.ft5dv1b6b {
  fill: none;
}

.hdpf4f2gc {
  stop-color: var(--svg-color--e4a261, #E4A261);
}

.i-kp2mfgm {
  stop-color: var(--svg-color--5f4341, #5F4341);
}

.i-s10ac-f {
  stop-color: var(--svg-color--ab695c, #AB695C);
}

.j_55_wbtw {
  stop-color: var(--svg-color--775b52, #775B52);
}

.j8t4j8bck {
  stop-color: var(--svg-color--db947e, #DB947E);
}

.jfr--m60t {
  stop-color: var(--svg-color--84645a, #84645A);
}

.jg6j2gjjx {
  stop-color: var(--svg-color--785c53, #785C53);
}

.jnny6_d9s {
  stop-color: var(--svg-color--5f4341, #5F4341);
  stop-opacity: 0;
}

.jwemecc9e {
  stop-color: var(--svg-color--42211c, #42211C);
  stop-opacity: 0;
}

.l8w3j0b0r {
  stop-color: var(--svg-color--4c2b22, #4C2B22);
  stop-opacity: 0;
}

.ldk8a5dcq {
  stop-color: var(--svg-color--b77e65, #B77E65);
}

.lepvdbbcr {
  stop-color: var(--svg-color--876c62, #876C62);
}

.mb0_zpgcf {
  width: 1.039px;
  height: 8.141px;
  x: 8.985px;
  y: 6.912px;
  rx: 0.52px;
}

.mfjr9rbpg {
  stop-color: var(--svg-color--866861, #866861);
}

.mkhv_um5d {
  d: path("M5.258 17.102a1 1 0 0 1 1.42-.026l3.748 3.646c.358.298.605.941.605 1.686c0 1.03-.472 1.863-1.055 1.863c-.22 0-.425-.12-.594-.324l-4.719-4.825a1 1 0 0 1-.008-1.39z");
}

.mn05pwbcx {
  cx: 16px;
  cy: 6.135px;
  rx: 7.93px;
  ry: 3.141px;
}

.n7sj7xbpn {
  stop-color: var(--svg-color--704c4b, #704C4B);
}

.nb_hgpu6o {
  d: path("M26.773 8.57a1 1 0 0 0-1.42-.025l-3.748 3.646c-.358.298-.605.941-.605 1.686c0 1.03.472 1.863 1.055 1.863c.22 0 .425-.12.595-.324l4.718-4.825a1 1 0 0 0 .008-1.39z");
}

.noxpn2bpc {
  stop-color: var(--svg-color--5b322a, #5B322A);
}

.o-x42hbzy {
  stop-color: var(--svg-color--634e48, #634E48);
  stop-opacity: 0;
}

.o86-8183y {
  stop-color: var(--svg-color--daa061, #DAA061);
}

.ooollbb2r {
  stop-color: var(--svg-color--87685f, #87685F);
}

.p2ucf3b0v {
  stop-color: var(--svg-color--876c62, #876C62);
  stop-opacity: 0;
}

.q_-yw4alu {
  stop-color: var(--svg-color--87685f, #87685F);
  stop-opacity: 0;
}

.q119r8h-x {
  stop-color: var(--svg-color--4c2b22, #4C2B22);
}

.r-1867kdy {
  stop-color: var(--svg-color--8b564a, #8B564A);
}

.r4auhobfb {
  stop-color: var(--svg-color--654335, #654335);
}

.r7-lzrb0u {
  stop-color: var(--svg-color--785c53, #785C53);
  stop-opacity: 0;
}

.rnpuuxr3j {
  d: path("M11.031 28.313v-6.057l-2.96-.545v4.154c0 .99 1.155 1.872 2.96 2.448");
}

.t59ghgrwq {
  stop-color: var(--svg-color--956860, #956860);
}

.ti6tbhhrq {
  stop-color: var(--svg-color--c9897c, #C9897C);
}

.trm2scc1b {
  stop-color: var(--svg-color--5c3846, #5C3846);
}

.tyabvdfxo {
  stop-color: var(--svg-color--5b322a, #5B322A);
  stop-opacity: 0;
}

.u8ko9xqvi {
  stop-color: var(--svg-color--734544, #734544);
}

.uarnkzbfs {
  stop-color: var(--svg-color--503c39, #503C39);
  stop-opacity: 0;
}

.ux8huh6ik {
  d: path("M21.998 27.92v-3.97a.499.499 0 1 0-.998 0v4.353q.541-.175.998-.384");
}

.v_csxszqc {
  stop-color: var(--svg-color--a77562, #A77562);
}

.v34x4fbav {
  d: path("M23.36 27.037V13.709H21v14.594c1.035-.334 1.854-.768 2.36-1.267");
}

.vzfimfmfw {
  stop-color: var(--svg-color--503c39, #503C39);
}

.w1yhmodrn {
  stop-color: var(--svg-color--c08067, #C08067);
}

.wa78x0yvz {
  stop-color: var(--svg-color--664336, #664336);
}

.xc7-btkmd {
  stop-color: var(--svg-color--643f3f, #643F3F);
}

.yffb1xb1n {
  stop-color: var(--svg-color--a26651, #A26651);
}

.yiaw8duyh {
  stop-color: var(--svg-color--84645a, #84645A);
  stop-opacity: 0;
}

.yksknjbsu {
  stop-color: var(--svg-color--bb7e65, #BB7E65);
}

.zjbdhlb3x {
  d: path("M23.92 5.975c-.21-1.66-3.676-2.98-7.92-2.98s-7.71 1.32-7.92 2.98l-.01.156v19.734c0 1.734 3.55 3.14 7.93 3.14s7.93-1.406 7.93-3.14V6.17z");
}

</style>
