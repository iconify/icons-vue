<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#iFHAaOd)" class="nw837ienf"/><g filter="url(#iTFdSdM)"><path class="dz_r98b9z"/></g><ellipse fill="url(#iao9X3P)" class="udnl381ah"/><g filter="url(#iug1scb)"><path class="gzcg8-spf"/></g><path stroke="url(#iBIFkcd)" class="v0chqfbdg"/><g filter="url(#ifllpIb)"><path class="v5dw7qbiz"/></g><path stroke="url(#iHx5Tvr)" class="al2w6abjv"/><g filter="url(#iLdkOcc)"><path fill="url(#iyMxDGb)" class="s1tcqabrq"/><path fill="url(#ieR11Vd)" class="s1tcqabrq"/><path fill="url(#iTJUwie)" class="s1tcqabrq"/></g><path fill="url(#iASxJdb)" class="s5jo7lhyf"/><path fill="url(#i06BRne)" class="qtnozzbgo"/><path fill="url(#ioMHbme)" class="l79b4_b2p"/><path fill="url(#ihpyVxc)" class="csw5q4iku"/><path fill="url(#igpGBBN)" class="khjekl0nm"/><g filter="url(#icJp9pc)"><path fill="url(#i9gdY7F)" class="u0n3knlao"/></g><g filter="url(#ibWM4Ws)"><path fill="url(#iCRxlad)" class="u_81bhf6s"/></g><g filter="url(#i3cc6hd)"><path fill="url(#izJ0CWb)" class="xi9exmb-z"/></g><g filter="url(#i7WPpOg)"><path fill="url(#iRmeFsc)" class="nmri_sz4l"/></g><g filter="url(#iLOfJFc)"><path stroke="url(#iOTcsXd)" class="hdcknja1d"/></g><path fill="url(#i8Bb7Ne)" class="b0mfb2bvf"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iFHAaOd" cx="0" cy="0" r="1" gradientTransform="rotate(96.176 11.673 6.36)scale(33.6956)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="og2_-db3e"/><stop offset="1" class="shiawcbtg"/></radialGradient><radialGradient id="iao9X3P" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6997 11.7155 0 16 29.263)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iBIFkcd" cx="0" cy="0" r="1" gradientTransform="rotate(-88.301 17.163 -5.441)scale(7.92539 12.3133)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ccr58nbuz"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".401" class="ovz69fb_x"/></radialGradient><radialGradient id="iHx5Tvr" cx="0" cy="0" r="1" gradientTransform="matrix(-.23498 -7.9219 12.30789 -.36507 10.406 11.875)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ccr58nbuz"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".401" class="ovz69fb_x"/></radialGradient><radialGradient id="iyMxDGb" cx="0" cy="0" r="1" gradientTransform="rotate(136.865 7.615 11.92)scale(32.4636 32.2586)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="fgh-vhavg"/><stop offset=".614" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iTJUwie" cx="0" cy="0" r="1" gradientTransform="rotate(115.708 4.803 14.334)scale(20.7424 28.3094)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="glgshpbvw"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="i9gdY7F" cx="0" cy="0" r="1" gradientTransform="matrix(-.7979 -.16086 .18796 -.93235 18.555 23.964)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="iCRxlad" cx="0" cy="0" r="1" gradientTransform="matrix(-.7979 -.16086 .18796 -.93235 18.336 21.164)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="izJ0CWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7979 -.16086 .18796 -.93235 17.626 18.655)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="iRmeFsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7979 -.16086 .18796 -.93235 15.178 17.455)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="i8Bb7Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6064 1.04544 -1.09804 -1.68721 9.99 17.783)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="url071kgq"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><filter id="iTFdSdM" width="16.456" height="14.612" x="3.609" y="14.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation="1"/></filter><filter id="iug1scb" width="10.15" height="6.814" x="16.508" y="7.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation=".75"/></filter><filter id="ifllpIb" width="11.024" height="7.623" x="3.822" y="7.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation=".75"/></filter><filter id="iLdkOcc" width="15.643" height="15.822" x="5.738" y="14.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-2"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.08 0"/><feBlend in2="shape" result="effect1_innerShadow_6890_5229"/></filter><filter id="icJp9pc" width="2.311" height="2.565" x="17.599" y="22.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation=".25"/></filter><filter id="ibWM4Ws" width="2.311" height="2.565" x="17.38" y="19.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation=".25"/></filter><filter id="i3cc6hd" width="2.311" height="2.565" x="16.671" y="17.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation=".25"/></filter><filter id="i7WPpOg" width="2.311" height="2.565" x="14.221" y="16.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation=".25"/></filter><filter id="iLOfJFc" width="7.74" height="9.455" x="9.265" y="18.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6890_5229" stdDeviation=".75"/></filter><linearGradient id="ieR11Vd" x1="3.01" x2="8.199" y1="17.251" y2="17.115" gradientUnits="userSpaceOnUse"><stop offset=".328" class="zus2g1bwj"/><stop offset=".865" class="z016bf25m"/></linearGradient><linearGradient id="iASxJdb" x1="10.477" x2="13.05" y1="15.254" y2="18.392" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="i06BRne" x1="13.461" x2="14.435" y1="18.741" y2="19.945" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="ioMHbme" x1="14.905" x2="16.035" y1="20.307" y2="21.748" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="ihpyVxc" x1="16.644" x2="17.567" y1="22.493" y2="23.665" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="igpGBBN" x1="9.178" x2="8.602" y1="21.462" y2="21.094" gradientUnits="userSpaceOnUse"><stop offset=".307" class="we9tu7l_e"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="iOTcsXd" x1="9.999" x2="15.776" y1="20.846" y2="28.101" gradientUnits="userSpaceOnUse"><stop offset=".328" class="q0n-e9fcm"/><stop offset="1" class="ocwji7vfg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:yawning-face" /></template>
<style>
.al2w6abjv {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M7.272 11.689c1.532-2.047 4.125-2.547 6.266-1.344");
}

.b0mfb2bvf {
  d: path("M10.46 18.689c-.339.519-1.078.65-1.676.284s-.808-1.085-.468-1.604c.339-.518 1.099-.642 1.697-.275s.787 1.076.448 1.595");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.csw5q4iku {
  d: path("m15.315 25.02l1.227 1.722l1.475-1.105l.795-.621c.616-.46.716-1.326.222-1.914a1.4 1.4 0 0 0-.43-.343c-.257-.132-.557-.033-.779.153z");
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.dz_r98b9z {
  fill: var(--svg-color--be6b12, #BE6B12);
  d: path("M15.45 17.337a1.246 1.246 0 0 0-1.687-.36l-3.526 2.197l.388-.901c.269-.626-.037-1.348-.684-1.614c-.65-.267-1.397.029-1.662.66l-1.075 2.555l-1.165 1.984a1 1 0 0 0-.058.112c-.397.559-.492 2.164-.21 2.844c.812 2.625 2.458 1.79 4.854 2.093c1.054.133 2.308.524 3.138 0l3.411-1.619a1.2 1.2 0 0 0 .469-1.686a1.26 1.26 0 0 0-.665-.537l.506-.314a1.21 1.21 0 0 0 .374-1.71a1.28 1.28 0 0 0-.663-.503l.155-.097a1.21 1.21 0 0 0 .375-1.709a1.304 1.304 0 0 0-1.765-.376l-.576.358c.316-.384.358-.938.066-1.377");
}

.fgh-vhavg {
  stop-color: var(--svg-color--ffd43c, #FFD43C);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.glgshpbvw {
  stop-color: var(--svg-color--fd61c2, #FD61C2);
  stop-opacity: 0;
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.gzcg8-spf {
  stroke: var(--svg-color--dd8526, #DD8526);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M24.208 12.126c-.969-2.031-3.406-2.156-5.25-1.687");
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hdcknja1d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.515 20.971c.938.707 2.9 2.687 3.24 4.955");
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.khjekl0nm {
  d: path("m7.89 22.142l2.476-2.596c.543-1.528.136-1.927.043-2.096z");
}

.l79b4_b2p {
  d: path("M13.679 23.276c.017.293.302.728.519.965c.51.556 1.39.606 1.965.11l2.46-2.12c.576-.496.767-1.346.256-1.903a1.8 1.8 0 0 0-.392-.299c-.379-.225-.833-.102-1.17.182z");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nmri_sz4l {
  d: path("M15.656 18.072c-.328.122-.719-.116-.872-.53s-.013-.85.314-.97c.328-.122.719.115.872.53c.154.414.013.849-.315.97");
}

.nw837ienf {
  d: path("M16 29.999c9.334 0 13.999-6.267 13.999-13.999c0-7.73-4.665-13.999-13.999-13.999s-13.999 6.268-13.999 14c0 7.73 4.665 13.998 13.999 13.998");
}

.ocwji7vfg {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.q0n-e9fcm {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0.5;
}

.qtnozzbgo {
  d: path("M12.417 21.37a1.32 1.32 0 0 0 .163 1.575c.51.556 1.39.605 1.965.11l3.66-3.294a1.32 1.32 0 0 0 .118-1.905a1.423 1.423 0 0 0-1.966-.11l-.528.474c-.101.086-.276.262-.387.358z");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s1tcqabrq {
  d: path("M15.66 16.732a1.36 1.36 0 0 0-1.878-.105l-3.432 2.958l.266-1.037c.186-.72-.265-1.447-1.007-1.625c-.746-.18-1.5.265-1.681.99l-.731 2.933l-.923 2.334a2 2 0 0 0-.045.13a4.7 4.7 0 0 0-.489 2.224c.074 2.608 2.27 4.662 4.902 4.587a4.78 4.78 0 0 0 3.015-1.177l5.193-3.93c.61-.46.71-1.316.223-1.896a1.38 1.38 0 0 0-.806-.467l.492-.424a1.32 1.32 0 0 0 .118-1.905a1.4 1.4 0 0 0-.8-.432l.152-.13a1.32 1.32 0 0 0 .117-1.905a1.423 1.423 0 0 0-1.965-.11l-.56.483a1.26 1.26 0 0 0-.16-1.496");
}

.s5jo7lhyf {
  d: path("M13.755 16.632a1.37 1.37 0 0 1 1.89.11a1.27 1.27 0 0 1-.088 1.816l-4.56 4.088a1.333 1.333 0 0 1-1.808-.04l-.39-.379a.7.7 0 0 1-.015-.994l1.51-1.613z");
}

.shiawcbtg {
  stop-color: var(--svg-color--f68354, #F68354);
}

.t56wa9uix {
  stop-color: var(--svg-color--83480a, #83480A);
}

.u_81bhf6s {
  d: path("M18.814 21.78c-.328.122-.718-.116-.872-.53s-.013-.85.315-.971c.328-.122.718.116.872.53s.013.85-.315.971");
}

.u0n3knlao {
  d: path("M19.033 24.58c-.328.121-.718-.116-.872-.53s-.013-.85.315-.971c.328-.122.718.115.872.53c.153.414.012.849-.315.97");
}

.udnl381ah {
  cx: 16px;
  cy: 20.947px;
  rx: 5.766px;
  ry: 5.758px;
}

.url071kgq {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0.3;
}

.v0chqfbdg {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M25.226 11.689c-1.532-2.047-4.125-2.547-6.266-1.344");
}

.v5dw7qbiz {
  stroke: var(--svg-color--dd8526, #DD8526);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M6.272 13.126c1.717-2.562 4.28-3.031 6.124-2.562");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.we9tu7l_e {
  stop-color: var(--svg-color--e27f17, #E27F17);
  stop-opacity: 0.53;
}

.xi9exmb-z {
  d: path("M18.105 19.272c-.328.121-.718-.116-.872-.53s-.013-.85.315-.972c.328-.121.718.116.872.53s.013.85-.315.971");
}

.xus32fblm {
  stop-color: var(--svg-color--faf194, #FAF194);
  stop-opacity: 0.4;
}

.xw7_k5baw {
  stop-color: var(--svg-color--cd7313, #CD7313);
}

.z016bf25m {
  stop-color: var(--svg-color--fa9428, #FA9428);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zus2g1bwj {
  stop-color: var(--svg-color--ee891e, #EE891E);
}

</style>
