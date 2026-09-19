<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9CpODc)"><path class="qn7_3mbms"/><path fill="url(#iLOfhJe)" class="i49u0jb4h"/></g><path fill="url(#iReLphb)" class="d94ttnbbo"/><g filter="url(#iUyvzdS)"><path fill="url(#iaymUcd)" class="afuvsp37i"/></g><path fill="url(#ipOvcAn)" class="o8rsn9ban"/><path fill="url(#i8FI72q)" class="o8rsn9ban"/><path fill="url(#iiqbnGe)" class="o8rsn9ban"/><path fill="url(#i3Bkjmd)" class="o8rsn9ban"/><path fill="url(#i5wOHjb)" class="o8rsn9ban"/><path fill="url(#inShzCe)" class="jlkxt1b-o"/><path fill="url(#i1JKIZc)" class="jlkxt1b-o"/><path fill="url(#ip1CTGc)" class="jlkxt1b-o"/><g filter="url(#igif0he)"><path fill="url(#iNLKNxc)" class="hwygqub2f"/></g><g filter="url(#iytggkd)"><path fill="url(#iLDm1Qc)" class="p8xsk0bxc"/></g><path fill="url(#ij2VkCe)" class="vqw4gwb7s"/><path fill="url(#irjFuRP)" class="vqw4gwb7s"/><path fill="url(#i4oPPqe)" class="vqw4gwb7s"/><path fill="url(#i15MwNd)" class="vqw4gwb7s"/><g filter="url(#ivwl8he)"><path fill="url(#iXDdPVc)" class="vbaxtlbwt"/></g><path fill="url(#iIfuplc)" class="i49u0jb4h"/><path fill="url(#igRR94d)" class="i49u0jb4h"/><path fill="url(#icmYjTb)" class="i49u0jb4h"/><path fill="url(#ivmuxjt)" class="i49u0jb4h"/><path fill="url(#iJe9Gte)" class="i49u0jb4h"/><path fill="url(#iRWo0mb)" class="i49u0jb4h"/><g filter="url(#in8RdUc)"><path fill="url(#iVD2Ioc)" class="mddybub0i"/></g><path fill="url(#iEl8t1t)" class="aggo5pb1z"/><path fill="url(#i5QTthS)" class="aggo5pb1z"/><path fill="url(#i1C0Esd)" class="aggo5pb1z"/><g filter="url(#iYrvmHc)"><path fill="url(#isnahvN)" class="n18ry-xel"/></g><defs><linearGradient id="iaymUcd" x1="18.414" x2="11.624" y1="6.372" y2="10.681" gradientUnits="userSpaceOnUse"><stop class="s6k51jtcn"/><stop offset="1" class="c67znyb9w"/></linearGradient><linearGradient id="ipOvcAn" x1="20.155" x2="20.267" y1="8.999" y2="11.049" gradientUnits="userSpaceOnUse"><stop class="nz-iscc1f"/><stop offset="1" class="y1-7qibqm"/></linearGradient><linearGradient id="i8FI72q" x1="20.939" x2="20.924" y1="14.023" y2="13.039" gradientUnits="userSpaceOnUse"><stop class="dsgleacfg"/><stop offset="1" class="y1_jdjbgy"/></linearGradient><linearGradient id="i3Bkjmd" x1="15.221" x2="17.221" y1="11.47" y2="10.851" gradientUnits="userSpaceOnUse"><stop offset=".236" class="cgb5macru"/><stop offset="1" class="rsw9qhbdq"/></linearGradient><linearGradient id="inShzCe" x1="22.111" x2="22.164" y1="12.695" y2="15.774" gradientUnits="userSpaceOnUse"><stop class="moydr9c6g"/><stop offset="1" class="xmqn4_b-j"/></linearGradient><linearGradient id="i1JKIZc" x1="14.924" x2="17.855" y1="15.226" y2="15.431" gradientUnits="userSpaceOnUse"><stop class="cgb5macru"/><stop offset="1" class="rsw9qhbdq"/></linearGradient><linearGradient id="iNLKNxc" x1="25.37" x2="23.29" y1="12.348" y2="16.495" gradientUnits="userSpaceOnUse"><stop class="c5xjm-bnc"/><stop offset="1" class="sy3de655l"/></linearGradient><linearGradient id="iLDm1Qc" x1="29.845" x2="23.682" y1="17.53" y2="26.161" gradientUnits="userSpaceOnUse"><stop class="a5c9r5b5q"/><stop offset="1" class="tahqmyqsp"/></linearGradient><linearGradient id="ij2VkCe" x1="21.177" x2="21.229" y1="17.598" y2="20.382" gradientUnits="userSpaceOnUse"><stop class="opby5l10x"/><stop offset="1" class="bh2uoub4w"/></linearGradient><linearGradient id="irjFuRP" x1="21.149" x2="21.139" y1="23.511" y2="22.04" gradientUnits="userSpaceOnUse"><stop class="opby5l10x"/><stop offset="1" class="bh2uoub4w"/></linearGradient><linearGradient id="i4oPPqe" x1="16.111" x2="18.85" y1="19.414" y2="19.943" gradientUnits="userSpaceOnUse"><stop class="d9k5ku1ib"/><stop offset="1" class="y2a4sdbhm"/></linearGradient><linearGradient id="iXDdPVc" x1="26.549" x2="12.986" y1="21.803" y2="21.803" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></linearGradient><linearGradient id="iIfuplc" x1="9.401" x2="9.401" y1="27.313" y2="21.959" gradientUnits="userSpaceOnUse"><stop class="ezp2_nbie"/><stop offset="1" class="n55x1ubvq"/></linearGradient><linearGradient id="iVD2Ioc" x1="15.869" x2="15.975" y1="27.154" y2="24.185" gradientUnits="userSpaceOnUse"><stop class="wrldoibjb"/><stop offset="1" class="hlimtm7ap"/></linearGradient><linearGradient id="iEl8t1t" x1="19.391" x2="19.145" y1="21.684" y2="24.011" gradientUnits="userSpaceOnUse"><stop class="eixcx7btr"/><stop offset="1" class="rv-9ycb0w"/></linearGradient><linearGradient id="i5QTthS" x1="15.049" x2="17.216" y1="23.545" y2="23.989" gradientUnits="userSpaceOnUse"><stop class="cubuwfiup"/><stop offset="1" class="vi5d7dvai"/></linearGradient><linearGradient id="isnahvN" x1="23.477" x2="9.916" y1="25.984" y2="25.735" gradientUnits="userSpaceOnUse"><stop class="l_3w1myze"/><stop offset="1" class="cv7wwgeqb"/></linearGradient><radialGradient id="iLOfhJe" cx="0" cy="0" r="1" gradientTransform="matrix(2.62497 5.12502 -18.39164 9.41998 4.924 9.445)" gradientUnits="userSpaceOnUse"><stop class="w8zkd9btc"/><stop offset="1" class="rrjsqabub"/></radialGradient><radialGradient id="iReLphb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7422 -1.1133 3.24362 -2.1624 16.611 10.083)" gradientUnits="userSpaceOnUse"><stop class="zd-x08bwh"/><stop offset="1" class="n6jfmbbci"/></radialGradient><radialGradient id="iiqbnGe" cx="0" cy="0" r="1" gradientTransform="rotate(-112.681 18.022 -1.981)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="cal_fs3bf"/><stop offset="1" class="aw253wwfv"/></radialGradient><radialGradient id="i5wOHjb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68398 .97056 -2.27507 -3.94737 28.205 10.008)" gradientUnits="userSpaceOnUse"><stop class="rl7g8yboo"/><stop offset="1" class="h0_9pr2oi"/></radialGradient><radialGradient id="ip1CTGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62144 .87499 -1.31993 -2.44595 29.983 14.601)" gradientUnits="userSpaceOnUse"><stop class="gtcaccb4j"/><stop offset="1" class="zlchv7bof"/></radialGradient><radialGradient id="i15MwNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.354 .79135 -1.24433 -2.12908 27.75 19.322)" gradientUnits="userSpaceOnUse"><stop class="jkx5vgsvr"/><stop offset="1" class="f2vsadtow"/></radialGradient><radialGradient id="igRR94d" cx="0" cy="0" r="1" gradientTransform="matrix(2.2675 -.1875 .14684 1.77572 16 12.664)" gradientUnits="userSpaceOnUse"><stop class="c7i9-_bft"/><stop offset="1" class="wxz6rxb6p"/></radialGradient><radialGradient id="icmYjTb" cx="0" cy="0" r="1" gradientTransform="matrix(2.17374 -.09375 .08645 2.00449 16 17.383)" gradientUnits="userSpaceOnUse"><stop class="c7i9-_bft"/><stop offset="1" class="wxz6rxb6p"/></radialGradient><radialGradient id="ivmuxjt" cx="0" cy="0" r="1" gradientTransform="rotate(-1.909 645.796 -462.53)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="c7i9-_bft"/><stop offset="1" class="wxz6rxb6p"/></radialGradient><radialGradient id="iJe9Gte" cx="0" cy="0" r="1" gradientTransform="rotate(-63.435 27.813 -.16)scale(2.37582 3.13027)" gradientUnits="userSpaceOnUse"><stop class="c7i9-_bft"/><stop offset="1" class="wxz6rxb6p"/></radialGradient><radialGradient id="iRWo0mb" cx="0" cy="0" r="1" gradientTransform="matrix(-.60189 -9.50058 17.93405 -1.13617 10.737 26.927)" gradientUnits="userSpaceOnUse"><stop class="is0haqy_b"/><stop offset="1" class="tc4b3ybft"/></radialGradient><radialGradient id="i1C0Esd" cx="0" cy="0" r="1" gradientTransform="rotate(154.485 10.034 14.562)scale(1.95209 5.21489)" gradientUnits="userSpaceOnUse"><stop class="g045yv56a"/><stop offset="1" class="l44i3w4rg"/></radialGradient><filter id="i9CpODc" width="28.215" height="24.039" x="2.017" y="2.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6463"/></filter><filter id="iUyvzdS" width="7.823" height="5.458" x="11.832" y="4.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6463" stdDeviation=".375"/></filter><filter id="igif0he" width="13.184" height="3.415" x="14.316" y="10.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6463" stdDeviation=".5"/></filter><filter id="iytggkd" width="15.808" height="4.064" x="14.438" y="14.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6463" stdDeviation=".5"/></filter><filter id="ivwl8he" width="13.094" height="3.555" x="14.455" y="19.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6463" stdDeviation=".5"/></filter><filter id="in8RdUc" width="21.827" height="6.11" x="3.418" y="21.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6463" stdDeviation=".5"/></filter><filter id="iYrvmHc" width="13.092" height="3.521" x="11.391" y="23.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6463" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-hand-dark" /></template>
<style>
.a5c9r5b5q {
  stop-color: var(--svg-color--64504e, #64504E);
}

.afuvsp37i {
  d: path("M15.683 9.58h-3.1l4.822-3.762a.93.93 0 0 1 1.152 1.458z");
}

.aggo5pb1z {
  d: path("m23.94 22.775l-8.548-.267l-.343 4.156l7.145.26a2.406 2.406 0 0 0 1.747-4.149");
}

.aw253wwfv {
  stop-color: var(--svg-color--211413, #211413);
  stop-opacity: 0;
}

.bh2uoub4w {
  stop-color: var(--svg-color--2f1818, #2F1818);
  stop-opacity: 0;
}

.c5xjm-bnc {
  stop-color: var(--svg-color--67514f, #67514F);
}

.c67znyb9w {
  stop-color: var(--svg-color--573c39, #573C39);
  stop-opacity: 0;
}

.c7i9-_bft {
  stop-color: var(--svg-color--523b3b, #523B3B);
}

.cal_fs3bf {
  stop-color: var(--svg-color--211413, #211413);
}

.cgb5macru {
  stop-color: var(--svg-color--4a3133, #4A3133);
}

.cubuwfiup {
  stop-color: var(--svg-color--513939, #513939);
}

.cv7wwgeqb {
  stop-color: var(--svg-color--665250, #665250);
  stop-opacity: 0;
}

.d94ttnbbo {
  d: path("m19.292 4.831l.06.079a2.536 2.536 0 0 1-.494 3.53l-1.419 1.084l-4.512.162z");
}

.d9k5ku1ib {
  stop-color: var(--svg-color--4b3133, #4B3133);
}

.dsgleacfg {
  stop-color: var(--svg-color--35201f, #35201F);
}

.eixcx7btr {
  stop-color: var(--svg-color--321a1b, #321A1B);
}

.ezp2_nbie {
  stop-color: var(--svg-color--533837, #533837);
}

.f2vsadtow {
  stop-color: var(--svg-color--483c3a, #483C3A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g045yv56a {
  stop-color: var(--svg-color--493835, #493835);
}

.gtcaccb4j {
  stop-color: var(--svg-color--483835, #483835);
}

.h0_9pr2oi {
  stop-color: var(--svg-color--4f3e3c, #4F3E3C);
  stop-opacity: 0;
}

.hlimtm7ap {
  stop-color: var(--svg-color--624c4b, #624C4B);
  stop-opacity: 0;
}

.hwygqub2f {
  d: path("m25.883 11.679l-10.567.13l.208 1.285l10.378-.196a.61.61 0 0 0-.02-1.219");
}

.i49u0jb4h {
  d: path("M27.51 13.562a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.041l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.is0haqy_b {
  stop-color: var(--svg-color--51393a, #51393A);
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.jkx5vgsvr {
  stop-color: var(--svg-color--483c3a, #483C3A);
}

.jlkxt1b-o {
  d: path("m26.702 18.4l-.002-.002l.945-.026a2.406 2.406 0 0 0 .022-4.81l-.455.008l-.447.013l.008-.005l-12.6.172v4.687z");
}

.l_3w1myze {
  stop-color: var(--svg-color--665250, #665250);
}

.l44i3w4rg {
  stop-color: var(--svg-color--533f35, #533F35);
  stop-opacity: 0;
}

.mddybub0i {
  d: path("M11.986 26.147c-3.648-.17-6.402-1.909-7.568-3.711l19.827 1.882c0 2.014-1.511 2.252-2.452 2.226c-1.961-.053-6.16-.228-9.807-.398");
}

.moydr9c6g {
  stop-color: var(--svg-color--31201f, #31201F);
}

.n18ry-xel {
  d: path("M23.483 25.607a.673.673 0 0 0-.664-.687c-2.142-.027-7.103-.092-9.627-.17c-.433-.014-.794.282-.8.659c-.007.37.333.677.76.684l9.644.177c.373.007.68-.29.687-.663");
}

.n55x1ubvq {
  stop-color: var(--svg-color--533837, #533837);
  stop-opacity: 0;
}

.n6jfmbbci {
  stop-color: var(--svg-color--231615, #231615);
  stop-opacity: 0;
}

.nz-iscc1f {
  stop-color: var(--svg-color--2b1818, #2B1818);
}

.o8rsn9ban {
  d: path("m17.453 9.513l-2.78.12l1.72 4.125l10.377-.178a2.384 2.384 0 0 0-1.383-4.396l-7.953.344z");
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.opby5l10x {
  stop-color: var(--svg-color--2f1818, #2F1818);
}

.p8xsk0bxc {
  d: path("M26.804 16.311c.302 0 .58-.06.81-.186c.38-.209.855-.43 1.244-.24c.311.153.487.51.33.82c-.542 1.065-1.67 1.196-2.384 1.169H16.211a.77.77 0 0 1-.773-.772c0-.434.355-.782.788-.776c3.493.048 9.664-.015 10.578-.015");
}

.qn7_3mbms {
  fill: var(--svg-color--4a3133, #4A3133);
  d: path("M27.51 13.562a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.041l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.rl7g8yboo {
  stop-color: var(--svg-color--4f3e3c, #4F3E3C);
}

.rrjsqabub {
  stop-color: var(--svg-color--3c272a, #3C272A);
  stop-opacity: 0;
}

.rsw9qhbdq {
  stop-color: var(--svg-color--4a3133, #4A3133);
  stop-opacity: 0;
}

.rv-9ycb0w {
  stop-color: var(--svg-color--321a1b, #321A1B);
  stop-opacity: 0;
}

.s6k51jtcn {
  stop-color: var(--svg-color--573c39, #573C39);
}

.sy3de655l {
  stop-color: var(--svg-color--67514f, #67514F);
  stop-opacity: 0;
}

.tahqmyqsp {
  stop-color: var(--svg-color--64504e, #64504E);
  stop-opacity: 0;
}

.tc4b3ybft {
  stop-color: var(--svg-color--51393a, #51393A);
  stop-opacity: 0;
}

.vbaxtlbwt {
  d: path("M26.549 21.37c0-.432-.35-.78-.782-.777c-2.195.015-7.039.042-9.523.006a.776.776 0 0 0-.789.776c0 .426.346.772.772.772h9.545a.777.777 0 0 0 .777-.777");
}

.vi5d7dvai {
  stop-color: var(--svg-color--513939, #513939);
  stop-opacity: 0;
}

.vqw4gwb7s {
  d: path("m26.705 18.401l-12.156-.018v4.187l9.383.197l-.002-.002l1.37.026a2.406 2.406 0 0 0 1.405-4.39");
}

.w8zkd9btc {
  stop-color: var(--svg-color--3c272a, #3C272A);
}

.wrldoibjb {
  stop-color: var(--svg-color--624c4b, #624C4B);
}

.wxz6rxb6p {
  stop-color: var(--svg-color--523b3b, #523B3B);
  stop-opacity: 0;
}

.xmqn4_b-j {
  stop-color: var(--svg-color--31201f, #31201F);
  stop-opacity: 0;
}

.y1_jdjbgy {
  stop-color: var(--svg-color--35201f, #35201F);
  stop-opacity: 0;
}

.y1-7qibqm {
  stop-color: var(--svg-color--2b1818, #2B1818);
  stop-opacity: 0;
}

.y2a4sdbhm {
  stop-color: var(--svg-color--4b3133, #4B3133);
  stop-opacity: 0;
}

.zd-x08bwh {
  stop-color: var(--svg-color--231615, #231615);
}

.zlchv7bof {
  stop-color: var(--svg-color--483835, #483835);
  stop-opacity: 0;
}

</style>
