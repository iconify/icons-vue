<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iR45GFR)"><path fill="url(#irBeX7b)" class="kucajh8au"/></g><g filter="url(#if4zk4c)"><path fill="url(#iRzinZb)" class="k5zxaccpr"/></g><g filter="url(#imHUJOe)"><path fill="url(#iMKL8ce)" class="c6k3m1bhn"/><path fill="url(#iZcz6jc)" class="c6k3m1bhn"/></g><g filter="url(#iaypboj)"><path fill="url(#ixe8rwc)" class="di8l1yblx"/></g><g filter="url(#iP1Be6b)"><path fill="url(#iWzQzdc)" class="bo_6btutb"/><path fill="url(#iVQzOqd)" class="bo_6btutb"/><path fill="url(#i3Yl40b)" class="bo_6btutb"/><path fill="url(#i0YFReo)" class="bo_6btutb"/><path fill="url(#iN6mrzO)" class="bo_6btutb"/><path fill="url(#iKBVBOb)" class="bo_6btutb"/><path fill="url(#i7YbO0d)" class="bo_6btutb"/><path fill="url(#iJ4df1c)" class="bo_6btutb"/></g><path fill="url(#iJopsIc)" class="bo_6btutb"/><g filter="url(#iwGD8pL)"><path fill="url(#i4NXYGc)" class="w_kracfzs"/></g><g filter="url(#igIcgle)"><path class="tzu84gyrs"/><path fill="url(#iL7OGiO)" class="c8vaqsbda"/><path fill="url(#isrK0Kd)" class="c8vaqsbda"/><path fill="url(#i5alSfd)" class="c8vaqsbda"/><path fill="url(#iuzlEPb)" class="c8vaqsbda"/><path fill="url(#i59nwie)" class="c8vaqsbda"/></g><g filter="url(#iDnSGdX)"><path stroke="url(#iRUUwZd)" class="vmw_irb9y"/></g><path class="wxgfgebei"/><g filter="url(#iNGXgde)"><path class="iuhfddcnf"/></g><g filter="url(#it9ocBc)"><path class="qhfgn5vli"/></g><path class="atqfqlphr"/><path fill="url(#ijaDolb)" class="b7ffjfb7q"/><path class="h7c0c7b5k"/><g filter="url(#ilvTtVd)"><path fill="url(#ik6Gqid)" class="mx8aigb4b"/></g><g filter="url(#iR2OG5t)"><ellipse transform="rotate(-27.914 11.27 15.663)" class="hh9yhccaw"/><ellipse fill="url(#i9T9rSb)" transform="rotate(-27.914 11.27 15.663)" class="l34umybke"/></g><path class="gpo-x8s4n"/><path fill="url(#iBzWYrd)" class="lpcbqrzyv"/><path class="dm21cybez"/><g filter="url(#izZxwpc)"><path class="d5irs8bop"/><path fill="url(#io2qQPb)" class="q5qi2rbdr"/></g><g filter="url(#i1FcmLp)"><path fill="url(#ijPjLAb)" class="fofe-abkb"/></g><g filter="url(#ibhggHc)"><path class="rqtwnzkif"/></g><g filter="url(#iTAvKOT)"><path class="q6nknmbph"/></g><g filter="url(#ibD9g5c)"><path fill="url(#icn26nd)" class="sd9_4o2-h"/></g><defs><radialGradient id="irBeX7b" cx="0" cy="0" r="1" gradientTransform="matrix(3.15625 0 0 5.09375 3.436 17.27)" gradientUnits="userSpaceOnUse"><stop class="esdmgdbya"/><stop offset="1" class="pws2eybzm"/></radialGradient><radialGradient id="iRzinZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48723 .21943 -.29636 -2.00865 6.643 17.182)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="uoqdc3bst"/><stop offset="1" class="lfai23bem"/></radialGradient><radialGradient id="iZcz6jc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.244 30.214 -18.39)scale(2.29666 2.22246)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="tvpdim4do"/><stop offset="1" class="s4yg3qbio"/></radialGradient><radialGradient id="iWzQzdc" cx="0" cy="0" r="1" gradientTransform="rotate(117.759 8.593 10.636)scale(17.7152 15.9561)" gradientUnits="userSpaceOnUse"><stop class="s_gru5b0s"/><stop offset="1" class="r_v6ig2ve"/></radialGradient><radialGradient id="iVQzOqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.17105 -8.57064 0 21.872 18.34)" gradientUnits="userSpaceOnUse"><stop class="d6vk_1y_q"/><stop offset="1" class="a55qy0sag"/></radialGradient><radialGradient id="i3Yl40b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.36514 10.5925 0 9.405 28.913)" gradientUnits="userSpaceOnUse"><stop class="mmvyxxg-n"/><stop offset="1" class="v-s__jzmv"/></radialGradient><radialGradient id="i0YFReo" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05461 19.43755 -18.9858 -2.98362 18.905 9.801)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="gsot_-7tt"/><stop offset="1" class="qzgm3hbth"/></radialGradient><radialGradient id="iN6mrzO" cx="0" cy="0" r="1" gradientTransform="matrix(.53947 -2.38004 2.66131 .60323 11.789 14.523)" gradientUnits="userSpaceOnUse"><stop class="p9uf-9bng"/><stop offset="1" class="a_ydchqjw"/></radialGradient><radialGradient id="iKBVBOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.91744 3.21246 0 20.28 14.563)" gradientUnits="userSpaceOnUse"><stop offset=".025" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="i7YbO0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75 -4.02907 0 17.625 3.719)" gradientUnits="userSpaceOnUse"><stop class="mq_ck7blr"/><stop offset="1" class="rpj744bdc"/></radialGradient><radialGradient id="iJ4df1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 6.6875 -9.88813 4.99026 9.096 2.75)" gradientUnits="userSpaceOnUse"><stop class="tpn7ugbej"/><stop offset="1" class="t97-jd3qw"/></radialGradient><radialGradient id="iJopsIc" cx="0" cy="0" r="1" gradientTransform="matrix(3.61765 5.39474 -14.04102 9.41573 8.742 2.591)" gradientUnits="userSpaceOnUse"><stop class="dpzu5gbvf"/><stop offset="1" class="hbbd049re"/></radialGradient><radialGradient id="isrK0Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-101.422 16.685 2.756)scale(4.55904 1.45764)" gradientUnits="userSpaceOnUse"><stop class="ibvyubcnx"/><stop offset="1" class="hsl5_jvxp"/></radialGradient><radialGradient id="iuzlEPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59505 0 0 -.28125 17.017 19.875)" gradientUnits="userSpaceOnUse"><stop class="gg9v3ibhg"/><stop offset="1" class="jgrs-ob8h"/></radialGradient><radialGradient id="ijaDolb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53876 -2.44757 0 11.784 15.844)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="i9T9rSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01467 -.93704 1.12636 -.01764 11.241 16.26)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBzWYrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.914 15.838)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="io2qQPb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.661 3.225)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icn26nd" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 4.71875 -11.46927 12.00094 17 7.25)" gradientUnits="userSpaceOnUse"><stop class="l3f93lbgc"/><stop offset="1" class="s_c-te6ux"/></radialGradient><filter id="iR45GFR" width="6" height="6.2" x="3.846" y="13.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.458824 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2076"/></filter><filter id="if4zk4c" width="4.132" height="4.132" x="4.78" y="14.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".125"/></filter><filter id="imHUJOe" width="6.2" height="6.2" x="21.846" y="13.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.407843 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2076"/></filter><filter id="iaypboj" width="4.632" height="4.632" x="22.733" y="14.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".25"/></filter><filter id="iP1Be6b" width="20.485" height="26.75" x="6.108" y="3.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.708333 0 0 0 0 0.525463 0 0 0 0 0.475174 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2076"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.596078 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2076" result="effect2_innerShadow_3930_2076"/></filter><filter id="iwGD8pL" width="4.5" height="5.836" x="13.358" y="15.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".25"/></filter><filter id="igIcgle" width="3.571" height="5.2" x="14.061" y="15.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".05"/></filter><filter id="iDnSGdX" width="6.619" height="2.54" x="12.537" y="22.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".075"/></filter><filter id="iNGXgde" width="4.424" height="2.097" x="18.809" y="10.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.129412 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2076"/></filter><filter id="it9ocBc" width="4.424" height="2.069" x="9.009" y="10.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.129412 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2076"/></filter><filter id="ilvTtVd" width="1.512" height="1.614" x="12.015" y="15.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".1"/></filter><filter id="iR2OG5t" width="1.552" height="1.157" x="10.493" y="15.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".05"/></filter><filter id="izZxwpc" width="1.294" height="1.125" x="18.632" y="15.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".05"/></filter><filter id="i1FcmLp" width="1.316" height="1.357" x="20.284" y="15.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".1"/></filter><filter id="ibhggHc" width="4.076" height="1.651" x="9.149" y="11.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".175"/></filter><filter id="iTAvKOT" width="3.97" height="1.737" x="19.087" y="11.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation=".175"/></filter><filter id="ibD9g5c" width="12.281" height="10.228" x="14" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2076" stdDeviation="1"/></filter><linearGradient id="iMKL8ce" x1="26.936" x2="24.846" y1="14.582" y2="19.645" gradientUnits="userSpaceOnUse"><stop class="ibswijbpv"/><stop offset="1" class="h0dd8j_ls"/></linearGradient><linearGradient id="ixe8rwc" x1="25.83" x2="25.049" y1="16.078" y2="19.219" gradientUnits="userSpaceOnUse"><stop class="uuid-wb4c"/><stop offset="1" class="uogww_z-r"/></linearGradient><linearGradient id="i4NXYGc" x1="14.611" x2="15.608" y1="19.287" y2="21.324" gradientUnits="userSpaceOnUse"><stop class="xe1uh3bgc"/><stop offset="1" class="n4_tdjrjb"/><stop offset="1" class="pu3vo_rqf"/></linearGradient><linearGradient id="iL7OGiO" x1="13.736" x2="15.455" y1="19.614" y2="19.904" gradientUnits="userSpaceOnUse"><stop class="d879-zb_f"/><stop offset="1" class="pvqf46-2f"/></linearGradient><linearGradient id="i5alSfd" x1="15.846" x2="15.846" y1="21.239" y2="19.77" gradientUnits="userSpaceOnUse"><stop class="bxey5s89g"/><stop offset="1" class="cywqw2bke"/></linearGradient><linearGradient id="i59nwie" x1="15.846" x2="15.846" y1="16.051" y2="17.125" gradientUnits="userSpaceOnUse"><stop class="e48d4vidk"/><stop offset="1" class="jcrhvi9tj"/></linearGradient><linearGradient id="iRUUwZd" x1="14.608" x2="15.139" y1="24.321" y2="22.973" gradientUnits="userSpaceOnUse"><stop class="vju3fybyz"/><stop offset="1" class="wp4xjyjzq"/></linearGradient><linearGradient id="ik6Gqid" x1="13.195" x2="12.6" y1="15.947" y2="16.313" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijPjLAb" x1="21.365" x2="20.78" y1="15.938" y2="16.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bald-medium" /></template>
<style>
.a_ydchqjw {
  stop-color: var(--svg-color--8c5c63, #8C5C63);
  stop-opacity: 0;
}

.a55qy0sag {
  stop-color: var(--svg-color--c6997f, #C6997F);
  stop-opacity: 0;
}

.atqfqlphr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.388 14.424a2.65 2.65 0 0 0-2.57 2.008a.52.52 0 0 0 .508.646h4.232a.436.436 0 0 0 .43-.515a2.66 2.66 0 0 0-2.6-2.139");
}

.b7ffjfb7q {
  d: path("M11.78 14.94a1.693 1.693 0 0 0-1.63 2.138h3.27q.059-.217.06-.446a1.704 1.704 0 0 0-1.7-1.692");
}

.bo_6btutb {
  d: path("M17.912 3.163h-4.147c-5.57 0-8.018 3.75-7.614 8.71l.7 10.69a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35l.67-10.69c.53-4.703-2.115-8.71-7.615-8.71");
}

.bxey5s89g {
  stop-color: var(--svg-color--9b6075, #9B6075);
}

.c6k3m1bhn {
  d: path("M24.846 20.051a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.c8vaqsbda {
  d: path("m15.16 16.578l-.955 3.17c-.195.651.273 1.303.935 1.303h1.412c.662 0 1.13-.662.935-1.304l-.955-3.17a.71.71 0 0 0-1.373 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cywqw2bke {
  stop-color: var(--svg-color--9b6075, #9B6075);
  stop-opacity: 0;
}

.d5irs8bop {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.796 15.3c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.d6vk_1y_q {
  stop-color: var(--svg-color--c6997f, #C6997F);
}

.d879-zb_f {
  stop-color: var(--svg-color--8d6657, #8D6657);
}

.di8l1yblx {
  d: path("M25.049 18.867a1.816 1.816 0 1 0 0-3.631a1.816 1.816 0 0 0 0 3.631");
}

.dm21cybez {
  fill: var(--svg-color--000, #000);
  d: path("M18.965 16.613c0-.53.424-.953.953-.953c.53 0 .953.423.953.953a.94.94 0 0 1-.106.438h-1.687a.86.86 0 0 1-.113-.438");
}

.dpzu5gbvf {
  stop-color: var(--svg-color--8d715c, #8D715C);
}

.e48d4vidk {
  stop-color: var(--svg-color--b38879, #B38879);
}

.esdmgdbya {
  stop-color: var(--svg-color--87595f, #87595F);
}

.fofe-abkb {
  d: path("M21.4 16.394a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.ft5dv1b6b {
  fill: none;
}

.gg9v3ibhg {
  stop-color: var(--svg-color--cda38f, #CDA38F);
}

.gpo-x8s4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.304 14.442c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.16a.43.43 0 0 1-.423-.506a2.606 2.606 0 0 1 2.557-2.103");
}

.gsot_-7tt {
  stop-color: var(--svg-color--965680, #965680);
  stop-opacity: 0;
}

.h0dd8j_ls {
  stop-color: var(--svg-color--ae7f72, #AE7F72);
}

.h7c0c7b5k {
  fill: var(--svg-color--000, #000);
  d: path("M12.75 16.632a.966.966 0 0 0-.97-.97a.966.966 0 0 0-.861 1.416h1.715a.96.96 0 0 0 .116-.446");
}

.hbbd049re {
  stop-color: var(--svg-color--8d715c, #8D715C);
  stop-opacity: 0;
}

.hh9yhccaw {
  cx: 11.27px;
  cy: 15.663px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.739px;
  ry: 0.374px;
}

.hsl5_jvxp {
  stop-color: var(--svg-color--cfa68e, #CFA68E);
  stop-opacity: 0;
}

.ibswijbpv {
  stop-color: var(--svg-color--cca38a, #CCA38A);
}

.ibvyubcnx {
  stop-color: var(--svg-color--cfa68e, #CFA68E);
}

.iuhfddcnf {
  fill: var(--svg-color--4d3431, #4D3431);
  d: path("M22.806 11.99c-.327-.284-.707-.585-1.282-.766c-.568-.179-1.278-.227-2.26-.106a.517.517 0 1 0 .125 1.026c.897-.11 1.446-.053 1.824.066c.37.117.62.305.913.56a.517.517 0 0 0 .68-.78");
}

.jcrhvi9tj {
  stop-color: var(--svg-color--b38879, #B38879);
  stop-opacity: 0;
}

.jgrs-ob8h {
  stop-color: var(--svg-color--cda38f, #CDA38F);
  stop-opacity: 0;
}

.k5zxaccpr {
  d: path("M6.846 18.867a1.816 1.816 0 1 0 0-3.632a1.816 1.816 0 0 0 0 3.632");
}

.kucajh8au {
  d: path("M6.846 20.051a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l34umybke {
  cx: 11.27px;
  cy: 15.663px;
  rx: 0.739px;
  ry: 0.374px;
}

.l3f93lbgc {
  stop-color: var(--svg-color--cda58e, #CDA58E);
}

.lfai23bem {
  stop-color: var(--svg-color--784c4b, #784C4B);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpcbqrzyv {
  d: path("M19.918 14.949a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.671-1.664");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mmvyxxg-n {
  stop-color: var(--svg-color--955d70, #955D70);
}

.mq_ck7blr {
  stop-color: var(--svg-color--ba967a, #BA967A);
}

.mx8aigb4b {
  d: path("M13.327 16.433c0-.547-.445-.911-.565-1.021l-.547.528l.336.686z");
}

.n4_tdjrjb {
  stop-color: var(--svg-color--733e4f, #733E4F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p9uf-9bng {
  stop-color: var(--svg-color--8c5c63, #8C5C63);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pu3vo_rqf {
  stop-color: var(--svg-color--8c5263, #8C5263);
}

.pvqf46-2f {
  stop-color: var(--svg-color--8d6657, #8D6657);
  stop-opacity: 0;
}

.pws2eybzm {
  stop-color: var(--svg-color--775349, #775349);
}

.q5qi2rbdr {
  d: path("M19.796 15.3c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.q6nknmbph {
  stroke: var(--svg-color--553e3e, #553E3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.582 12.295c-.5-.484-1.695-.918-3.02-.75");
}

.qhfgn5vli {
  fill: var(--svg-color--4d3431, #4D3431);
  d: path("M9.487 11.788a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.126 1.026a4.14 4.14 0 0 0-2.585.53a3 3 0 0 0-.171.112l-.005.004a.517.517 0 0 1-.634-.817z");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzgm3hbth {
  stop-color: var(--svg-color--965680, #965680);
}

.r_v6ig2ve {
  stop-color: var(--svg-color--936865, #936865);
}

.rpj744bdc {
  stop-color: var(--svg-color--b89075, #B89075);
  stop-opacity: 0;
}

.rqtwnzkif {
  stroke: var(--svg-color--553e3e, #553E3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.624 12.209c.408-.303 1.689-.808 3.126-.681");
}

.s_c-te6ux {
  stop-color: var(--svg-color--cda58e, #CDA58E);
  stop-opacity: 0;
}

.s_gru5b0s {
  stop-color: var(--svg-color--d0a88d, #D0A88D);
}

.s-ceiepmf {
  stop-color: var(--svg-color--654843, #654843);
}

.s4yg3qbio {
  stop-color: var(--svg-color--a06c5d, #A06C5D);
  stop-opacity: 0;
}

.sd9_4o2-h {
  d: path("m22.813 6.5l-5.269 1.232A2 2 0 0 0 16 9.68v1.747a1 1 0 0 0 .495.863l.572.335a.745.745 0 0 0 1.12-.643c0-.353.25-.658.595-.729l5.5-1.128c0-1.5-1.042-3.208-1.47-3.625");
}

.t97-jd3qw {
  stop-color: var(--svg-color--8e705b, #8E705B);
  stop-opacity: 0;
}

.tpn7ugbej {
  stop-color: var(--svg-color--8e705b, #8E705B);
}

.tvpdim4do {
  stop-color: var(--svg-color--a06c5d, #A06C5D);
}

.tzu84gyrs {
  fill: var(--svg-color--ac8370, #AC8370);
  d: path("m15.16 16.578l-.955 3.17c-.195.651.273 1.303.935 1.303h1.412c.662 0 1.13-.662.935-1.304l-.955-3.17a.71.71 0 0 0-1.373 0");
}

.uogww_z-r {
  stop-color: var(--svg-color--aa7d65, #AA7D65);
}

.uoqdc3bst {
  stop-color: var(--svg-color--734d4e, #734D4E);
}

.uuid-wb4c {
  stop-color: var(--svg-color--a87a6c, #A87A6C);
}

.v-s__jzmv {
  stop-color: var(--svg-color--955d70, #955D70);
  stop-opacity: 0;
}

.vju3fybyz {
  stop-color: var(--svg-color--ac817d, #AC817D);
}

.vmw_irb9y {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.235 22.27a.34.34 0 0 0-.407.071a.31.31 0 0 0-.034.4a3.65 3.65 0 0 0 3.052 1.63a3.65 3.65 0 0 0 3.052-1.63a.314.314 0 0 0-.035-.404a.34.34 0 0 0-.406-.066a5.6 5.6 0 0 1-2.611.619a5.66 5.66 0 0 1-2.611-.62Z");
}

.w_kracfzs {
  d: path("m15.108 17.015l-1.204 3.005a1.005 1.005 0 0 0 .97 1.304h1.467c.687 0 1.173-.662.97-1.304l-1.125-3.005c-.213-.703-.855-.703-1.078 0");
}

.wp4xjyjzq {
  stop-color: var(--svg-color--ac817d, #AC817D);
  stop-opacity: 0;
}

.wxgfgebei {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.846 22.94a5.7 5.7 0 0 1-2.634-.625c-.26-.132-.54.161-.376.398a3.6 3.6 0 0 0 3.01 1.608a3.6 3.6 0 0 0 3.01-1.608c.164-.246-.116-.53-.376-.398a5.7 5.7 0 0 1-2.634.625");
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xe1uh3bgc {
  stop-color: var(--svg-color--865758, #865758);
}

</style>
