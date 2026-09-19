<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVQ50nd)" class="qrvw8zb4k"/><path fill="url(#in73MTd)" class="qrvw8zb4k"/><path fill="url(#ipC1qJS)" class="qrvw8zb4k"/><path fill="url(#ibmaPkb)" class="qrvw8zb4k"/><path fill="url(#iz54Bbb)" class="qrvw8zb4k"/><path fill="url(#iJfHITb)" class="qofo0bbjl"/><path fill="url(#iktxLSe)" class="qofo0bbjl"/><path fill="url(#idXLwld)" class="qofo0bbjl"/><g filter="url(#ihuErBc)"><path fill="url(#ip7Kpze)" class="hcl4zacta"/></g><g filter="url(#iDkdTBd)"><path stroke="url(#ie7Grgx)" class="si0g-6_fm"/></g><path fill="url(#i2LfTwe)" class="hrbu-ybrp"/><path fill="url(#ieD3Rbh)" class="hrbu-ybrp"/><path fill="url(#iSbBRve)" class="hrbu-ybrp"/><g filter="url(#ieArYBD)"><path fill="url(#iACqAhd)" class="ebpsnbcrc"/></g><path fill="url(#i3mupkb)" class="kjhu4xbaw"/><path fill="url(#iWjCMTc)" class="kjhu4xbaw"/><path fill="url(#iT8UIOb)" class="kjhu4xbaw"/><path fill="url(#inRdGfd)" class="kjhu4xbaw"/><path fill="url(#i5d18je)" class="kjhu4xbaw"/><path fill="url(#iO6PxMb)" class="wfssnqbra"/><path fill="url(#iGLi07k)" class="wfssnqbra"/><path fill="url(#iQdihnc)" class="wfssnqbra"/><path fill="url(#iPMbdBd)" class="wfssnqbra"/><path fill="url(#iEimQ9v)" class="wfssnqbra"/><path fill="url(#idSuQrx)" class="wfssnqbra"/><path fill="url(#iq3Nu1c)" class="wfssnqbra"/><path fill="url(#iEE44eb)" class="wfssnqbra"/><path fill="url(#i1oMJPc)" class="wfssnqbra"/><g filter="url(#il1cCqc)"><path fill="url(#iEJsMKd)" class="b_tgb1b2n"/></g><defs><linearGradient id="iVQ50nd" x1="16.002" x2="16.002" y1="29.795" y2="20.316" gradientUnits="userSpaceOnUse"><stop class="l9miucc0b"/><stop offset="1" class="sddv6hldr"/></linearGradient><linearGradient id="in73MTd" x1="14.878" x2="15.503" y1="27.925" y2="27.878" gradientUnits="userSpaceOnUse"><stop class="y8f693b9e"/><stop offset="1" class="wnjx4wbjd"/></linearGradient><linearGradient id="ipC1qJS" x1="17" x2="16.503" y1="27.972" y2="27.972" gradientUnits="userSpaceOnUse"><stop class="y8f693b9e"/><stop offset="1" class="wnjx4wbjd"/></linearGradient><linearGradient id="ibmaPkb" x1="14.909" x2="15.347" y1="23.566" y2="23.582" gradientUnits="userSpaceOnUse"><stop class="lcl8i2bvp"/><stop offset="1" class="n4t4mlb3d"/></linearGradient><linearGradient id="iJfHITb" x1="12.508" x2="8.29" y1="24.71" y2="30.421" gradientUnits="userSpaceOnUse"><stop offset=".011" class="hinb-sbwy"/><stop offset="1" class="c3bch-exu"/><stop offset="1" class="o4i9h6buw"/></linearGradient><linearGradient id="iktxLSe" x1="13.883" x2="13.883" y1="30.202" y2="28.233" gradientUnits="userSpaceOnUse"><stop class="e-2abd5ql"/><stop offset="1" class="d7hfbsbga"/></linearGradient><linearGradient id="ip7Kpze" x1="14.524" x2="9.258" y1="28.733" y2="25.374" gradientUnits="userSpaceOnUse"><stop class="dq2vqeb7n"/><stop offset="1" class="ao7x5xbuq"/></linearGradient><linearGradient id="ie7Grgx" x1="14.524" x2="9.727" y1="27.102" y2="24.352" gradientUnits="userSpaceOnUse"><stop class="awtm28vjm"/><stop offset="1" class="q6d83lbcd"/></linearGradient><linearGradient id="i2LfTwe" x1="17.761" x2="24.936" y1="29.785" y2="25.005" gradientUnits="userSpaceOnUse"><stop class="gdhzxbc-m"/><stop offset="1" class="ol8o05bqz"/></linearGradient><linearGradient id="ieD3Rbh" x1="19.198" x2="19.198" y1="30.123" y2="28.717" gradientUnits="userSpaceOnUse"><stop class="h26o556mt"/><stop offset="1" class="oy7h34bgk"/></linearGradient><linearGradient id="iACqAhd" x1="22.667" x2="18.759" y1="25.244" y2="28.478" gradientUnits="userSpaceOnUse"><stop class="norg35btb"/><stop offset="1" class="n-xdwifnc"/></linearGradient><linearGradient id="i3mupkb" x1="16.264" x2="16.264" y1="7.313" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="j6vgg7bgq"/><stop offset="1" class="plchktk5y"/></linearGradient><linearGradient id="iq3Nu1c" x1="25.67" x2="22.295" y1="15.75" y2="15.188" gradientUnits="userSpaceOnUse"><stop class="qnlsznz0b"/><stop offset="1" class="visb5fbno"/></linearGradient><linearGradient id="iEE44eb" x1="6.389" x2="7.92" y1="8.062" y2="8.156" gradientUnits="userSpaceOnUse"><stop class="uon2l3lhy"/><stop offset="1" class="znz1p1esn"/></linearGradient><linearGradient id="iEJsMKd" x1="12.932" x2="3.472" y1="10.457" y2="-1.296" gradientUnits="userSpaceOnUse"><stop class="p63dvac8c"/><stop offset="1" class="csyoo24nx"/></linearGradient><radialGradient id="iz54Bbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.625 -.46875 0 16.206 26.941)" gradientUnits="userSpaceOnUse"><stop class="g_o8fz06n"/><stop offset="1" class="ju50frbjv"/></radialGradient><radialGradient id="idXLwld" cx="0" cy="0" r="1" gradientTransform="rotate(158.54 3.982 13.754)scale(4.86879 6.63165)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="wo8bwxbie"/><stop offset="1" class="emp987nse"/></radialGradient><radialGradient id="iSbBRve" cx="0" cy="0" r="1" gradientTransform="matrix(-.79687 .82813 -.17558 -.16895 23.917 24.92)" gradientUnits="userSpaceOnUse"><stop class="w3qgp_15u"/><stop offset="1" class="y7zl7wbxw"/></radialGradient><radialGradient id="iWjCMTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1 .2765 -1.48087 -5.35581 18.92 8.286)" gradientUnits="userSpaceOnUse"><stop class="femze-bad"/><stop offset="1" class="cqty6mb3b"/></radialGradient><radialGradient id="iT8UIOb" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -6.96875 1.92157 .06894 17.608 12.063)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q4wga11bt"/><stop offset="1" class="imyl7sb_b"/></radialGradient><radialGradient id="inRdGfd" cx="0" cy="0" r="1" gradientTransform="matrix(4.1875 -3.21875 4.2184 5.48801 12.295 10.781)" gradientUnits="userSpaceOnUse"><stop class="q4wga11bt"/><stop offset=".668" class="imyl7sb_b"/></radialGradient><radialGradient id="i5d18je" cx="0" cy="0" r="1" gradientTransform="rotate(18.779 -21.08 40.423)scale(1.74737 8.4415)" gradientUnits="userSpaceOnUse"><stop class="l86i4abar"/><stop offset="1" class="w94zsh0zg"/></radialGradient><radialGradient id="iO6PxMb" cx="0" cy="0" r="1" gradientTransform="rotate(44.328 -10.024 20.158)scale(10.8339 10.4937)" gradientUnits="userSpaceOnUse"><stop class="eays0e59l"/><stop offset="1" class="o0qin2bnx"/></radialGradient><radialGradient id="iGLi07k" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9825 16.37503 -11.572 -1.401 17.983 6.125)" gradientUnits="userSpaceOnUse"><stop offset=".844" class="ieray3bjf"/><stop offset="1" class="lb1ct0ble"/></radialGradient><radialGradient id="iQdihnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.9375 -1.82689 0 16 8.812)" gradientUnits="userSpaceOnUse"><stop class="ztzndkftm"/><stop offset="1" class="bfsqqyb-m"/></radialGradient><radialGradient id="iPMbdBd" cx="0" cy="0" r="1" gradientTransform="matrix(3.29258 -4.4179 .69284 .51636 19.151 7.04)" gradientUnits="userSpaceOnUse"><stop class="lkcf_absb"/><stop offset="1" class="evsts688a"/></radialGradient><radialGradient id="iEimQ9v" cx="0" cy="0" r="1" gradientTransform="rotate(149.81 11.81 7.475)scale(20.6375 21.9671)" gradientUnits="userSpaceOnUse"><stop offset=".913" class="lnpnv8b6a"/><stop offset=".989" class="d54aq7r0v"/></radialGradient><radialGradient id="idSuQrx" cx="0" cy="0" r="1" gradientTransform="rotate(127.534 11.66 7.882)scale(3.96258 .71932)" gradientUnits="userSpaceOnUse"><stop class="bf5_fx1rs"/><stop offset="1" class="k_2oacp5v"/></radialGradient><radialGradient id="i1oMJPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46877 6.5 -1.9403 -.43844 16.826 9.625)" gradientUnits="userSpaceOnUse"><stop class="mh5lj_b3x"/><stop offset="1" class="uwrrneyie"/></radialGradient><filter id="ihuErBc" width="7.218" height="5.43" x="8.056" y="24.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7534" stdDeviation=".375"/></filter><filter id="iDkdTBd" width="4.727" height="5.051" x="10.547" y="24.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7534" stdDeviation=".25"/></filter><filter id="ieArYBD" width="6.997" height="4.988" x="17.067" y="24.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7534" stdDeviation=".3"/></filter><filter id="il1cCqc" width="10.152" height="13.945" x="6.981" y="2.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7534" stdDeviation=".6"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tulip" /></template>
<style>
.ao7x5xbuq {
  stop-color: var(--svg-color--619a6a, #619A6A);
}

.awtm28vjm {
  stop-color: var(--svg-color--86ad7a, #86AD7A);
}

.b_tgb1b2n {
  d: path("M9.016 4.116a.625.625 0 1 0-.419 1.178zM14.7 15.144a.625.625 0 0 0 1.216-.288zm-6.103-9.85c.764.272 1.93 1.177 3.102 2.843c1.159 1.645 2.284 3.978 3.001 7.007l1.216-.288c-.75-3.173-1.938-5.654-3.194-7.439c-1.243-1.764-2.595-2.905-3.706-3.3z");
}

.bf5_fx1rs {
  stop-color: var(--svg-color--ec6fb0, #EC6FB0);
}

.bfsqqyb-m {
  stop-color: var(--svg-color--bc2c76, #BC2C76);
  stop-opacity: 0;
}

.c3bch-exu {
  stop-color: var(--svg-color--008461, #008461);
}

.cqty6mb3b {
  stop-color: var(--svg-color--d36592, #D36592);
  stop-opacity: 0;
}

.csyoo24nx {
  stop-color: var(--svg-color--e573ba, #E573BA);
  stop-opacity: 0;
}

.d54aq7r0v {
  stop-color: var(--svg-color--de86bc, #DE86BC);
}

.d7hfbsbga {
  stop-color: var(--svg-color--6f7e82, #6F7E82);
  stop-opacity: 0;
}

.dq2vqeb7n {
  stop-color: var(--svg-color--6fa06a, #6FA06A);
}

.e-2abd5ql {
  stop-color: var(--svg-color--6f7e82, #6F7E82);
}

.eays0e59l {
  stop-color: var(--svg-color--e55cbb, #E55CBB);
}

.ebpsnbcrc {
  d: path("M17.667 28.51c0-1.79 1.53-3.244 3.341-3.258l2.26-.008c.11 0 .203.09.195.201c-.11 1.984-1.835 3.587-3.953 3.587h-1.623a.214.214 0 0 1-.22-.208z");
}

.emp987nse {
  stop-color: var(--svg-color--92b196, #92B196);
}

.evsts688a {
  stop-color: var(--svg-color--df85aa, #DF85AA);
  stop-opacity: 0;
}

.femze-bad {
  stop-color: var(--svg-color--d36592, #D36592);
}

.ft5dv1b6b {
  fill: none;
}

.g_o8fz06n {
  stop-color: var(--svg-color--83b15d, #83B15D);
}

.gdhzxbc-m {
  stop-color: var(--svg-color--528c39, #528C39);
}

.h26o556mt {
  stop-color: var(--svg-color--6a806e, #6A806E);
}

.hcl4zacta {
  d: path("M8.806 25.827c0 1.856 1.509 3.365 3.296 3.38l2.228.008a.195.195 0 0 0 .194-.209c-.109-2.058-1.81-3.721-3.9-3.721H9.023c-.124 0-.217.1-.217.216z");
}

.hinb-sbwy {
  stop-color: var(--svg-color--629b53, #629B53);
}

.hrbu-ybrp {
  d: path("M16.707 29.085c0-2.4 1.95-4.35 4.26-4.37l2.88-.01c.14 0 .26.12.25.27c-.14 2.66-2.34 4.81-5.04 4.81h-2.07a.28.28 0 0 1-.28-.28z");
}

.ieray3bjf {
  stop-color: var(--svg-color--bb3e97, #BB3E97);
  stop-opacity: 0;
}

.imyl7sb_b {
  stop-color: var(--svg-color--b51e5f, #B51E5F);
  stop-opacity: 0;
}

.j6vgg7bgq {
  stop-color: var(--svg-color--d33e8e, #D33E8E);
}

.ju50frbjv {
  stop-color: var(--svg-color--83b15d, #83B15D);
  stop-opacity: 0;
}

.k_2oacp5v {
  stop-color: var(--svg-color--ec6fb0, #EC6FB0);
  stop-opacity: 0;
}

.kjhu4xbaw {
  d: path("M11.957 7.933c.446-1.396 1.37-4.288 3.173-5.529a1.54 1.54 0 0 1 1.74 0c1.804 1.24 2.727 4.133 3.173 5.53l.066.207L16 14.438L11.89 8.14z");
}

.l86i4abar {
  stop-color: var(--svg-color--e07ea7, #E07EA7);
}

.l9miucc0b {
  stop-color: var(--svg-color--5da112, #5DA112);
}

.lb1ct0ble {
  stop-color: var(--svg-color--bb3e97, #BB3E97);
}

.lcl8i2bvp {
  stop-color: var(--svg-color--8fb87f, #8FB87F);
}

.lkcf_absb {
  stop-color: var(--svg-color--df85aa, #DF85AA);
}

.lnpnv8b6a {
  stop-color: var(--svg-color--de86bc, #DE86BC);
  stop-opacity: 0;
}

.mh5lj_b3x {
  stop-color: var(--svg-color--be2475, #BE2475);
}

.n-xdwifnc {
  stop-color: var(--svg-color--7ba561, #7BA561);
}

.n4t4mlb3d {
  stop-color: var(--svg-color--8fb87f, #8FB87F);
  stop-opacity: 0;
}

.norg35btb {
  stop-color: var(--svg-color--87be58, #87BE58);
}

.o0qin2bnx {
  stop-color: var(--svg-color--d94aaa, #D94AAA);
}

.o4i9h6buw {
  stop-color: var(--svg-color--4d9055, #4D9055);
}

.ol8o05bqz {
  stop-color: var(--svg-color--81bd52, #81BD52);
}

.oy7h34bgk {
  stop-color: var(--svg-color--6a806e, #6A806E);
  stop-opacity: 0;
}

.p63dvac8c {
  stop-color: var(--svg-color--e573ba, #E573BA);
}

.plchktk5y {
  stop-color: var(--svg-color--ad1d50, #AD1D50);
}

.q4wga11bt {
  stop-color: var(--svg-color--b51e5f, #B51E5F);
}

.q6d83lbcd {
  stop-color: var(--svg-color--86ad7a, #86AD7A);
  stop-opacity: 0;
}

.qnlsznz0b {
  stop-color: var(--svg-color--ba4383, #BA4383);
}

.qofo0bbjl {
  d: path("M7.97 25.41c0 2.4 1.95 4.35 4.26 4.37l2.88.01c.14 0 .26-.12.25-.27c-.14-2.66-2.34-4.81-5.04-4.81H8.25a.28.28 0 0 0-.28.28z");
}

.qrvw8zb4k {
  d: path("M17 19.66h-2v10.13h2z");
}

.sddv6hldr {
  stop-color: var(--svg-color--74a93f, #74A93F);
}

.si0g-6_fm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.298 25.457c1.156.156 3.039 1.513 3.226 3.55");
}

.uon2l3lhy {
  stop-color: var(--svg-color--e598bc, #E598BC);
}

.uwrrneyie {
  stop-color: var(--svg-color--be2475, #BE2475);
  stop-opacity: 0;
}

.visb5fbno {
  stop-color: var(--svg-color--ba4383, #BA4383);
  stop-opacity: 0;
}

.w3qgp_15u {
  stop-color: var(--svg-color--9dd271, #9DD271);
}

.w94zsh0zg {
  stop-color: var(--svg-color--e07ea7, #E07EA7);
  stop-opacity: 0;
}

.wfssnqbra {
  d: path("M24.96 4.86c.168 3.968.044 10.898-2.093 14.078c-1.947 2.896-5.26 3.104-6.875 3.105v.004c-1.61 0-4.906-.203-6.86-3.11C6.997 15.759 6.873 8.829 7.04 4.86c0-2.343 2.629-1.409 4.14.078c2.864 2.817 4.298 6.445 4.754 8.394c.026.112.234.112.26 0c.447-1.975 1.793-5.606 4.627-8.394c1.512-1.487 4.14-2.421 4.14-.078");
}

.wnjx4wbjd {
  stop-color: var(--svg-color--51923c, #51923C);
  stop-opacity: 0;
}

.wo8bwxbie {
  stop-color: var(--svg-color--92b196, #92B196);
  stop-opacity: 0;
}

.y7zl7wbxw {
  stop-color: var(--svg-color--9dd271, #9DD271);
  stop-opacity: 0;
}

.y8f693b9e {
  stop-color: var(--svg-color--51923c, #51923C);
}

.znz1p1esn {
  stop-color: var(--svg-color--e598bc, #E598BC);
  stop-opacity: 0;
}

.ztzndkftm {
  stop-color: var(--svg-color--bc2c76, #BC2C76);
}

</style>
