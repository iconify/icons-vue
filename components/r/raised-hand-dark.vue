<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="i8qvkeuun"/><path fill="url(#i45iBsc)" class="d14ov9bcx"/><path fill="url(#iPkpwPd)" class="d14ov9bcx"/><path fill="url(#izaUbec)" class="d14ov9bcx"/><path fill="url(#iJnBwmb)" class="d14ov9bcx"/><path fill="url(#i5QY45N)" class="d14ov9bcx"/><path fill="url(#iQEPlgH)" class="zmn3mpbji"/><path fill="url(#iyihMQe)" class="zmn3mpbji"/><path fill="url(#ilVEadd)" class="zmn3mpbji"/><g filter="url(#icJsrQh)"><path class="a5e8m_qbg"/></g><path fill="url(#ihKz18c)" class="u8rgtwhda"/><path fill="url(#iDgOLoe)" class="u8rgtwhda"/><path fill="url(#iHvGGxc)" class="u8rgtwhda"/><path fill="url(#iZDGbje)" class="u8rgtwhda"/><g filter="url(#iqjHzte)"><path class="m8e8rve3a"/></g><path fill="url(#igmMIoc)" class="e8nvnwb0l"/><path fill="url(#iMdElYc)" class="e8nvnwb0l"/><path fill="url(#ikMekgd)" class="e8nvnwb0l"/><path fill="url(#iIBHK1e)" class="e8nvnwb0l"/><g filter="url(#i56Xrbe)"><path class="bwrz18mnq"/></g><path fill="url(#iFEvQ4g)" class="ov0jz3bsg"/><path fill="url(#ifWcESd)" class="ov0jz3bsg"/><path fill="url(#iYh1whd)" class="ov0jz3bsg"/><g filter="url(#ixci53l)"><path class="tyd2sbc-a"/></g><path fill="url(#ipUK6rb)" class="k7np98bul"/><path fill="url(#iBwvSws)" class="d14ov9bcx"/><path fill="url(#ip50MGe)" class="d14ov9bcx"/><path fill="url(#inywgqb)" class="d14ov9bcx"/><path fill="url(#iijzu2d)" class="d14ov9bcx"/><path fill="url(#iBSgSsd)" class="jmtiz8b1f"/><g filter="url(#igfR6ib)"><path stroke="url(#iajmKOd)" class="ykwbklbmi"/></g><g filter="url(#iKgUSFc)"><path stroke="url(#ij30yEe)" class="zbpb9jvxv"/></g><g filter="url(#is6voub)"><path stroke="url(#ieidLGe)" class="tviy62b6d"/></g><g filter="url(#iW1sIOt)"><path stroke="url(#isQdHHe)" class="aj10tcc5j"/></g><g filter="url(#izCcdUA)"><path stroke="url(#iL3XJWd)" class="vciz70bvv"/></g><g filter="url(#iax8wFr)"><path fill="url(#iYJsvke)" class="bqdwa73qe"/></g><defs><radialGradient id="i45iBsc" cx="0" cy="0" r="1" gradientTransform="rotate(161.868 11.695 10.853)scale(20.6992 31.5601)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="ezlfynhrn"/><stop offset="1" class="v0evrfpzt"/></radialGradient><radialGradient id="iPkpwPd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.81574 24.215 -16.71615 -4.01473 18.376 7.908)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="r-ag40bgp"/><stop offset="1" class="tt7eg3bmb"/></radialGradient><radialGradient id="izaUbec" cx="0" cy="0" r="1" gradientTransform="rotate(-117.318 19.507 8.448)scale(8.58217 10.8072)" gradientUnits="userSpaceOnUse"><stop class="ot534kb2d"/><stop offset="1" class="vodpp_ldn"/></radialGradient><radialGradient id="iJnBwmb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.2764 22.703 -15.67234 -2.26177 17.014 7.905)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="szxk_5rol"/><stop offset="1" class="ogljt3byp"/></radialGradient><radialGradient id="i5QY45N" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -1 4.27933 -6.01781 27.227 18.123)" gradientUnits="userSpaceOnUse"><stop class="bjvg8d-bk"/><stop offset="1" class="bur_fqbxn"/></radialGradient><radialGradient id="ilVEadd" cx="0" cy="0" r="1" gradientTransform="rotate(87.826 .108 7.566)scale(2.17344 5.42725)" gradientUnits="userSpaceOnUse"><stop class="tp6n4fzof"/><stop offset="1" class="j4n9yibxg"/></radialGradient><radialGradient id="iZDGbje" cx="0" cy="0" r="1" gradientTransform="rotate(77.964 3.171 8.758)scale(3.35183 5.94373)" gradientUnits="userSpaceOnUse"><stop class="ekoq87n-x"/><stop offset="1" class="nzibwv97f"/></radialGradient><radialGradient id="iIBHK1e" cx="0" cy="0" r="1" gradientTransform="rotate(-116.651 12.782 -.314)scale(9.71133 11.3986)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="h_dl52bpu"/><stop offset="1" class="k9pf56bxo"/></radialGradient><radialGradient id="iYh1whd" cx="0" cy="0" r="1" gradientTransform="rotate(-113.761 16.345 -.403)scale(10.8875 11.755)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="lfy25fb4x"/><stop offset="1" class="dllwv2bqg"/></radialGradient><radialGradient id="ipUK6rb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21602 1.37466 -5.26167 4.65448 23.188 13.566)" gradientUnits="userSpaceOnUse"><stop class="n3akuff4o"/><stop offset="1" class="kwfvq_byo"/></radialGradient><radialGradient id="iBwvSws" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79397 2.08686 -1.22257 -1.05098 27.987 13.566)" gradientUnits="userSpaceOnUse"><stop class="l_3w1myze"/><stop offset="1" class="cv7wwgeqb"/></radialGradient><radialGradient id="ip50MGe" cx="0" cy="0" r="1" gradientTransform="rotate(130.365 10.185 7.68)scale(2.77561 2.99718)" gradientUnits="userSpaceOnUse"><stop class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></radialGradient><radialGradient id="inywgqb" cx="0" cy="0" r="1" gradientTransform="rotate(112.533 8.291 7.278)scale(2.69033 2.84931)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></radialGradient><radialGradient id="iijzu2d" cx="0" cy="0" r="1" gradientTransform="rotate(122.8 4.5 6.313)scale(1.41523 1.65613)" gradientUnits="userSpaceOnUse"><stop class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></radialGradient><radialGradient id="iBSgSsd" cx="0" cy="0" r="1" gradientTransform="rotate(120.411 1.478 6.834)scale(1.41004 1.52259)" gradientUnits="userSpaceOnUse"><stop class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></radialGradient><radialGradient id="iYJsvke" cx="0" cy="0" r="1" gradientTransform="rotate(144.625 8.842 11.22)scale(3.83256 5.45389)" gradientUnits="userSpaceOnUse"><stop class="vgntnsbqz"/><stop offset="1" class="c5l6kybhp"/></radialGradient><linearGradient id="iQEPlgH" x1="10.141" x2="8.82" y1="11.224" y2="11.217" gradientUnits="userSpaceOnUse"><stop class="pw2wixnzv"/><stop offset="1" class="nanduho6s"/></linearGradient><linearGradient id="iyihMQe" x1="9.715" x2="9.108" y1="13.834" y2="12.964" gradientUnits="userSpaceOnUse"><stop class="bunp3ab1x"/><stop offset="1" class="mgppfsfvp"/></linearGradient><linearGradient id="ihKz18c" x1="14.383" x2="13.07" y1="9.405" y2="9.498" gradientUnits="userSpaceOnUse"><stop class="j_ky0nb9p"/><stop offset="1" class="q6czmub6c"/></linearGradient><linearGradient id="iDgOLoe" x1="9.378" x2="11.775" y1="10.383" y2="10.262" gradientUnits="userSpaceOnUse"><stop class="pte74toty"/><stop offset="1" class="ub7gi2bmx"/></linearGradient><linearGradient id="iHvGGxc" x1="11.91" x2="11.016" y1="14.981" y2="11.675" gradientUnits="userSpaceOnUse"><stop offset=".405" class="bunp3ab1x"/><stop offset="1" class="mgppfsfvp"/></linearGradient><linearGradient id="igmMIoc" x1="13.983" x2="16.078" y1="8.227" y2="8.122" gradientUnits="userSpaceOnUse"><stop class="unuyjut0u"/><stop offset="1" class="kx08u4ydv"/></linearGradient><linearGradient id="iMdElYc" x1="18.308" x2="17.465" y1="8.498" y2="8.489" gradientUnits="userSpaceOnUse"><stop class="xdu91mb0m"/><stop offset="1" class="wiibt-xil"/></linearGradient><linearGradient id="ikMekgd" x1="16.078" x2="16.078" y1="13.648" y2="11.841" gradientUnits="userSpaceOnUse"><stop offset=".348" class="bunp3ab1x"/><stop offset="1" class="mgppfsfvp"/></linearGradient><linearGradient id="iFEvQ4g" x1="17.918" x2="20.563" y1="10.502" y2="10.596" gradientUnits="userSpaceOnUse"><stop class="euu3n7elf"/><stop offset="1" class="ld_cxyysk"/></linearGradient><linearGradient id="ifWcESd" x1="19.316" x2="20.226" y1="14.414" y2="12.659" gradientUnits="userSpaceOnUse"><stop class="bunp3ab1x"/><stop offset="1" class="mgppfsfvp"/></linearGradient><linearGradient id="iajmKOd" x1="27.327" x2="22.824" y1="15.104" y2="21.511" gradientUnits="userSpaceOnUse"><stop class="ztd0e99bh"/><stop offset="1" class="ccgji1bxi"/></linearGradient><linearGradient id="ij30yEe" x1="10.154" x2="8.883" y1="14.874" y2="17.487" gradientUnits="userSpaceOnUse"><stop class="f33i6dbme"/><stop offset="1" class="sddksqb5q"/></linearGradient><linearGradient id="ieidLGe" x1="14.395" x2="14.054" y1="12.978" y2="14.322" gradientUnits="userSpaceOnUse"><stop class="f33i6dbme"/><stop offset="1" class="sddksqb5q"/></linearGradient><linearGradient id="isQdHHe" x1="18.223" x2="18.065" y1="13.313" y2="13.819" gradientUnits="userSpaceOnUse"><stop class="f33i6dbme"/><stop offset="1" class="sddksqb5q"/></linearGradient><linearGradient id="iL3XJWd" x1="22.516" x2="23.023" y1="15.203" y2="15.941" gradientUnits="userSpaceOnUse"><stop class="f33i6dbme"/><stop offset="1" class="sddksqb5q"/></linearGradient><filter id="icJsrQh" width="4.609" height="10.585" x="6.016" y="7.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".5"/></filter><filter id="iqjHzte" width="4.647" height="11.076" x="10.224" y="3.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".5"/></filter><filter id="i56Xrbe" width="3.365" height="12.11" x="15.455" y="2.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".5"/></filter><filter id="ixci53l" width="3.365" height="12.11" x="20.089" y="4.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".5"/></filter><filter id="igfR6ib" width="7.344" height="8.406" x="21.257" y="12.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".5"/></filter><filter id="iKgUSFc" width="3.344" height="3.406" x="7.297" y="13.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".25"/></filter><filter id="is6voub" width="3.656" height="2.594" x="11.266" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".25"/></filter><filter id="iW1sIOt" width="3.794" height="1.975" x="14.937" y="12.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".25"/></filter><filter id="izCcdUA" width="2.438" height="2.906" x="20.656" y="14.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".25"/></filter><filter id="iax8wFr" width="5.031" height="5.219" x="17.844" y="13.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1476" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-hand-dark" /></template>
<style>
.a5e8m_qbg {
  fill: var(--svg-color--624e4d, #624E4D);
  d: path("M8.11 9.51c-.1-1.07-.64-1.297-1.094-1.297c1.219-.53 2.125.188 2.219 1.297l.39 5.188l-1.953 1.922l.766-2.188c0-1.23-.234-3.922-.328-4.922");
}

.aj10tcc5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.688 13.078c.609.313 1.64.578 2.294.436");
}

.bjvg8d-bk {
  stop-color: var(--svg-color--4c3133, #4C3133);
}

.bqdwa73qe {
  d: path("M22.375 15.297c-1.75-.013-3.427-1.052-3.969-1.5c-.4 2.162 1.24 3.765 2.078 4.219z");
}

.bunp3ab1x {
  stop-color: var(--svg-color--4d3233, #4D3233);
}

.bur_fqbxn {
  stop-color: var(--svg-color--4c3133, #4C3133);
  stop-opacity: 0;
}

.bwrz18mnq {
  fill: var(--svg-color--5a4746, #5A4746);
  d: path("M16.455 3.102v10.11h1.203c.054-2.124.162-6.75.162-8.258s-.91-1.863-1.365-1.852");
}

.c5l6kybhp {
  stop-color: var(--svg-color--5e4b4a, #5E4B4A);
  stop-opacity: 0;
}

.ccgji1bxi {
  stop-color: var(--svg-color--5f4143, #5F4143);
  stop-opacity: 0;
}

.cv7wwgeqb {
  stop-color: var(--svg-color--665250, #665250);
  stop-opacity: 0;
}

.d14ov9bcx {
  d: path("M13.652 4.547a2.416 2.416 0 0 1 4.83-.114l.023.973a2.407 2.407 0 0 1 4.5 1.26l-.255 8.254l1.45-1.799a2.516 2.516 0 0 1 3.919 3.158l-.623.773l-.006.01a45 45 0 0 0-3.216 4.663c-.475.712-.887 1.472-1.299 2.231c-.587 1.082-1.172 2.162-1.934 3.094a8.25 8.25 0 0 1-6.424 3.063a8.26 8.26 0 0 1-7.276-4.341l-.005.008c-1.273-2.282-1.46-4.805-1.523-6.157l-.137-2.442a2 2 0 0 1-.016-.19l-.305-7.19a2.332 2.332 0 0 1 4.071-1.65L9.38 6.746a2.34 2.34 0 0 1 4.293-1.369z");
}

.dllwv2bqg {
  stop-color: var(--svg-color--4d4342, #4D4342);
}

.e8nvnwb0l {
  d: path("M18.24 6.378c0-.458.166-.864.264-.977v-.004l-.022-.964a2.416 2.416 0 1 0-4.83.114l.02.83c.294.529.31 1.133.324 1.724c.045 1.81.27 4.172.387 5.98h3.736c.026-1.967.12-6.06.12-6.703");
}

.ekoq87n-x {
  stop-color: var(--svg-color--443634, #443634);
}

.euu3n7elf {
  stop-color: var(--svg-color--2b1717, #2B1717);
}

.ezlfynhrn {
  stop-color: var(--svg-color--372127, #372127);
  stop-opacity: 0;
}

.f33i6dbme {
  stop-color: var(--svg-color--6c5958, #6C5958);
}

.ft5dv1b6b {
  fill: none;
}

.h_dl52bpu {
  stop-color: var(--svg-color--453634, #453634);
  stop-opacity: 0;
}

.i8qvkeuun {
  fill: var(--svg-color--4d3233, #4D3233);
  d: path("M13.652 4.547a2.416 2.416 0 0 1 4.83-.114l.023.973a2.407 2.407 0 0 1 4.5 1.26l-.255 8.254l1.45-1.799a2.516 2.516 0 0 1 3.919 3.158l-.623.773l-.006.01a45 45 0 0 0-3.216 4.663c-.475.712-.887 1.472-1.299 2.231c-.587 1.082-1.172 2.162-1.934 3.094a8.25 8.25 0 0 1-6.424 3.063a8.26 8.26 0 0 1-7.276-4.341l-.005.008c-1.273-2.282-1.46-4.805-1.523-6.157l-.137-2.442a2 2 0 0 1-.016-.19l-.305-7.19a2.332 2.332 0 0 1 4.071-1.65L9.38 6.746a2.34 2.34 0 0 1 4.293-1.369z");
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.j_ky0nb9p {
  stop-color: var(--svg-color--392321, #392321);
}

.j4n9yibxg {
  stop-color: var(--svg-color--4b3936, #4B3936);
  stop-opacity: 0;
}

.jmtiz8b1f {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M13.652 4.547a2.416 2.416 0 0 1 4.83-.114l.023.973a2.407 2.407 0 0 1 4.5 1.26l-.255 8.254l1.45-1.799a2.516 2.516 0 0 1 3.919 3.158l-.623.773l-.006.01a45 45 0 0 0-3.216 4.663c-.475.712-.887 1.472-1.299 2.231c-.587 1.082-1.172 2.162-1.934 3.094a8.25 8.25 0 0 1-6.424 3.063a8.26 8.26 0 0 1-7.276-4.341l-.005.008c-1.273-2.282-1.46-4.805-1.523-6.157l-.137-2.442a2 2 0 0 1-.016-.19l-.305-7.19a2.332 2.332 0 0 1 4.071-1.65L9.38 6.746a2.34 2.34 0 0 1 4.293-1.369z");
}

.k7np98bul {
  d: path("M22.875 14.766L24.2 13.12a2.516 2.516 0 0 1 3.918 3.158l-.623.773l-.006.01a45 45 0 0 0-3.216 4.663c-.428.641-.805 1.322-1.176 2.005c-3.158-1.688-2.697-4.863-1.994-6.358z");
}

.k9pf56bxo {
  stop-color: var(--svg-color--453634, #453634);
}

.kwfvq_byo {
  stop-color: var(--svg-color--342726, #342726);
  stop-opacity: 0;
}

.kx08u4ydv {
  stop-color: var(--svg-color--2f1b1a, #2F1B1A);
  stop-opacity: 0;
}

.l_3w1myze {
  stop-color: var(--svg-color--665250, #665250);
}

.ld_cxyysk {
  stop-color: var(--svg-color--2b1717, #2B1717);
  stop-opacity: 0;
}

.lfy25fb4x {
  stop-color: var(--svg-color--4d4342, #4D4342);
  stop-opacity: 0;
}

.m8e8rve3a {
  fill: var(--svg-color--5a4746, #5A4746);
  d: path("M12.318 6.36c-.1-1.071-.64-1.298-1.094-1.298c1.22-.53 2.125.188 2.22 1.297l.427 6.669l-2.013.931l.575-1.274c.175-.388.267-.808.25-1.234c-.061-1.526-.284-4.233-.365-5.092");
}

.mgppfsfvp {
  stop-color: var(--svg-color--4d3233, #4D3233);
  stop-opacity: 0;
}

.n3akuff4o {
  stop-color: var(--svg-color--342726, #342726);
}

.nanduho6s {
  stop-color: var(--svg-color--3f2825, #3F2825);
  stop-opacity: 0;
}

.nzibwv97f {
  stop-color: var(--svg-color--443634, #443634);
  stop-opacity: 0;
}

.ogljt3byp {
  stop-color: var(--svg-color--593056, #593056);
}

.ot534kb2d {
  stop-color: var(--svg-color--51373b, #51373B);
}

.ov0jz3bsg {
  d: path("M18.504 5.4c-.098.114-.264.52-.264.978c0 2.605-.12 4.52-.12 7.126l4.63 3.316v-1.902l.256-8.253a2.407 2.407 0 0 0-4.501-1.26z");
}

.p6wb4qngy {
  stop-color: var(--svg-color--634f4d, #634F4D);
}

.pte74toty {
  stop-color: var(--svg-color--2d1817, #2D1817);
}

.pw2wixnzv {
  stop-color: var(--svg-color--3f2825, #3F2825);
}

.q6czmub6c {
  stop-color: var(--svg-color--392321, #392321);
  stop-opacity: 0;
}

.r-ag40bgp {
  stop-color: var(--svg-color--3c2035, #3C2035);
  stop-opacity: 0;
}

.sddksqb5q {
  stop-color: var(--svg-color--6c5958, #6C5958);
  stop-opacity: 0;
}

.szxk_5rol {
  stop-color: var(--svg-color--593056, #593056);
  stop-opacity: 0;
}

.tp6n4fzof {
  stop-color: var(--svg-color--4b3936, #4B3936);
}

.tt7eg3bmb {
  stop-color: var(--svg-color--3c2035, #3C2035);
}

.tviy62b6d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.016 13.906c.656-.25 1.68-.744 2.156-1.094");
}

.tyd2sbc-a {
  fill: var(--svg-color--65514f, #65514F);
  d: path("M21.089 5.172v10.11h1.203c.054-2.124.162-6.749.162-8.257s-.91-1.864-1.365-1.853");
}

.u8rgtwhda {
  d: path("M9.426 8.143c.179.237.452.743.496 1.496c.035.6.231 3.923.343 5.643l4.177-1.172L14 7.23c-.017-.632-.011-1.286-.327-1.853A2.34 2.34 0 0 0 9.38 6.745z");
}

.ub7gi2bmx {
  stop-color: var(--svg-color--2d1817, #2D1817);
  stop-opacity: 0;
}

.unuyjut0u {
  stop-color: var(--svg-color--2f1b1a, #2F1B1A);
}

.v0evrfpzt {
  stop-color: var(--svg-color--372127, #372127);
}

.vciz70bvv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.406 16.703c.266-.39.735-1.172.938-1.406");
}

.vgntnsbqz {
  stop-color: var(--svg-color--5e4b4a, #5E4B4A);
}

.vodpp_ldn {
  stop-color: var(--svg-color--51373b, #51373B);
  stop-opacity: 0;
}

.wiibt-xil {
  stop-color: var(--svg-color--382320, #382320);
  stop-opacity: 0;
}

.xdu91mb0m {
  stop-color: var(--svg-color--382320, #382320);
}

.ykwbklbmi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M26.851 14.738c-.744.745-2.555 2.768-3.844 4.906");
}

.zbpb9jvxv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.89 14.5c-.291.344-1.28 1.344-1.843 1.906");
}

.zmn3mpbji {
  d: path("m5.542 14.223l-.187-4.421a2.332 2.332 0 0 1 4.071-1.65v-.009c.179.237.452.743.496 1.496c.056.969.17 3.367.219 4.445z");
}

.ztd0e99bh {
  stop-color: var(--svg-color--5f4143, #5F4143);
}

</style>
