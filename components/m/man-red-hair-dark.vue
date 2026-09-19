<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRyZCfd)"><circle fill="url(#iLGAAeb)" class="c3vm8kt4c"/></g><g filter="url(#il0vpad)"><circle fill="url(#i7bCLjb)" class="n73l6to2h"/></g><g filter="url(#i8litQd)"><circle fill="url(#i8my3bc)" class="jvwpinbbf"/><circle fill="url(#igjvuse)" class="jvwpinbbf"/></g><g filter="url(#ixsutlc)"><circle class="s424eg2ut"/><circle fill="url(#i3RhOed)" class="xq483lxba"/><circle fill="url(#i0p6bru)" class="xq483lxba"/></g><g filter="url(#i3niIle)"><path fill="url(#ioF6nHb)" class="bhop8fbem"/><path fill="url(#indEFIc)" class="bhop8fbem"/><path fill="url(#iTlcJHe)" class="bhop8fbem"/><path fill="url(#ilrnJ5b)" class="bhop8fbem"/><path fill="url(#iyzOLDd)" class="bhop8fbem"/><path fill="url(#is9PYIc)" class="bhop8fbem"/><path fill="url(#iVWUkbe)" class="bhop8fbem"/></g><g filter="url(#i64hIke)"><path fill="url(#ibi3Qyc)" class="y7d3--b_f"/></g><g filter="url(#iKrJ0Rb)"><path fill="url(#isUxwxM)" class="ynsl3-bvt"/><path fill="url(#iq28ndc)" class="ynsl3-bvt"/><path fill="url(#iaLExbc)" class="ynsl3-bvt"/><path fill="url(#iZXjRPb)" class="ynsl3-bvt"/><path fill="url(#iHC9ARb)" class="ynsl3-bvt"/><path fill="url(#i42KZxc)" class="ynsl3-bvt"/></g><path fill="url(#iFldDEc)" class="ynsl3-bvt"/><path fill="url(#i0riIbb)" class="ynsl3-bvt"/><path fill="url(#iBJdSec)" class="ynsl3-bvt"/><g filter="url(#i4fcyzb)"><path class="a9d4hobtp"/></g><g filter="url(#imhnbcd)"><path class="q12lo_b7m"/><path fill="url(#iHslHyb)" class="bdg888bzf"/><path fill="url(#iWnFSzu)" class="bdg888bzf"/><path fill="url(#ibhIFxd)" class="bdg888bzf"/><path fill="url(#iqS7zhc)" class="bdg888bzf"/></g><path fill="url(#iA453fc)" class="bdg888bzf"/><path stroke="url(#iJtWyYd)" class="wcy0rhhon"/><g filter="url(#iLDNidc)"><path class="p71ln533h"/></g><g filter="url(#ibIxzYc)"><path class="ez5ls3poe"/></g><path class="pdv4ldbpr"/><path fill="url(#iT72KYv)" class="ysuyqjbga"/><path class="heacg5ncs"/><g filter="url(#iJHrsge)"><path class="z98s40bed"/><path fill="url(#iO48bjt)" class="z20bumf_j"/></g><g filter="url(#iifsyTL)"><path fill="url(#ikMrDfd)" class="i_ux49j5u"/></g><path class="l6wzmlbrw"/><path fill="url(#igY4D7c)" class="pymlyd-1i"/><path class="uozffyiai"/><g filter="url(#iFr3X2d)"><path fill="url(#itFLHzb)" class="sow05c3ou"/></g><g filter="url(#i4fKTgc)"><ellipse transform="rotate(-27.914 11.367 16.608)" class="xk1wlybvw"/><ellipse fill="url(#ivdEdNn)" transform="rotate(-27.914 11.367 16.608)" class="bz40dzb6n"/></g><g filter="url(#iANTOwc)"><path stroke="url(#is8obne)" class="khbuz0hlc"/></g><g filter="url(#iQwtwye)"><path stroke="url(#i6Xflid)" class="ut7qi9bnx"/></g><defs><radialGradient id="iLGAAeb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="igjvuse" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i3RhOed" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i0p6bru" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.54 39.223)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ioF6nHb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.8125 0 0 -25.0154 24.188 20.375)" gradientUnits="userSpaceOnUse"><stop class="y14k4lb6j"/><stop offset="1" class="g75mbmjbv"/></radialGradient><radialGradient id="iTlcJHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.3495 -27.7163 0 17.216 14.246)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="f0lf6f3kb"/><stop offset="1" class="l9pefv81z"/></radialGradient><radialGradient id="ilrnJ5b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9969 0 0 -3.02146 18.111 17.688)" gradientUnits="userSpaceOnUse"><stop class="qu1cfg7_g"/><stop offset="1" class="scckxcbxt"/></radialGradient><radialGradient id="iyzOLDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 2.93253 0 20.321 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="is9PYIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.625)" gradientUnits="userSpaceOnUse"><stop class="osc-jklcq"/><stop offset="1" class="pup9lmq3m"/></radialGradient><radialGradient id="iVWUkbe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.16694 4.8677 -4.19823 -7.04371 26.313 10.25)" gradientUnits="userSpaceOnUse"><stop class="fspy8rbwh"/><stop offset="1" class="tqs3frbia"/></radialGradient><radialGradient id="iq28ndc" cx="0" cy="0" r="1" gradientTransform="rotate(-169.032 11.112 3.065)scale(8.21251 6.30254)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="tzxi8pb6h"/><stop offset="1" class="hmx8eit6p"/></radialGradient><radialGradient id="iaLExbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56248 -7.49998 14.07497 -1.05559 26.813 17.017)" gradientUnits="userSpaceOnUse"><stop class="gg3p-v-oi"/><stop offset="1" class="go8dnjb_b"/></radialGradient><radialGradient id="iZXjRPb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.625 1.78488 10.88777 3.813 11.563)" gradientUnits="userSpaceOnUse"><stop class="zk1gozblh"/><stop offset="1" class="o7liw8bnz"/></radialGradient><radialGradient id="iHC9ARb" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.40625 -6.20388 5.23883 7.813 4.813)" gradientUnits="userSpaceOnUse"><stop class="hchmvbcwb"/><stop offset="1" class="ei1bt-b0e"/></radialGradient><radialGradient id="i42KZxc" cx="0" cy="0" r="1" gradientTransform="rotate(80.538 7.776 11.423)scale(1.61573 2.88964)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="e_h6jabwf"/><stop offset="1" class="moyyndcqm"/></radialGradient><radialGradient id="iFldDEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 -4.59375 1.72724 -.094 8.219 11.813)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="sn-n94bif"/><stop offset="1" class="vu7vn7bhc"/></radialGradient><radialGradient id="i0riIbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69638 -4.375 1.72998 -.27536 4.196 11.125)" gradientUnits="userSpaceOnUse"><stop class="sdjph8tjs"/><stop offset="1" class="xhmtc9b9f"/></radialGradient><radialGradient id="iBJdSec" cx="0" cy="0" r="1" gradientTransform="matrix(1.11615 -6 2.3152 .43068 27.696 14.375)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="t7o6ccjes"/><stop offset="1" class="kd9fr-txf"/></radialGradient><radialGradient id="iqS7zhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 21.055)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iT72KYv" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="iO48bjt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.941 3.676)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igY4D7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="ivdEdNn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.134 3.016)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iRyZCfd" width="6.427" height="6.227" x="3.979" y="14.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20007"/></filter><filter id="il0vpad" width="4.711" height="4.711" x="4.737" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".25"/></filter><filter id="i8litQd" width="6.477" height="6.477" x="21.72" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20007"/></filter><filter id="ixsutlc" width="4.711" height="4.711" x="22.478" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".25"/></filter><filter id="i3niIle" width="19.345" height="22.73" x="6.327" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.0980392 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20007"/></filter><filter id="i64hIke" width="11.918" height="9.719" x="15.009" y="5.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation="1"/></filter><filter id="iKrJ0Rb" width="23.5" height="15.5" x="4.196" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.262745 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20007"/></filter><filter id="i4fcyzb" width="4.782" height="6.5" x="13.11" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".375"/></filter><filter id="imhnbcd" width="4" height="5.5" x="13.946" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".125"/></filter><filter id="iLDNidc" width="5.34" height="3.147" x="18.151" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20007"/></filter><filter id="ibIxzYc" width="5.341" height="3.147" x="8.551" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20007"/></filter><filter id="iJHrsge" width="1.294" height="1.125" x="18.727" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".05"/></filter><filter id="iifsyTL" width="1.316" height="1.357" x="20.38" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".1"/></filter><filter id="iFr3X2d" width="1.493" height="1.594" x="12.097" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".1"/></filter><filter id="i4fKTgc" width="1.529" height="1.141" x="10.603" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".05"/></filter><filter id="iANTOwc" width="4.949" height="2.304" x="18.293" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".25"/></filter><filter id="iQwtwye" width="5.094" height="2.41" x="8.56" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20007" stdDeviation=".25"/></filter><linearGradient id="i7bCLjb" x1="7.092" x2="5.898" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="i8my3bc" x1="26.859" x2="25.332" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="indEFIc" x1="5.688" x2="9.469" y1="23.188" y2="23" gradientUnits="userSpaceOnUse"><stop offset=".264" class="ndh-ggbqf"/><stop offset="1" class="naoj9jbij"/></linearGradient><linearGradient id="ibi3Qyc" x1="15.701" x2="30.889" y1="13.219" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="isUxwxM" x1="3.433" x2="25.91" y1="11.365" y2="11.365" gradientUnits="userSpaceOnUse"><stop class="z8b5eybgc"/><stop offset=".349" class="rkde3beof"/><stop offset="1" class="q1uq6hbwz"/></linearGradient><linearGradient id="iHslHyb" x1="14.335" x2="16.084" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iWnFSzu" x1="17.696" x2="15.784" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="ibhIFxd" x1="16.309" x2="16.309" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iA453fc" x1="16.181" x2="16.181" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iJtWyYd" x1="14.012" x2="14.824" y1="25.012" y2="23.73" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ikMrDfd" x1="21.46" x2="20.875" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itFLHzb" x1="13.26" x2="12.675" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="is8obne" x1="21.489" x2="20.706" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i6Xflid" x1="11.597" x2="9.379" y1="12.659" y2="11.729" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-red-hair-dark" /></template>
<style>
.a9d4hobtp {
  fill: var(--svg-color--332024, #332024);
  d: path("M15.433 17.83L13.903 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.bdg888bzf {
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.bhop8fbem {
  d: path("M6.327 14.234c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L24.97 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.387-.373-6.785-.683-10.166");
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bz40dzb6n {
  cx: 11.367px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.c3vm8kt4c {
  cx: 7.092px;
  cy: 18.059px;
  r: 3.113px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e_h6jabwf {
  stop-color: var(--svg-color--bd765f, #BD765F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ei1bt-b0e {
  stop-color: var(--svg-color--af725f, #AF725F);
  stop-opacity: 0;
}

.ez5ls3poe {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.f0lf6f3kb {
  stop-color: var(--svg-color--432633, #432633);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fspy8rbwh {
  stop-color: var(--svg-color--5a403d, #5A403D);
}

.ft5dv1b6b {
  fill: none;
}

.g75mbmjbv {
  stop-color: var(--svg-color--3c2827, #3C2827);
}

.gg3p-v-oi {
  stop-color: var(--svg-color--d56a42, #D56A42);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.go8dnjb_b {
  stop-color: var(--svg-color--d56a42, #D56A42);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hchmvbcwb {
  stop-color: var(--svg-color--af725f, #AF725F);
}

.heacg5ncs {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.hmx8eit6p {
  stop-color: var(--svg-color--f78d61, #F78D61);
  stop-opacity: 0;
}

.i_ux49j5u {
  d: path("M21.496 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.jvwpinbbf {
  cx: 24.833px;
  cy: 18.059px;
  r: 3.113px;
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kd9fr-txf {
  stop-color: var(--svg-color--d57852, #D57852);
  stop-opacity: 0;
}

.khbuz0hlc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.717c.802-.14 2.366-.1 3.449.742");
}

.l6wzmlbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.l9pefv81z {
  stop-color: var(--svg-color--422741, #422741);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.moyyndcqm {
  stop-color: var(--svg-color--bd765f, #BD765F);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n73l6to2h {
  cx: 7.092px;
  cy: 18.059px;
  r: 1.855px;
}

.naoj9jbij {
  stop-color: var(--svg-color--544340, #544340);
  stop-opacity: 0;
}

.ndh-ggbqf {
  stop-color: var(--svg-color--544340, #544340);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7liw8bnz {
  stop-color: var(--svg-color--ba7260, #BA7260);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.osc-jklcq {
  stop-color: var(--svg-color--371f28, #371F28);
}

.p71ln533h {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.pdv4ldbpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.39c1.217 0 2.245.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pup9lmq3m {
  stop-color: var(--svg-color--371f28, #371F28);
  stop-opacity: 0;
}

.pymlyd-1i {
  d: path("M11.87 15.897A1.664 1.664 0 0 0 10.266 18h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.q12lo_b7m {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.q1uq6hbwz {
  stop-color: var(--svg-color--ea8455, #EA8455);
}

.qh547r7uu {
  stop-color: var(--svg-color--5e433e, #5E433E);
}

.qu1cfg7_g {
  stop-color: var(--svg-color--573d3a, #573D3A);
}

.rkde3beof {
  stop-color: var(--svg-color--c26333, #C26333);
}

.s424eg2ut {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--463133, #463133);
}

.scckxcbxt {
  stop-color: var(--svg-color--573d3a, #573D3A);
  stop-opacity: 0;
}

.sdjph8tjs {
  stop-color: var(--svg-color--b97362, #B97362);
}

.sn-n94bif {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
}

.sow05c3ou {
  d: path("M13.39 17.366c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.t7o6ccjes {
  stop-color: var(--svg-color--d57852, #D57852);
}

.tqs3frbia {
  stop-color: var(--svg-color--5a403d, #5A403D);
  stop-opacity: 0;
}

.tzxi8pb6h {
  stop-color: var(--svg-color--f78d61, #F78D61);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uozffyiai {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.ut7qi9bnx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.vu7vn7bhc {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wcy0rhhon {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.239a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xhmtc9b9f {
  stop-color: var(--svg-color--b97362, #B97362);
  stop-opacity: 0;
}

.xk1wlybvw {
  cx: 11.367px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.xq483lxba {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y14k4lb6j {
  stop-color: var(--svg-color--523330, #523330);
}

.y7d3--b_f {
  d: path("m24.084 7.57l-5.739 1.913a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.ynsl3-bvt {
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1.03.513 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.ysuyqjbga {
  d: path("M20.013 15.898A1.664 1.664 0 0 1 21.617 18h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z20bumf_j {
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.z8b5eybgc {
  stop-color: var(--svg-color--bc613d, #BC613D);
}

.z98s40bed {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zk1gozblh {
  stop-color: var(--svg-color--ba7260, #BA7260);
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
