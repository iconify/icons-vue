<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irlxveO)" class="grk2p1o7q"/><path fill="url(#itmHqRH)" class="grk2p1o7q"/><path fill="url(#iKpUIRb)" class="ah8mgblru"/><path fill="url(#iVDb0Ob)" class="ah8mgblru"/><rect fill="url(#i0yc6tL)" class="ca3l_ob1l"/><path fill="url(#ilIjgoc)" class="vt3foky3w"/><path class="zs-qayqhv"/><path fill="url(#irRBxab)" class="iz9sru7oq"/><path fill="url(#i3McAxc)" class="sum0mpb6n"/><path fill="url(#iS0iWww)" class="oa3f53i1m"/><path fill="url(#iNCcXGd)" class="vb09y0bih"/><path fill="url(#izY80Gl)" class="vx3djo4iy"/><path fill="url(#idWtDVb)" class="jeje5pq_f"/><path class="y29a041lk"/><path class="fyz_bhbwb"/><path fill="url(#iORy7Ce)" class="d85up4-8d"/><path fill="url(#i1KhXZc)" class="d85up4-8d"/><path fill="url(#if4sE2d)" class="d85up4-8d"/><path fill="url(#in5xOVd)" class="d85up4-8d"/><path fill="url(#imLw2Yc)" class="d85up4-8d"/><path fill="url(#imqftfV)" class="bmuanemgu"/><path fill="url(#i0m9esd)" class="bmuanemgu"/><path fill="url(#izKa8Ic)" class="ricase8dp"/><path fill="url(#iHvS2vb)" class="bes702o2t"/><path fill="url(#ifx3nUb)" class="wes-w6c2g"/><path fill="url(#iyvu9te)" class="f57pv4bbd"/><path fill="url(#ilfs45c)" class="waonwjbfr"/><path fill="url(#i6hpdfe)" class="tm5gjbqie"/><path class="x4-ky3baa"/><path class="y_o0o2blv"/><path fill="url(#iyfHBPc)" class="fkh3v_bzo"/><path fill="url(#iRWaHOc)" class="i0beh5bsd"/><path fill="url(#iYHrh4d)" class="imvx2g4gw"/><path fill="url(#ivp7uHd)" class="iu-cs-bqt"/><path clip-rule="evenodd" class="dxz9wq5mv"/><path class="rl-6kjbsa"/><path clip-rule="evenodd" class="p7a1c5b9h"/><path class="a6olr0bbw"/><path fill="url(#iPWpbSd)" class="tumqcjaet"/><path fill="url(#iSb97we)" class="o-tmdsbrx"/><path fill="url(#iqCN7Gc)" class="o23y2q_5a"/><path fill="url(#ia358db)" class="m3sul076e"/><path fill="url(#iRNDbVc)" class="pcnmcubpk"/><path fill="url(#iNTWxDk)" class="e70xtwb0p"/><path fill="url(#imDdWbd)" class="w5g6t3yth"/><path fill="url(#iZ3k43d)" class="hy3862byj"/><defs><radialGradient id="i3McAxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.99218 .58593 -.28959 -.49037 17.914 28.445)" gradientUnits="userSpaceOnUse"><stop class="n8ykqbbka"/><stop offset="1" class="gh76w5b5p"/></radialGradient><radialGradient id="i1KhXZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00781 .46875 -1.54619 -.02577 14.922 25.14)" gradientUnits="userSpaceOnUse"><stop class="azuulmb_t"/><stop offset="1" class="izir-4brw"/></radialGradient><radialGradient id="if4sE2d" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 .9375 -.26612 .11532 13.953 25.906)" gradientUnits="userSpaceOnUse"><stop class="sfl7l2b5w"/><stop offset="1" class="vaxkcacgm"/></radialGradient><radialGradient id="in5xOVd" cx="0" cy="0" r="1" gradientTransform="rotate(50.146 -20.845 31.643)scale(.99732 .29763)" gradientUnits="userSpaceOnUse"><stop class="k3qmz6eds"/><stop offset="1" class="z5w81wb3k"/></radialGradient><radialGradient id="imLw2Yc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89063 0 0 .52126 14.516 24.453)" gradientUnits="userSpaceOnUse"><stop class="c66pd2x3w"/><stop offset="1" class="gij9s_pnq"/></radialGradient><radialGradient id="imqftfV" cx="0" cy="0" r="1" gradientTransform="matrix(-.64843 1.0625 -1.12062 -.6839 15.703 21.328)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="s8_ri4u2z"/><stop offset=".32" class="q6hn02srk"/><stop offset=".798" class="t04ra0b1r"/></radialGradient><radialGradient id="izKa8Ic" cx="0" cy="0" r="1" gradientTransform="matrix(.35937 1.04688 -1.76194 .60483 18.141 21.407)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="i15b9fbbj"/><stop offset=".181" class="t58t8xb4c"/><stop offset=".467" class="nvei9qbvj"/><stop offset=".873" class="y-p767g9l"/></radialGradient><radialGradient id="iHvS2vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.24306 1.1 -1.14543 -.2531 14.297 21.245)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i15b9fbbj"/><stop offset=".337" class="t58t8xb4c"/><stop offset=".613" class="ijwzyclpp"/><stop offset="1" class="y-p767g9l"/></radialGradient><radialGradient id="ifx3nUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.56379 -1.54416 0 18.664 20.28)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="bkz4dzbei"/><stop offset=".561" class="egpyvzbat"/><stop offset="1" class="xr9jeybwq"/></radialGradient><radialGradient id="iyvu9te" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.56379 -1.54416 0 13.344 20.28)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="qjpg6ibno"/><stop offset=".561" class="egpyvzbat"/><stop offset="1" class="xr9jeybwq"/></radialGradient><radialGradient id="ilfs45c" cx="0" cy="0" r="1" gradientTransform="rotate(-129.436 14.317 5.86)scale(.63955 .85369)" gradientUnits="userSpaceOnUse"><stop class="gjwoft19a"/><stop offset="1" class="d_bed0edo"/></radialGradient><radialGradient id="i6hpdfe" cx="0" cy="0" r="1" gradientTransform="rotate(-129.909 11.596 7.155)scale(.63322 .84786)" gradientUnits="userSpaceOnUse"><stop class="gjwoft19a"/><stop offset="1" class="d_bed0edo"/></radialGradient><radialGradient id="iyfHBPc" cx="0" cy="0" r="1" gradientTransform="rotate(113.199 1.393 15.771)scale(1.90394)" gradientUnits="userSpaceOnUse"><stop class="ooo3984nz"/><stop offset=".435" class="gq4jgvu_n"/><stop offset=".76" class="jfunewboj"/></radialGradient><radialGradient id="iRWaHOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -1.62377 0 16.531 19.75)" gradientUnits="userSpaceOnUse"><stop class="h661yw8qh"/><stop offset="1" class="yreslebek"/></radialGradient><radialGradient id="iSb97we" cx="0" cy="0" r="1" gradientTransform="rotate(122.838 8.671 6.548)scale(10.4885)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="lx3__tgsn"/><stop offset=".571" class="p4itl734o"/><stop offset=".924" class="pidt4gb6v"/></radialGradient><radialGradient id="iqCN7Gc" cx="0" cy="0" r="1" gradientTransform="rotate(118.727 1.538 7.31)scale(6.37177 14.0504)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="lldcpbb3e"/><stop offset=".303" class="l8zzbjb9x"/><stop offset=".534" class="furvwd3si"/><stop offset=".762" class="mp6ua98qf"/><stop offset=".996" class="pnrq3cc8a"/></radialGradient><radialGradient id="ia358db" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 8.78125 -4.46623 1.19205 9.906 6.156)" gradientUnits="userSpaceOnUse"><stop class="xezleacvu"/><stop offset=".436" class="rqrr6ld2g"/><stop offset=".738" class="vrm2cpbmi"/></radialGradient><radialGradient id="iRNDbVc" cx="0" cy="0" r="1" gradientTransform="rotate(108.06 10.925 14.99)scale(6.04798 10.122)" gradientUnits="userSpaceOnUse"><stop class="sfiqop45t"/><stop offset=".698" class="fnvt1xoin"/><stop offset="1" class="ej_sksbjp"/></radialGradient><radialGradient id="iNTWxDk" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43755 6.25495 -5.66287 -3.11216 24.125 6.5)" gradientUnits="userSpaceOnUse"><stop class="ovw9dsbem"/><stop offset=".466" class="l_ry81btp"/><stop offset="1" class="s2l3hydvb"/></radialGradient><radialGradient id="imDdWbd" cx="0" cy="0" r="1" gradientTransform="matrix(.24218 .625 -.47868 .18548 19.664 19.891)" gradientUnits="userSpaceOnUse"><stop class="ds9p4kzka"/><stop offset=".218" class="ds9p4kzka"/><stop offset=".622" class="ojmh81vgb"/></radialGradient><radialGradient id="iZ3k43d" cx="0" cy="0" r="1" gradientTransform="matrix(-.16406 .70313 -.5385 -.12565 12.402 19.598)" gradientUnits="userSpaceOnUse"><stop class="u65qowbhp"/><stop offset=".218" class="ywqc5gn6u"/><stop offset=".704" class="jo2knabzf"/></radialGradient><linearGradient id="irlxveO" x1="19.074" x2="18.254" y1="15.594" y2="15.594" gradientUnits="userSpaceOnUse"><stop class="gh88s7sup"/><stop offset=".243" class="d27a9fbfo"/><stop offset=".753" class="tg85u0cmk"/><stop offset=".972" class="ma1y3ibfq"/></linearGradient><linearGradient id="itmHqRH" x1="19.074" x2="18.254" y1="11.969" y2="13.062" gradientUnits="userSpaceOnUse"><stop class="xt-hlzybi"/><stop offset="1" class="kjijhjbxo"/></linearGradient><linearGradient id="iKpUIRb" x1="13.754" x2="12.934" y1="16.125" y2="16.125" gradientUnits="userSpaceOnUse"><stop class="mzxqds_mg"/><stop offset=".472" class="z4w4gebbu"/><stop offset="1" class="fekm-hbrq"/></linearGradient><linearGradient id="iVDb0Ob" x1="13.344" x2="13.754" y1="11.562" y2="13.437" gradientUnits="userSpaceOnUse"><stop class="o4e75obvc"/><stop offset="1" class="z1dhz6b-w"/></linearGradient><linearGradient id="i0yc6tL" x1="16.016" x2="16.016" y1="15.551" y2="16.359" gradientUnits="userSpaceOnUse"><stop class="evqm0yjsy"/><stop offset=".389" class="iisdoevii"/><stop offset=".733" class="wg968sbbv"/><stop offset="1" class="jgzdidzoe"/></linearGradient><linearGradient id="ilIjgoc" x1="18.134" x2="17.25" y1="23.094" y2="23.094" gradientUnits="userSpaceOnUse"><stop class="v9guu7bko"/><stop offset=".347" class="r04k_ri3h"/><stop offset=".628" class="f8ibtibqz"/></linearGradient><linearGradient id="irRBxab" x1="17.891" x2="17.516" y1="27.922" y2="29.531" gradientUnits="userSpaceOnUse"><stop class="eibmwrz8h"/><stop offset="1" class="ticmadc3g"/></linearGradient><linearGradient id="iS0iWww" x1="13.578" x2="14.982" y1="27.578" y2="27.578" gradientUnits="userSpaceOnUse"><stop class="t8zl1xvfa"/><stop offset="1" class="w-u9sybqm"/></linearGradient><linearGradient id="iNCcXGd" x1="10.156" x2="9.281" y1="17.062" y2="18.031" gradientUnits="userSpaceOnUse"><stop offset=".118" class="kkji2wdfs"/><stop offset=".285" class="l0hrcee2k"/><stop offset=".571" class="j6w6yfb5y"/><stop offset="1" class="xs3b_zbkf"/></linearGradient><linearGradient id="izY80Gl" x1="21.945" x2="22.719" y1="17.344" y2="18.219" gradientUnits="userSpaceOnUse"><stop class="cth-ractz"/><stop offset=".395" class="w3iaffbfc"/><stop offset="1" class="sed2krenl"/></linearGradient><linearGradient id="idWtDVb" x1="14.648" x2="14.414" y1="27.188" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="q_18d4bux"/><stop offset="1" class="h3qgiyb0y"/></linearGradient><linearGradient id="iORy7Ce" x1="17.266" x2="16.859" y1="24.328" y2="24.328" gradientUnits="userSpaceOnUse"><stop class="z59iekbbe"/><stop offset="1" class="c3s429bab"/></linearGradient><linearGradient id="i0m9esd" x1="17.444" x2="16.656" y1="23.391" y2="23.391" gradientUnits="userSpaceOnUse"><stop class="z59iekbbe"/><stop offset="1" class="hvuelfbhb"/></linearGradient><linearGradient id="iYHrh4d" x1="16.703" x2="17.256" y1="20.711" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="id1-hkbyf"/><stop offset=".994" class="uye5zhbwo"/></linearGradient><linearGradient id="ivp7uHd" x1="16.828" x2="17.184" y1="20.148" y2="20.573" gradientUnits="userSpaceOnUse"><stop class="s2l3hydvb"/><stop offset="1" class="a89gg5xsx"/></linearGradient><linearGradient id="iPWpbSd" x1="15.051" x2="17.444" y1="23.995" y2="23.995" gradientUnits="userSpaceOnUse"><stop class="axb1jbbfq"/><stop offset=".041" class="whsspsb6k"/><stop offset="1" class="rjcmw01tt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:parachute" /></template>
<style>
.a6olr0bbw {
  fill: var(--svg-color--e04b3c, #E04B3C);
  d: path("M17.444 23.555h-2.43v.508h2.43z");
}

.a89gg5xsx {
  stop-color: var(--svg-color--1c75ba, #1C75BA);
  stop-opacity: 0;
}

.ah8mgblru {
  d: path("M13.754 10.375c0-.23-.18-.41-.41-.41s-.41.18-.41.41v8.94c0 .23.18.41.41.41s.41-.18.41-.41z");
}

.axb1jbbfq {
  stop-color: var(--svg-color--726383, #726383);
}

.azuulmb_t {
  stop-color: var(--svg-color--e64a57, #E64A57);
}

.bes702o2t {
  d: path("M15.014 21.455h-.72c-.17 0-.31-.14-.31-.31v-1h-.89v1c0 .66.54 1.2 1.2 1.2h.72z");
}

.bkz4dzbei {
  stop-color: var(--svg-color--9984ad, #9984AD);
}

.bmuanemgu {
  d: path("M17.444 21.455h-2.43v2.54h2.43z");
}

.c3s429bab {
  stop-color: var(--svg-color--ff8e4b, #FF8E4B);
  stop-opacity: 0;
}

.c66pd2x3w {
  stop-color: var(--svg-color--ff7e3f, #FF7E3F);
}

.ca3l_ob1l {
  width: 5.563px;
  height: 0.809px;
  x: 13.234px;
  y: 15.551px;
  rx: 0.404px;
}

.cth-ractz {
  stop-color: var(--svg-color--aba5b3, #ABA5B3);
}

.d_bed0edo {
  stop-color: var(--svg-color--be6438, #BE6438);
}

.d27a9fbfo {
  stop-color: var(--svg-color--c7bcd4, #C7BCD4);
}

.d85up4-8d {
  d: path("M15.014 22.345v1.65h-1.15c-.39 0-.75.2-.95.53s-.22.74-.03 1.09l.52 1.11c.1.18.29.3.49.3c.09 0 .18-.02.26-.06c.27-.14.38-.48.24-.75l-.52-1.1h2.14l-.37.77c-.27.58-.17 1.26.25 1.73l.57.65c.11.12.26.19.42.19a.556.556 0 0 0 .41-.93l-.57-.65a.44.44 0 0 1-.07-.51l.72-1.51c.01-.02.02-.05.03-.07c.03-.06.04-.13.04-.2v-2.22z");
}

.ds9p4kzka {
  stop-color: var(--svg-color--e1dae8, #E1DAE8);
}

.dxz9wq5mv {
  fill: var(--svg-color--2239a0, #2239A0);
  fill-rule: evenodd;
  d: path("M15.305 20.325h.957a.36.36 0 0 1 .289.145h.05a.4.4 0 0 1 .1.303c-.002.249-.238.418-.49.418h-.193a.6.6 0 0 1-.205-.048a.4.4 0 0 0-.147-.038a.4.4 0 0 0-.15.039a.6.6 0 0 1-.201.047h-.01a.5.5 0 0 1-.112-.011a1 1 0 0 1-.005-.093v-.047a.37.37 0 0 1-.254-.348c0-.203.166-.367.371-.367");
}

.e70xtwb0p {
  d: path("M23.904 4.025c1.62.52 2.48 1.76 2.75 2.22l.1.17l-4.99 6.34c-.78-.29-1.68-.55-2.66-.74l1.1-7.93s1.79-.68 3.7-.06");
}

.egpyvzbat {
  stop-color: var(--svg-color--d2cbd9, #D2CBD9);
}

.eibmwrz8h {
  stop-color: var(--svg-color--715b88, #715B88);
}

.ej_sksbjp {
  stop-color: var(--svg-color--e27751, #E27751);
}

.evqm0yjsy {
  stop-color: var(--svg-color--a1a2aa, #A1A2AA);
}

.f57pv4bbd {
  d: path("M13.344 19.905c.2 0 .36.16.36.36v.03c0 .2-.16.36-.36.36s-.36-.16-.36-.36v-.03c0-.2.16-.36.36-.36m0-.82c-.65 0-1.18.53-1.18 1.18v.03c0 .65.53 1.18 1.18 1.18s1.18-.53 1.18-1.18v-.03c0-.65-.53-1.18-1.18-1.18");
}

.f8ibtibqz {
  stop-color: var(--svg-color--614178, #614178);
}

.fekm-hbrq {
  stop-color: var(--svg-color--948399, #948399);
}

.fkh3v_bzo {
  d: path("M16.224 21.965h-.18a.85.85 0 0 1-.85-.85v-.64h2.06v.47c0 .56-.46 1.02-1.03 1.02");
}

.fnvt1xoin {
  stop-color: var(--svg-color--f89d47, #F89D47);
}

.ft5dv1b6b {
  fill: none;
}

.furvwd3si {
  stop-color: var(--svg-color--ffbd44, #FFBD44);
}

.fyz_bhbwb {
  fill: var(--svg-color--ff763e, #FF763E);
  d: path("M15.014 22.345v1.65h-1.15c-.39 0-.75.2-.95.53s-.22.74-.03 1.09l.52 1.11c.1.18.29.3.49.3c.09 0 .18-.02.26-.06c.27-.14.38-.48.24-.75l-.52-1.1h2.14l-.37.77c-.27.58-.17 1.26.25 1.73l.57.65c.11.12.26.19.42.19a.556.556 0 0 0 .41-.93l-.57-.65a.44.44 0 0 1-.07-.51l.72-1.51c.01-.02.02-.05.03-.07c.03-.06.04-.13.04-.2v-2.22z");
}

.gh76w5b5p {
  stop-color: var(--svg-color--624384, #624384);
  stop-opacity: 0;
}

.gh88s7sup {
  stop-color: var(--svg-color--c2bcc9, #C2BCC9);
}

.gij9s_pnq {
  stop-color: var(--svg-color--ff8c4f, #FF8C4F);
  stop-opacity: 0;
}

.gjwoft19a {
  stop-color: var(--svg-color--a34923, #A34923);
}

.gq4jgvu_n {
  stop-color: var(--svg-color--3a70d8, #3A70D8);
}

.grk2p1o7q {
  d: path("M18.664 9.965c-.23 0-.41.18-.41.41v8.94c0 .23.18.41.41.41s.41-.18.41-.41v-8.94c0-.23-.18-.41-.41-.41");
}

.h3qgiyb0y {
  stop-color: var(--svg-color--6f5686, #6F5686);
  stop-opacity: 0;
}

.h661yw8qh {
  stop-color: var(--svg-color--649feb, #649FEB);
}

.hvuelfbhb {
  stop-color: var(--svg-color--ff904d, #FF904D);
  stop-opacity: 0;
}

.hy3862byj {
  d: path("M12.379 20.594c-.074-.383-.066-.545.094-.836s.515-.39.152-.366c-.358.07-.376-.134-.51 0c-.113.113.008.17.05.506c.03.254-.05.313.214.696");
}

.i0beh5bsd {
  d: path("M16.484 19.245h-.7c-.43 0-.77.35-.77.78v.17c0 .08.06.14.14.14h.66v.33c0 .22.17.39.39.39h.83c.13 0 .23-.1.23-.23v-.79c-.01-.45-.35-.79-.78-.79");
}

.i15b9fbbj {
  stop-color: var(--svg-color--c5653a, #C5653A);
}

.id1-hkbyf {
  stop-color: var(--svg-color--6b5288, #6B5288);
}

.iisdoevii {
  stop-color: var(--svg-color--b6abc2, #B6ABC2);
}

.ijwzyclpp {
  stop-color: var(--svg-color--eb7c4d, #EB7C4D);
}

.imvx2g4gw {
  d: path("M17.264 20.595h-.79v.24h.79z");
}

.iu-cs-bqt {
  d: path("M16.984 20.465a.14.14 0 1 0 0-.28a.14.14 0 0 0 0 .28");
}

.iz9sru7oq {
  d: path("m16.424 28.005l.86.79c.04.03.07.08.08.13l.24.68c.06.18.32.15.35-.03l.15-1a.26.26 0 0 0-.07-.21l-1.12-1.05z");
}

.izir-4brw {
  stop-color: var(--svg-color--e64a56, #E64A56);
  stop-opacity: 0;
}

.j6w6yfb5y {
  stop-color: var(--svg-color--9985ad, #9985AD);
}

.jeje5pq_f {
  d: path("M14.82 27.555c.007-.038-.336-.589-.547-.914l-.359.14l.524.953c.124-.044.376-.142.382-.18");
}

.jfunewboj {
  stop-color: var(--svg-color--3c5ecb, #3C5ECB);
}

.jgzdidzoe {
  stop-color: var(--svg-color--946fb5, #946FB5);
}

.jo2knabzf {
  stop-color: var(--svg-color--a898b8, #A898B8);
  stop-opacity: 0;
}

.k3qmz6eds {
  stop-color: var(--svg-color--ff9161, #FF9161);
}

.kjijhjbxo {
  stop-color: var(--svg-color--6d6294, #6D6294);
  stop-opacity: 0;
}

.kkji2wdfs {
  stop-color: var(--svg-color--ada9ad, #ADA9AD);
}

.l_ry81btp {
  stop-color: var(--svg-color--349bf6, #349BF6);
}

.l0hrcee2k {
  stop-color: var(--svg-color--bab1c2, #BAB1C2);
}

.l8zzbjb9x {
  stop-color: var(--svg-color--ffd659, #FFD659);
}

.lldcpbb3e {
  stop-color: var(--svg-color--f99d2a, #F99D2A);
}

.lx3__tgsn {
  stop-color: var(--svg-color--6dffac, #6DFFAC);
}

.m3sul076e {
  d: path("M8.094 4.025c-1.61.52-2.47 1.76-2.74 2.21l-.1.17l4.99 6.34c.78-.29 1.68-.55 2.66-.74l-1.1-7.92s-1.79-.68-3.71-.06");
}

.ma1y3ibfq {
  stop-color: var(--svg-color--938ba1, #938BA1);
}

.mp6ua98qf {
  stop-color: var(--svg-color--f39446, #F39446);
}

.mzxqds_mg {
  stop-color: var(--svg-color--b1aeb7, #B1AEB7);
}

.n8ykqbbka {
  stop-color: var(--svg-color--755f90, #755F90);
}

.nvei9qbvj {
  stop-color: var(--svg-color--ff813e, #FF813E);
}

.o-tmdsbrx {
  d: path("M26.754 6.415s-.84-1.74-2.84-2.39c-1.91-.62-3.7.06-3.7.06c-.02-.02-.03-.04-.05-.06c-2.11-2.7-6.2-2.7-8.31 0c-.02.02-.04.04-.05.06c0 0-1.79-.68-3.7-.06c-2 .65-2.84 2.39-2.84 2.39s-3.5.71-3.24 4.32a3.745 3.745 0 0 0 3.75 3.75c.64 0 1.28-.16 1.87-.51c1.44-.85 4.46-2.26 8.36-2.27c3.9 0 6.92 1.42 8.37 2.26a3.74 3.74 0 0 0 5.11-1.35c.35-.59.51-1.24.51-1.89c.25-3.6-3.24-4.31-3.24-4.31");
}

.o23y2q_5a {
  d: path("M7.124 4.465c-1.3.78-1.87 1.95-1.87 1.95s-3.5.71-3.24 4.32a3.745 3.745 0 0 0 3.75 3.75c.64 0 1.28-.16 1.87-.51c.81-.47 2.12-1.12 3.79-1.61z");
}

.o4e75obvc {
  stop-color: var(--svg-color--6c6482, #6C6482);
}

.oa3f53i1m {
  d: path("m14.964 27.585l-.85-1.42l-.65.37l.42.72c.04.06.03.14-.02.19l-.36.45c-.03.03-.04.08-.03.12c.02.08.1.13.18.11l1.26-.39c.06-.01.09-.09.05-.15");
}

.ojmh81vgb {
  stop-color: var(--svg-color--e1d9e8, #E1D9E8);
  stop-opacity: 0;
}

.ooo3984nz {
  stop-color: var(--svg-color--3a88e1, #3A88E1);
}

.ovw9dsbem {
  stop-color: var(--svg-color--68c6ff, #68C6FF);
}

.p4itl734o {
  stop-color: var(--svg-color--42c88b, #42C88B);
}

.p7a1c5b9h {
  fill: var(--svg-color--c3b8d1, #C3B8D1);
  fill-rule: evenodd;
  d: path("M14.844 20.705c0-.26.21-.47.47-.47h.98c.258 0 .473.22.45.474a.47.47 0 0 1-.47.466h-.23a.34.34 0 0 1-.302-.203l-.004-.008l-.018-.057a.04.04 0 0 0-.072 0l-.019.056a.32.32 0 0 1-.305.212h-.01a.47.47 0 0 1-.47-.47m.47-.29a.29.29 0 1 0 0 .58h.01c.066 0 .118-.04.135-.088l.021-.065a.22.22 0 0 1 .407 0l.002.005l.019.055a.16.16 0 0 0 .136.093h.23c.16 0 .29-.13.29-.29v-.009c.014-.143-.11-.281-.27-.281z");
}

.pcnmcubpk {
  d: path("M29.484 12.615c.35-.59.51-1.24.51-1.89c.26-3.61-3.24-4.32-3.24-4.32s-.1-.2-.3-.48l-5.38 6.59c1.44.46 2.57 1.03 3.3 1.46c1.78 1.03 4.07.43 5.11-1.36");
}

.pidt4gb6v {
  stop-color: var(--svg-color--389079, #389079);
}

.pnrq3cc8a {
  stop-color: var(--svg-color--db7545, #DB7545);
}

.q_18d4bux {
  stop-color: var(--svg-color--6f5787, #6F5787);
}

.q6hn02srk {
  stop-color: var(--svg-color--b14a29, #B14A29);
}

.qjpg6ibno {
  stop-color: var(--svg-color--8a84ad, #8A84AD);
}

.r04k_ri3h {
  stop-color: var(--svg-color--6d5588, #6D5588);
}

.ricase8dp {
  d: path("M18.414 20.145v1c0 .17-.14.31-.31.31h-.698v.91h.698c.66 0 1.2-.54 1.2-1.2l-.02-1.02z");
}

.rjcmw01tt {
  stop-color: var(--svg-color--70588d, #70588D);
}

.rl-6kjbsa {
  fill: var(--svg-color--9de0ff, #9DE0FF);
  d: path("M16.294 20.325h-.98a.38.38 0 1 0 0 .76h.01c.1 0 .19-.06.22-.15l.02-.06a.13.13 0 0 1 .24 0l.02.06c.04.09.13.15.22.15h.23c.21 0 .38-.17.38-.38c.02-.2-.15-.38-.36-.38");
}

.rqrr6ld2g {
  stop-color: var(--svg-color--eb295b, #EB295B);
}

.s2l3hydvb {
  stop-color: var(--svg-color--1c75ba, #1C75BA);
}

.s8_ri4u2z {
  stop-color: var(--svg-color--923b1a, #923B1A);
}

.sed2krenl {
  stop-color: var(--svg-color--bca4d2, #BCA4D2);
}

.sfiqop45t {
  stop-color: var(--svg-color--ffef6b, #FFEF6B);
}

.sfl7l2b5w {
  stop-color: var(--svg-color--ff9264, #FF9264);
}

.sum0mpb6n {
  d: path("m17.922 28.406l-.5-.508l-.258.329l.484.414l.22.906c.03-.268.096-.825.109-.906a.45.45 0 0 0-.055-.235");
}

.t04ra0b1r {
  stop-color: var(--svg-color--b44a29, #B44A29);
  stop-opacity: 0;
}

.t58t8xb4c {
  stop-color: var(--svg-color--dc6c30, #DC6C30);
}

.t8zl1xvfa {
  stop-color: var(--svg-color--57446b, #57446B);
}

.tg85u0cmk {
  stop-color: var(--svg-color--a698bb, #A698BB);
}

.ticmadc3g {
  stop-color: var(--svg-color--46335f, #46335F);
}

.tm5gjbqie {
  d: path("M13.334 20.745h-.02a.38.38 0 0 1-.38-.38v-.21h.79v.21c0 .21-.17.38-.39.38");
}

.tumqcjaet {
  d: path("M17.444 23.555h-2.43v.44h2.43z");
}

.u65qowbhp {
  stop-color: var(--svg-color--9a8f9e, #9A8F9E);
}

.uye5zhbwo {
  stop-color: var(--svg-color--4e3567, #4E3567);
}

.v9guu7bko {
  stop-color: var(--svg-color--695383, #695383);
}

.vaxkcacgm {
  stop-color: var(--svg-color--ff9262, #FF9262);
  stop-opacity: 0;
}

.vb09y0bih {
  d: path("m12.904 19.685l-8.93-7.89a.412.412 0 0 0-.54.62l9.05 8c.02.02.05.04.08.05c.06-.28.19-.54.34-.78");
}

.vrm2cpbmi {
  stop-color: var(--svg-color--d33242, #D33242);
}

.vt3foky3w {
  d: path("M16.474 21.005h-1.45a.38.38 0 0 0-.38.38v1.09h1.84v1.96h1.01c.36 0 .64-.29.64-.64v-2.15c0-.36-.29-.64-.64-.64z");
}

.vx3djo4iy {
  d: path("M19.494 20.505c-.11 0-.23-.05-.31-.14a.41.41 0 0 1 .04-.58l9.05-8a.412.412 0 0 1 .54.62l-9.05 8c-.08.07-.17.1-.27.1");
}

.w-u9sybqm {
  stop-color: var(--svg-color--614283, #614283);
}

.w3iaffbfc {
  stop-color: var(--svg-color--cab9dd, #CAB9DD);
}

.w5g6t3yth {
  d: path("M18.986 19.51c-.143-.062.16.01.512.106c.352.095.44-.143.564 0c.106.12-.085.134-.212.448c-.101.252-.045.358-.436.744c.039-.14.184-.476.11-.744c-.075-.267-.209-.414-.538-.555");
}

.waonwjbfr {
  d: path("M18.664 20.745a.39.39 0 0 1-.39-.39v-.21h.79v.21c-.01.21-.18.39-.4.39");
}

.wes-w6c2g {
  d: path("M18.664 19.905c.2 0 .36.16.36.36v.03c0 .2-.16.36-.36.36s-.36-.16-.36-.36v-.03c0-.2.16-.36.36-.36m0-.82c-.65 0-1.18.53-1.18 1.18v.03c0 .65.53 1.18 1.18 1.18s1.18-.53 1.18-1.18v-.03c0-.65-.53-1.18-1.18-1.18");
}

.wg968sbbv {
  stop-color: var(--svg-color--af97c7, #AF97C7);
}

.whsspsb6k {
  stop-color: var(--svg-color--583979, #583979);
}

.x4-ky3baa {
  fill: var(--svg-color--57377a, #57377A);
  d: path("M15.014 22.995v-1.55h-.38v1.17c0 .21.17.38.38.38");
}

.xezleacvu {
  stop-color: var(--svg-color--ff627c, #FF627C);
}

.xr9jeybwq {
  stop-color: var(--svg-color--7f76a6, #7F76A6);
}

.xs3b_zbkf {
  stop-color: var(--svg-color--896fa1, #896FA1);
}

.xt-hlzybi {
  stop-color: var(--svg-color--6c6294, #6C6294);
}

.y_o0o2blv {
  fill: var(--svg-color--614484, #614484);
  d: path("M17.444 22.995v-1.55h-.38v1.17c0 .21.17.38.38.38");
}

.y-p767g9l {
  stop-color: var(--svg-color--db544c, #DB544C);
}

.y29a041lk {
  fill: var(--svg-color--ff7c46, #FF7C46);
  d: path("M18.414 20.145v1c0 .17-.14.31-.31.31h-3.81c-.17 0-.31-.14-.31-.31v-1h-.89v1c0 .66.54 1.2 1.2 1.2h.72v1.65h-1.15c-.39 0-.75.2-.95.53s-.22.74-.03 1.09l.52 1.11c.1.18.29.3.49.3c.09 0 .18-.02.26-.06c.27-.14.38-.48.24-.75l-.52-1.1h2.14l-.37.77c-.27.58-.17 1.26.25 1.73l.57.65c.11.12.26.19.42.19a.556.556 0 0 0 .41-.93l-.57-.65a.44.44 0 0 1-.07-.51l.72-1.51c.01-.02.02-.05.03-.07c.03-.06.04-.13.04-.2v-2.22h.66c.66 0 1.2-.54 1.2-1.2l-.02-1.02z");
}

.yreslebek {
  stop-color: var(--svg-color--3163a4, #3163A4);
}

.ywqc5gn6u {
  stop-color: var(--svg-color--a395b0, #A395B0);
}

.z1dhz6b-w {
  stop-color: var(--svg-color--6e6684, #6E6684);
  stop-opacity: 0;
}

.z4w4gebbu {
  stop-color: var(--svg-color--b4a8c1, #B4A8C1);
}

.z59iekbbe {
  stop-color: var(--svg-color--ff904d, #FF904D);
}

.z5w81wb3k {
  stop-color: var(--svg-color--ff9166, #FF9166);
  stop-opacity: 0;
}

.zs-qayqhv {
  fill: var(--svg-color--39244e, #39244E);
  d: path("M16.474 21.005h-1.45a.38.38 0 0 0-.38.38v.26h3.49c0-.36-.29-.64-.64-.64z");
}

</style>
