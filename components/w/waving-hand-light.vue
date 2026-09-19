<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nztezqbbi"/><path fill="url(#iCt5BQb)" class="ymcz05bgh"/><path fill="url(#iWX4eCb)" class="ymcz05bgh"/><path fill="url(#iiWU6Pd)" class="c77jgl0xp"/><path fill="url(#iFgdn3d)" class="c77jgl0xp"/><path fill="url(#idAuRmf)" class="c77jgl0xp"/><path fill="url(#i9QNUIb)" class="c77jgl0xp"/><path fill="url(#idlMIcb)" class="c77jgl0xp"/><path fill="url(#inWo0Pe)" class="w8ik5kb4l"/><path fill="url(#iCL77nT)" class="w8ik5kb4l"/><path fill="url(#iNAeUbe)" class="w8ik5kb4l"/><path fill="url(#iWFIkIz)" class="w8ik5kb4l"/><path fill="url(#i2Gxwtd)" class="w8ik5kb4l"/><g filter="url(#i2ij3ce)"><path class="wm1qk2b-r"/></g><path fill="url(#ivGhGFd)" class="rrrpenbho"/><path fill="url(#iEKPBme)" class="rrrpenbho"/><path fill="url(#iqfFVke)" class="rrrpenbho"/><g filter="url(#ib9ltqb)"><ellipse fill="url(#iuQwtCe)" transform="rotate(-29.74 28.164 11.32)" class="b6l-5mbrj"/></g><g filter="url(#iEvhQus)"><path class="u-vyseb6d"/></g><g filter="url(#io19iue)"><path fill="url(#iTA9CXk)" class="ho-p919zk"/></g><path fill="url(#icHIrCc)" class="wjpozccyw"/><path fill="url(#ijcnJPC)" class="wjpozccyw"/><path fill="url(#ipumQ6d)" class="wjpozccyw"/><path fill="url(#iVEykjc)" class="wjpozccyw"/><path fill="url(#ixgppoM)" class="h46ghk6cn"/><path fill="url(#ioNtOxc)" class="h46ghk6cn"/><g filter="url(#iM5jked)"><path class="xmyfb-lnz"/></g><g filter="url(#i70bJkd)"><path class="eagmvcclc"/></g><g filter="url(#izzBY5b)"><path stroke="url(#iwqqUJO)" class="hej7y5urj"/></g><g filter="url(#irJ8Bcb)"><path class="l3gxjyh7l"/><path stroke="url(#iRrEtpE)" class="z5pol9bvk"/></g><g filter="url(#iPHOJub)"><path class="q5mwj2bpq"/><path stroke="url(#iuXF37b)" class="c5f8q6bth"/></g><path stroke="url(#isJpAAc)" class="ivt52iv4f"/><path stroke="url(#iSsgKRT)" class="ivt52iv4f"/><path stroke="url(#iUsALte)" class="zjmnh5tuh"/><path stroke="url(#i2uWvgA)" class="zjmnh5tuh"/><g filter="url(#iZyqoSy)"><path class="dkds3gbmr"/></g><g filter="url(#iSIbque)"><path class="dqfuztb-r"/></g><defs><radialGradient id="iCt5BQb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71815 16.56953 -18.49756 -3.03443 23.65 14.495)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="uyowfwbfi"/><stop offset="1" class="xrbc3fbgy"/></radialGradient><radialGradient id="iiWU6Pd" cx="0" cy="0" r="1" gradientTransform="rotate(156.037 10.42 8.078)scale(4.10207 8.61847)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="lr79vlbed"/><stop offset="1" class="ie29-bxie"/></radialGradient><radialGradient id="iFgdn3d" cx="0" cy="0" r="1" gradientTransform="rotate(154.952 10.364 8.193)scale(5.1506 12.9593)" gradientUnits="userSpaceOnUse"><stop offset=".769" class="oh250pbjd"/><stop offset="1" class="sb6wk2byh"/></radialGradient><radialGradient id="i9QNUIb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.591 15.91 1.399)scale(3.72686 .79712)" gradientUnits="userSpaceOnUse"><stop class="jlzc1hmib"/><stop offset="1" class="irrsfmbkh"/></radialGradient><radialGradient id="idlMIcb" cx="0" cy="0" r="1" gradientTransform="rotate(84.463 6.569 13.732)scale(2.29203 2.86609)" gradientUnits="userSpaceOnUse"><stop class="b-yy833xw"/><stop offset="1" class="kwcymbcht"/></radialGradient><radialGradient id="inWo0Pe" cx="0" cy="0" r="1" gradientTransform="rotate(146.452 5.632 10.211)scale(3.50589 9.38314)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="b-05l3cyt"/><stop offset="1" class="ml8qh4bmo"/></radialGradient><radialGradient id="iCL77nT" cx="0" cy="0" r="1" gradientTransform="matrix(-3.875 2.43748 -6.52366 -10.37103 15.969 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="wmm0e_bzg"/><stop offset="1" class="t_12r5b8z"/></radialGradient><radialGradient id="iNAeUbe" cx="0" cy="0" r="1" gradientTransform="rotate(-32.681 36.166 -12.852)scale(3.93552 24.9102)" gradientUnits="userSpaceOnUse"><stop offset=".692" class="fv9b8e-wb"/><stop offset="1" class="w4z9hac_o"/></radialGradient><radialGradient id="i2Gxwtd" cx="0" cy="0" r="1" gradientTransform="matrix(.27556 2.28608 -2.69994 .32545 12.74 11.218)" gradientUnits="userSpaceOnUse"><stop class="qq6ywpb-h"/><stop offset="1" class="b6ax3lbyf"/></radialGradient><radialGradient id="ivGhGFd" cx="0" cy="0" r="1" gradientTransform="rotate(-77.656 23.9 -6.9)scale(5.26228 2.27148)" gradientUnits="userSpaceOnUse"><stop class="b8yyai6re"/><stop offset="1" class="f7px2jbjy"/></radialGradient><radialGradient id="iEKPBme" cx="0" cy="0" r="1" gradientTransform="rotate(5.452 -109.9 266.556)scale(.97611 3.53409)" gradientUnits="userSpaceOnUse"><stop class="d--bbkbqj"/><stop offset="1" class="mm2n7x1qf"/></radialGradient><radialGradient id="iqfFVke" cx="0" cy="0" r="1" gradientTransform="matrix(1.09943 1.78124 -6.44922 3.98063 25.8 9.171)" gradientUnits="userSpaceOnUse"><stop class="d--bbkbqj"/><stop offset="1" class="mm2n7x1qf"/></radialGradient><radialGradient id="iuQwtCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69946 .39095 -.54292 -2.3601 28.784 11.323)" gradientUnits="userSpaceOnUse"><stop class="lg7-j0bme"/><stop offset="1" class="hj5r_l0gb"/></radialGradient><radialGradient id="iTA9CXk" cx="0" cy="0" r="1" gradientTransform="rotate(113.948 8.56 19.112)scale(12.2413 6.11907)" gradientUnits="userSpaceOnUse"><stop class="a5lkoibji"/><stop offset="1" class="sfjtufb3d"/></radialGradient><radialGradient id="icHIrCc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74425 2.16183 -5.117 -8.86255 18.94 12.488)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="vypoye1-t"/><stop offset="1" class="bkve6yyho"/></radialGradient><radialGradient id="ijcnJPC" cx="0" cy="0" r="1" gradientTransform="rotate(155.961 8.086 8.249)scale(1.67667 10.6108)" gradientUnits="userSpaceOnUse"><stop class="vf1klmbbe"/><stop offset="1" class="impe11qjv"/></radialGradient><radialGradient id="iVEykjc" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 2.5 -2.76076 .31059 15.446 6.68)" gradientUnits="userSpaceOnUse"><stop class="div-dm-vd"/><stop offset="1" class="s32zvbb3b"/></radialGradient><radialGradient id="ixgppoM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15624 .96876 -3.28463 -3.9203 14.313 18.547)" gradientUnits="userSpaceOnUse"><stop class="ufyarqbls"/><stop offset="1" class="z_91umbnv"/></radialGradient><radialGradient id="ioNtOxc" cx="0" cy="0" r="1" gradientTransform="matrix(.2813 2.1063 -2.74727 .36691 11.12 15.872)" gradientUnits="userSpaceOnUse"><stop class="ykn1odbpg"/><stop offset="1" class="gfu2ke2_j"/></radialGradient><radialGradient id="iRrEtpE" cx="0" cy="0" r="1" gradientTransform="matrix(1.54687 -1.53125 3.91781 3.95778 22.844 5.469)" gradientUnits="userSpaceOnUse"><stop class="kzdh98h8q"/><stop offset=".744" class="t68_d7h5n"/></radialGradient><radialGradient id="iuXF37b" cx="0" cy="0" r="1" gradientTransform="matrix(1.6667 -1.60486 4.1034 4.26156 20.83 7.183)" gradientUnits="userSpaceOnUse"><stop class="kzdh98h8q"/><stop offset=".862" class="t68_d7h5n"/></radialGradient><radialGradient id="iSsgKRT" cx="0" cy="0" r="1" gradientTransform="rotate(164.814 1.832 9.818)scale(2.26665 6.09358)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l96_08dtf"/><stop offset="1" class="mes48ob5k"/></radialGradient><radialGradient id="i2uWvgA" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08905 .55293 -1.45444 -5.4951 4.177 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l96_08dtf"/><stop offset="1" class="mes48ob5k"/></radialGradient><filter id="i2ij3ce" width="5.595" height="8.26" x="11.937" y="11.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".375"/></filter><filter id="ib9ltqb" width="2.735" height="3.069" x="26.797" y="9.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".25"/></filter><filter id="iEvhQus" width="6.259" height="7.813" x="22.905" y="14.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".5"/></filter><filter id="io19iue" width="6.88" height="14" x="23.281" y="15.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".75"/></filter><filter id="iM5jked" width="11.875" height="11.063" x="13" y="13.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".75"/></filter><filter id="i70bJkd" width="7.072" height="11.259" x="18.112" y="5.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".6"/></filter><filter id="izzBY5b" width="4.444" height="6.709" x="20.09" y="9.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".35"/></filter><filter id="irJ8Bcb" width="5.549" height="6.363" x="20.362" y="2.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.337255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1078"/></filter><filter id="iPHOJub" width="5.902" height="6.621" x="18.191" y="3.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.337255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1078"/></filter><filter id="iZyqoSy" width="5.285" height="6.928" x="10.346" y="16.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".375"/></filter><filter id="iSIbque" width="6.281" height="10.797" x="14.5" y="6.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1078" stdDeviation=".5"/></filter><linearGradient id="iWX4eCb" x1="14.754" x2="11.138" y1="22.627" y2="25.49" gradientUnits="userSpaceOnUse"><stop class="uyowfwbfi"/><stop offset="1" class="xrbc3fbgy"/></linearGradient><linearGradient id="idAuRmf" x1="20.547" x2="20.14" y1="16.667" y2="14.562" gradientUnits="userSpaceOnUse"><stop class="fbjwdq0st"/><stop offset="1" class="a64jmnqyu"/></linearGradient><linearGradient id="iWFIkIz" x1="16.813" x2="15.094" y1="19.359" y2="18.453" gradientUnits="userSpaceOnUse"><stop class="fbjwdq0st"/><stop offset="1" class="a64jmnqyu"/></linearGradient><linearGradient id="ipumQ6d" x1="17.656" x2="16.797" y1="17.969" y2="15.328" gradientUnits="userSpaceOnUse"><stop class="fbjwdq0st"/><stop offset="1" class="a64jmnqyu"/></linearGradient><linearGradient id="iwqqUJO" x1="23.5" x2="21.031" y1="14.797" y2="10.391" gradientUnits="userSpaceOnUse"><stop class="t5xnb9bze"/><stop offset="1" class="hb--lkbee"/></linearGradient><linearGradient id="isJpAAc" x1="5.469" x2="8.656" y1="16.195" y2="22.828" gradientUnits="userSpaceOnUse"><stop class="norwhxbmc"/><stop offset="1" class="ez4l67b7b"/></linearGradient><linearGradient id="iUsALte" x1="3.505" x2="7.247" y1="18.063" y2="26.183" gradientUnits="userSpaceOnUse"><stop offset=".298" class="norwhxbmc"/><stop offset="1" class="ez4l67b7b"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waving-hand-light" /></template>
<style>
.a5lkoibji {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
}

.a64jmnqyu {
  stop-color: var(--svg-color--f5bfae, #F5BFAE);
  stop-opacity: 0;
}

.b-05l3cyt {
  stop-color: var(--svg-color--e2a693, #E2A693);
  stop-opacity: 0;
}

.b-yy833xw {
  stop-color: var(--svg-color--e3b79c, #E3B79C);
}

.b6ax3lbyf {
  stop-color: var(--svg-color--daaa90, #DAAA90);
  stop-opacity: 0;
}

.b6l-5mbrj {
  cx: 28.164px;
  cy: 11.32px;
  rx: 0.773px;
  ry: 1.106px;
}

.b8yyai6re {
  stop-color: var(--svg-color--ebb5a5, #EBB5A5);
}

.bkve6yyho {
  stop-color: var(--svg-color--e2a085, #E2A085);
}

.c5f8q6bth {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M18.64 4.207c1.75.059 5.016 1.574 4.899 5.621");
}

.c77jgl0xp {
  d: path("M17.056 8.263c.029.248.102.566.252.956q.097.257.237.643c.419 1.227 1.206 3.308 2.25 5.21c.393.716 1.11 1.22 1.927 1.181c1.076-.05 2.312-.405 2.786-1.464l-.003-.01l-.023.06c-1.077-1.494-2.527-4.8-3.327-7.123a2.09 2.09 0 0 0-4.099.547");
}

.d--bbkbqj {
  stop-color: var(--svg-color--d3987e, #D3987E);
}

.div-dm-vd {
  stop-color: var(--svg-color--ddad92, #DDAD92);
}

.dkds3gbmr {
  fill: var(--svg-color--ffd6c0, #FFD6C0);
  d: path("M14.739 22.893a54 54 0 0 1-3.514-4.318a.696.696 0 0 1 .14-.953a.72.72 0 0 1 1.011.112l2.504 3.113c.012.9-.089 1.74-.141 2.046");
}

.dqfuztb-r {
  stroke: var(--svg-color--fdcbb6, #FDCBB6);
  stroke-linecap: round;
  d: path("M16 8.484c.323 1.125 1.76 5.365 3.281 7.797");
}

.eagmvcclc {
  stroke: var(--svg-color--ffe4c9, #FFE4C9);
  stroke-linecap: round;
  d: path("M19.813 7.39c.53 2.282 2.515 6.079 3.671 7.86");
}

.ez4l67b7b {
  stop-color: var(--svg-color--0d5194, #0D5194);
}

.f7px2jbjy {
  stop-color: var(--svg-color--ebb5a5, #EBB5A5);
  stop-opacity: 0;
}

.fbjwdq0st {
  stop-color: var(--svg-color--f5bfae, #F5BFAE);
}

.ft5dv1b6b {
  fill: none;
}

.fv9b8e-wb {
  stop-color: var(--svg-color--d59271, #D59271);
  stop-opacity: 0;
}

.gfu2ke2_j {
  stop-color: var(--svg-color--dca990, #DCA990);
  stop-opacity: 0;
}

.h46ghk6cn {
  d: path("M11.478 16.414a2.067 2.067 0 0 0-2.276 3.216c1.004 1.503 2.7 3.629 4.616 5.687c2.378-1.114 2.166-3.38 1.76-3.861c-.007.022-2.024-2.79-3.004-4.034l-.049-.062c-.303-.387-.666-.85-1.04-.946c-.145-.265-.146-.272-.007 0");
}

.hb--lkbee {
  stop-color: var(--svg-color--fdccb8, #FDCCB8);
  stop-opacity: 0;
}

.hej7y5urj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-7px, 0.7px);
  d: path("M21.14 10.438c.344.802 1.17 2.909 2.344 4.609");
}

.hj5r_l0gb {
  stop-color: var(--svg-color--ffe2c7, #FFE2C7);
  stop-opacity: 0;
}

.ho-p919zk {
  d: path("M24.845 16.936c.506.759 2.301 1.622 3.405 1.86c.458 1.22 1.219 6.813-2.156 9.032c.785-1.374 1.335-6.449-1.25-10.892");
}

.ie29-bxie {
  stop-color: var(--svg-color--e1a696, #E1A696);
}

.impe11qjv {
  stop-color: var(--svg-color--e1a086, #E1A086);
  stop-opacity: 0;
}

.irrsfmbkh {
  stop-color: var(--svg-color--c8947a, #C8947A);
  stop-opacity: 0;
}

.ivt52iv4f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M4.379 16.195c-.2 2.47 1.191 5.22 4.676 5.797");
}

.jlzc1hmib {
  stop-color: var(--svg-color--c8947a, #C8947A);
}

.kwcymbcht {
  stop-color: var(--svg-color--e3b79c, #E3B79C);
  stop-opacity: 0;
}

.kzdh98h8q {
  stop-color: var(--svg-color--16579c, #16579C);
}

.l3gxjyh7l {
  stroke: var(--svg-color--1b99e7, #1B99E7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M20.812 2.629c1.758.125 4.641 1.598 4.547 5.363");
}

.l96_08dtf {
  stop-color: var(--svg-color--0e5196, #0E5196);
  stop-opacity: 0;
}

.lg7-j0bme {
  stop-color: var(--svg-color--ffe2c7, #FFE2C7);
}

.lr79vlbed {
  stop-color: var(--svg-color--e1a696, #E1A696);
  stop-opacity: 0;
}

.mes48ob5k {
  stop-color: var(--svg-color--0e5196, #0E5196);
}

.ml8qh4bmo {
  stop-color: var(--svg-color--e2a693, #E2A693);
}

.mm2n7x1qf {
  stop-color: var(--svg-color--d3987e, #D3987E);
  stop-opacity: 0;
}

.norwhxbmc {
  stop-color: var(--svg-color--1679c5, #1679C5);
}

.nztezqbbi {
  fill: var(--svg-color--f5bfae, #F5BFAE);
  d: path("M19.145 6.2a2.09 2.09 0 0 1 2.01 1.516c.8 2.323 2.25 5.629 3.327 7.123a7 7 0 0 0 .389-1.652c.02-.188.152-1.41.336-1.956c.221-.658.678-1.224 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.053.162.08.326c.13.56.04 1.073-.014 1.412a61 61 0 0 0-.359 2.625a19.6 19.6 0 0 0 .125 4.781c.3 1.413.219 2.912.14 3.485c-.86 6.31-7.847 6.78-9.812 5.85c-1.339-.435-2.758-1.47-4.71-3.468c-2.283-2.335-4.368-4.905-5.529-6.643a2.067 2.067 0 0 1 2.276-3.216c-.377-.735-.68-1.377-.917-2.087a2.067 2.067 0 0 1 3.534-2.007c-.12-.267-.835-2.032-.96-2.854a2.089 2.089 0 0 1 6.01-3.266");
}

.oh250pbjd {
  stop-color: var(--svg-color--df9e84, #DF9E84);
  stop-opacity: 0;
}

.q5mwj2bpq {
  stroke: var(--svg-color--1b99e7, #1B99E7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M18.64 4.207c1.75.059 5.016 1.574 4.899 5.621");
}

.qq6ywpb-h {
  stop-color: var(--svg-color--daaa90, #DAAA90);
}

.rrrpenbho {
  d: path("m24.478 14.834l.004.005c.19-.492.329-1.11.389-1.652l.002-.018c.026-.238.156-1.407.334-1.938c.221-.658.678-1.224 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.053.163.08.326c.126.538.047 1.034-.007 1.373l-.006.039a61 61 0 0 0-.36 2.625c-.094.9-.153 2.327.02 3.967c-2.27.437-3.664-.998-4.135-1.826c-.509-.896-.614-2.598-.395-2.932");
}

.s32zvbb3b {
  stop-color: var(--svg-color--ddad92, #DDAD92);
  stop-opacity: 0;
}

.sb6wk2byh {
  stop-color: var(--svg-color--df9e84, #DF9E84);
}

.sfjtufb3d {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
  stop-opacity: 0;
}

.t_12r5b8z {
  stop-color: var(--svg-color--e09e7e, #E09E7E);
}

.t5xnb9bze {
  stop-color: var(--svg-color--fdccb8, #FDCCB8);
}

.t68_d7h5n {
  stop-color: var(--svg-color--16579c, #16579C);
  stop-opacity: 0;
}

.u-vyseb6d {
  fill: var(--svg-color--fcc8b3, #FCC8B3);
  d: path("M28.164 19.484a4.5 4.5 0 0 1-3.5-4.062c-.469.208-1 1.86-.64 2.969c.702 2.17 2.984 2.823 3.609 2.843z");
}

.ufyarqbls {
  stop-color: var(--svg-color--f2b69c, #F2B69C);
}

.uyowfwbfi {
  stop-color: var(--svg-color--ba7d94, #BA7D94);
  stop-opacity: 0;
}

.vf1klmbbe {
  stop-color: var(--svg-color--e1a086, #E1A086);
}

.vypoye1-t {
  stop-color: var(--svg-color--e2a085, #E2A085);
  stop-opacity: 0;
}

.w4z9hac_o {
  stop-color: var(--svg-color--d59271, #D59271);
}

.w8ik5kb4l {
  d: path("M10.565 14.327a2.067 2.067 0 0 1 3.514-2.03c1.034 2.086 2.309 4.519 3.276 5.937c-1.23 1.672-1.526 2.516-1.78 3.235c-.782-1.089-2.416-3.305-3-4.047c-.314-.398-.696-.906-1.09-1.008a13 13 0 0 1-.92-2.087");
}

.wjpozccyw {
  d: path("M13.994 12.081c.745 1.601 1.672 3.594 2.832 5.315c.207.308.58.464.924.325a5.2 5.2 0 0 0 2.047-1.542c.238-.297.23-.71.045-1.042c-.842-1.505-2.043-4.166-2.799-6.876a2.067 2.067 0 0 0-3.908 1.205c.104.688.623 2.037.859 2.615");
}

.wm1qk2b-r {
  fill: var(--svg-color--ffd6c0, #FFD6C0);
  d: path("M16.177 19.5c-1.701-2.814-2.796-4.85-3.41-5.896a.577.577 0 0 1 .167-.768a.555.555 0 0 1 .792.182l1.369 2.377l1.686 3.058c-.187.5-.406.89-.604 1.047");
}

.wmm0e_bzg {
  stop-color: var(--svg-color--e09e7e, #E09E7E);
  stop-opacity: 0;
}

.xmyfb-lnz {
  fill: var(--svg-color--f0bba4, #F0BBA4);
  d: path("M14.515 22.582a.5.5 0 0 0 .97.242zm8.394-6.443a.5.5 0 1 0-.068-.997zm-7.424 6.685c.291-1.165 1.09-2.777 2.36-4.13c1.264-1.35 2.966-2.41 5.064-2.555l-.068-.997c-2.415.166-4.338 1.387-5.726 2.867c-1.383 1.475-2.266 3.238-2.6 4.573z");
}

.xrbc3fbgy {
  stop-color: var(--svg-color--ba7d94, #BA7D94);
}

.ykn1odbpg {
  stop-color: var(--svg-color--dca990, #DCA990);
}

.ymcz05bgh {
  d: path("M19.145 6.2a2.09 2.09 0 0 1 2.01 1.516c.8 2.323 2.25 5.629 3.327 7.123a7 7 0 0 0 .389-1.652c.02-.188.152-1.41.336-1.956c.221-.658.678-1.224 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.053.162.08.326c.13.56.04 1.073-.014 1.412a61 61 0 0 0-.359 2.625a19.6 19.6 0 0 0 .125 4.781c.3 1.413.219 2.912.14 3.485c-.86 6.31-7.847 6.78-9.812 5.85c-1.339-.435-2.758-1.47-4.71-3.468c-2.283-2.335-4.368-4.905-5.529-6.643a2.067 2.067 0 0 1 2.276-3.216c-.377-.735-.68-1.377-.917-2.087a2.067 2.067 0 0 1 3.534-2.007c-.12-.267-.835-2.032-.96-2.854a2.089 2.089 0 0 1 6.01-3.266");
}

.z_91umbnv {
  stop-color: var(--svg-color--f2b69c, #F2B69C);
  stop-opacity: 0;
}

.z5pol9bvk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M20.812 2.629c1.758.125 4.641 1.598 4.547 5.363");
}

.zjmnh5tuh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M2.469 18.063c-.235 2.468 1.398 4.984 4.46 5.398");
}

</style>
