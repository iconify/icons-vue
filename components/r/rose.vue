<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iUWvKAb)" class="v9ju7lbar"/><path fill="url(#izohrTd)" class="v9ju7lbar"/><path fill="url(#ioGiSde)" class="v9ju7lbar"/><path fill="url(#i2kR2pd)" class="v9ju7lbar"/><path fill="url(#iyTYabe)" class="v9ju7lbar"/><path fill="url(#i7doMIc)" class="v9ju7lbar"/><path fill="url(#iKtcHld)" class="v9ju7lbar"/><path fill="url(#islsQee)" class="v9ju7lbar"/><path fill="url(#idRvpPb)" class="sru3d9y4o"/><path fill="url(#iGBM6kd)" class="sru3d9y4o"/><path fill="url(#iO58OJb)" class="sru3d9y4o"/><path fill="url(#imx9dve)" class="sru3d9y4o"/><path fill="url(#iNq63id)" class="sru3d9y4o"/><path fill="url(#iHmZz2c)" class="sru3d9y4o"/><path fill="url(#iHKo7ie)" class="sru3d9y4o"/><g filter="url(#iD3AvSd)"><path fill="url(#iSxvOec)" class="r452kub1i"/></g><path class="accsa4qbd"/><path fill="url(#iYTnCdd)" class="cq_rynb8z"/><path fill="url(#ivctOte)" class="cq_rynb8z"/><path fill="url(#iAhyhdd)" class="cq_rynb8z"/><path fill="url(#iGXJj0v)" class="cq_rynb8z"/><g filter="url(#icSR8gd)"><path class="r6du9_3ah"/><path fill="url(#iYraImd)" class="crj3ztt1m"/><path fill="url(#iYxqbtB)" class="crj3ztt1m"/></g><g filter="url(#iz3962c)"><path class="qxbskh0ln"/><path fill="url(#ibt5Mac)" class="eizn6pqgq"/><path fill="url(#iOE1Npd)" class="eizn6pqgq"/><path fill="url(#iaNEUxP)" class="eizn6pqgq"/></g><g filter="url(#ilEll3d)"><path fill="url(#iXUAUOd)" class="fsntsib3h"/></g><g filter="url(#iunSWze)"><path class="h8g61ds9p"/><path fill="url(#iU04wEe)" class="sw2_kjbon"/><path fill="url(#iO9aQWb)" class="sw2_kjbon"/><path fill="url(#iesSx3c)" class="sw2_kjbon"/></g><path fill="url(#iBbvfMd)" class="sw2_kjbon"/><g filter="url(#ibr8R4b)"><path stroke="url(#ilGKThe)" class="do-15rbmp"/></g><g filter="url(#iuCqXKd)"><path stroke="url(#i2eohGd)" class="ep_l14ita"/></g><defs><radialGradient id="iUWvKAb" cx="0" cy="0" r="1" gradientTransform="rotate(140.575 7.124 16.728)scale(10.2352 9.53824)" gradientUnits="userSpaceOnUse"><stop class="zrdtcqboz"/><stop offset="1" class="ap2aztbvp"/></radialGradient><radialGradient id="izohrTd" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -4.625 3.52185 3.42666 16.75 30.875)" gradientUnits="userSpaceOnUse"><stop class="qnmjf17fr"/><stop offset="1" class="qu1y8mf_w"/></radialGradient><radialGradient id="iyTYabe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.074 17.355 10.785)scale(7.31137 10.5409)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="ruf0gpbyn"/><stop offset="1" class="b2cyfybym"/></radialGradient><radialGradient id="i7doMIc" cx="0" cy="0" r="1" gradientTransform="matrix(5.28124 4.09375 -6.3611 8.20629 18.719 23.383)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="ruf0gpbyn"/><stop offset="1" class="b2cyfybym"/></radialGradient><radialGradient id="iKtcHld" cx="0" cy="0" r="1" gradientTransform="matrix(1.96093 -2.04687 .3406 .3263 15.844 27.352)" gradientUnits="userSpaceOnUse"><stop class="irxnkms1g"/><stop offset="1" class="u7n4qabfu"/></radialGradient><radialGradient id="islsQee" cx="0" cy="0" r="1" gradientTransform="rotate(142.381 8.095 16.267)scale(2.15022 .35721)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="wjsqe42mb"/><stop offset=".982" class="zewz83b9r"/></radialGradient><radialGradient id="iGBM6kd" cx="0" cy="0" r="1" gradientTransform="rotate(-51.582 34.962 -.914)scale(1.15667 2.17277)" gradientUnits="userSpaceOnUse"><stop class="as7arwm4c"/><stop offset="1" class="o8070tbpv"/></radialGradient><radialGradient id="iO58OJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.04688 0 0 -.89063 18.188 20.977)" gradientUnits="userSpaceOnUse"><stop class="tt1tmub5e"/><stop offset="1" class="lsvj38b6y"/></radialGradient><radialGradient id="imx9dve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20313 0 0 -.1875 18.188 20.977)" gradientUnits="userSpaceOnUse"><stop class="c9eq0k_ez"/><stop offset="1" class="buvddwb4o"/></radialGradient><radialGradient id="iNq63id" cx="0" cy="0" r="1" gradientTransform="rotate(146.753 5.528 12.59)scale(1.08635 1.14761)" gradientUnits="userSpaceOnUse"><stop class="csbidibni"/><stop offset="1" class="yjpbfuidh"/></radialGradient><radialGradient id="iHmZz2c" cx="0" cy="0" r="1" gradientTransform="rotate(118.04 2.581 14.404)scale(1.05223 1.28698)" gradientUnits="userSpaceOnUse"><stop class="piovgebrk"/><stop offset="1" class="xowxu3t4w"/></radialGradient><radialGradient id="ivctOte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 -.21875 .57735 -3.95907 15.688 7.406)" gradientUnits="userSpaceOnUse"><stop class="uc4_l_vov"/><stop offset="1" class="m9g294tyg"/></radialGradient><radialGradient id="iGXJj0v" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.3125 1.13403 0 13.922 6.062)" gradientUnits="userSpaceOnUse"><stop class="gn25u5bzo"/><stop offset="1" class="qsza63bbq"/></radialGradient><radialGradient id="ibt5Mac" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 10.125 16.219 14.469)" gradientUnits="userSpaceOnUse"><stop class="osv2jg2js"/><stop offset="1" class="iu-jyjd8w"/></radialGradient><radialGradient id="iO9aQWb" cx="0" cy="0" r="1" gradientTransform="matrix(3.21283 0 0 8.1875 8.287 9.25)" gradientUnits="userSpaceOnUse"><stop class="a8bg17bkn"/><stop offset="1" class="n82an-bxh"/></radialGradient><radialGradient id="iesSx3c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.37756 1.68752 -3.02315 -6.0508 16.188 5.75)" gradientUnits="userSpaceOnUse"><stop class="w_mj22bww"/><stop offset="1" class="mzg8lac0d"/></radialGradient><radialGradient id="iBbvfMd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03127 -3.56249 6.21707 -3.54486 16.969 17.781)" gradientUnits="userSpaceOnUse"><stop class="q1pmlnboh"/><stop offset="1" class="vs9r38bbu"/></radialGradient><radialGradient id="i2eohGd" cx="0" cy="0" r="1" gradientTransform="rotate(90.69 5.719 8.244)scale(1.29697 2.22811)" gradientUnits="userSpaceOnUse"><stop class="as0990fts"/><stop offset="1" class="nn0i4slpc"/></radialGradient><linearGradient id="ioGiSde" x1="18.406" x2="18.406" y1="30.406" y2="29.469" gradientUnits="userSpaceOnUse"><stop class="q2zk3jggk"/><stop offset="1" class="rx0yp3llt"/></linearGradient><linearGradient id="i2kR2pd" x1="19.969" x2="19.969" y1="24" y2="24.883" gradientUnits="userSpaceOnUse"><stop class="ci7yapd7r"/><stop offset="1" class="r4ejjd8vc"/></linearGradient><linearGradient id="idRvpPb" x1="15.432" x2="15.432" y1="21.672" y2="30" gradientUnits="userSpaceOnUse"><stop class="qkk30sbcw"/><stop offset="1" class="b1t0o8bew"/></linearGradient><linearGradient id="iHKo7ie" x1="15.432" x2="15.432" y1="29.563" y2="30.133" gradientUnits="userSpaceOnUse"><stop class="cy9m90byq"/><stop offset="1" class="lnh_zjc4j"/></linearGradient><linearGradient id="iSxvOec" x1="15.651" x2="15.651" y1="18.656" y2="29.288" gradientUnits="userSpaceOnUse"><stop class="cb-id1qca"/><stop offset="1" class="lw5-k98ke"/></linearGradient><linearGradient id="iYTnCdd" x1="15.471" x2="13.22" y1="6.14" y2="6.14" gradientUnits="userSpaceOnUse"><stop class="dp5wqlbmm"/><stop offset="1" class="bl2xhwxiv"/></linearGradient><linearGradient id="iAhyhdd" x1="10.063" x2="11.938" y1="4.094" y2="4.094" gradientUnits="userSpaceOnUse"><stop class="x8yokebfe"/><stop offset="1" class="z365xob0u"/></linearGradient><linearGradient id="iYraImd" x1="15.813" x2="18.695" y1="5.572" y2="5.572" gradientUnits="userSpaceOnUse"><stop class="n39c0ybrs"/><stop offset="1" class="yt3mqmbzb"/></linearGradient><linearGradient id="iYxqbtB" x1="21.501" x2="20.098" y1="5.572" y2="5.572" gradientUnits="userSpaceOnUse"><stop class="n39c0ybrs"/><stop offset="1" class="yt3mqmbzb"/></linearGradient><linearGradient id="iOE1Npd" x1="21.311" x2="21.311" y1="19.185" y2="10.918" gradientUnits="userSpaceOnUse"><stop class="d8jkfjzsi"/><stop offset="1" class="ei_p__bbj"/></linearGradient><linearGradient id="iaNEUxP" x1="17.688" x2="17.688" y1="4.965" y2="6.671" gradientUnits="userSpaceOnUse"><stop class="v02alnben"/><stop offset="1" class="z0_idfbys"/></linearGradient><linearGradient id="iXUAUOd" x1="18.564" x2="18.564" y1="9.174" y2="21.195" gradientUnits="userSpaceOnUse"><stop class="aykjqsbbb"/><stop offset="1" class="ra7jcxb7k"/></linearGradient><linearGradient id="iU04wEe" x1="14.375" x2="14.375" y1="19.688" y2="12.875" gradientUnits="userSpaceOnUse"><stop class="numszorkx"/><stop offset="1" class="ocif3hbty"/></linearGradient><linearGradient id="ilGKThe" x1="20.06" x2="17.87" y1="2.443" y2="2.765" gradientUnits="userSpaceOnUse"><stop class="h8euypb6n"/><stop offset="1" class="gai4nlb2s"/></linearGradient><filter id="iD3AvSd" width="2.697" height="12.891" x="14.303" y="17.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7303" stdDeviation=".5"/></filter><filter id="icSR8gd" width="5.588" height="7.634" x="14.985" y="2.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.121569 0 0 0 0 0.184314 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7303"/></filter><filter id="iz3962c" width="10.031" height="14.609" x="12.797" y="4.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.164706 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7303"/></filter><filter id="ilEll3d" width="8.961" height="9.712" x="14.084" y="7.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7303" stdDeviation=".75"/></filter><filter id="iunSWze" width="9.146" height="14.409" x="8.187" y="4.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.403922 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7303"/></filter><filter id="ibr8R4b" width="3.272" height="1.102" x="17.125" y="1.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7303" stdDeviation=".125"/></filter><filter id="iuCqXKd" width="2.922" height="2.391" x="12.375" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7303" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rose" /></template>
<style>
.a8bg17bkn {
  stop-color: var(--svg-color--d0716f, #D0716F);
}

.accsa4qbd {
  fill: var(--svg-color--c42a3d, #C42A3D);
  d: path("M11.21 2.07c3.948-.32 4.73 2.828 4.73 5.33v2.131H10.5v-6.76c0-.405.304-.686.708-.7");
}

.ap2aztbvp {
  stop-color: var(--svg-color--6f967c, #6F967C);
}

.as0990fts {
  stop-color: var(--svg-color--d55e6c, #D55E6C);
}

.as7arwm4c {
  stop-color: var(--svg-color--60826d, #60826D);
}

.aykjqsbbb {
  stop-color: var(--svg-color--f56563, #F56563);
}

.b1t0o8bew {
  stop-color: var(--svg-color--639262, #639262);
}

.b2cyfybym {
  stop-color: var(--svg-color--5c9948, #5C9948);
}

.bl2xhwxiv {
  stop-color: var(--svg-color--ac1322, #AC1322);
  stop-opacity: 0;
}

.buvddwb4o {
  stop-color: var(--svg-color--99b35d, #99B35D);
  stop-opacity: 0;
}

.c9eq0k_ez {
  stop-color: var(--svg-color--99b35d, #99B35D);
}

.cb-id1qca {
  stop-color: var(--svg-color--98b858, #98B858);
}

.ci7yapd7r {
  stop-color: var(--svg-color--89c146, #89C146);
}

.cq_rynb8z {
  d: path("M11.21 2.07c3.948-.32 4.73 2.828 4.73 5.33v2.131H10.5v-6.76c0-.405.304-.686.708-.7");
}

.crj3ztt1m {
  d: path("M19.715 2.07c-3.948-.32-4.73 2.828-4.73 5.33v2.131h5.439v-6.76c0-.405-.305-.686-.709-.7");
}

.csbidibni {
  stop-color: var(--svg-color--778823, #778823);
}

.cy9m90byq {
  stop-color: var(--svg-color--65797d, #65797D);
  stop-opacity: 0;
}

.d8jkfjzsi {
  stop-color: var(--svg-color--cb4151, #CB4151);
}

.do-15rbmp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.5 2.69a4.4 4.4 0 0 1 2.522-.275");
}

.dp5wqlbmm {
  stop-color: var(--svg-color--ac1322, #AC1322);
}

.ei_p__bbj {
  stop-color: var(--svg-color--cb4151, #CB4151);
  stop-opacity: 0;
}

.eizn6pqgq {
  d: path("m21.591 8.366l.768-2.992a.6.6 0 0 0-.581-.749h-2.152c-.628 0-1.262.097-1.797.424c-1.837 1.125-3.732 3.672-4.246 8.515c-.427 4.02-1.532 5.233 0 5.42h4.112a4.883 4.883 0 0 0 4.674-6.295l-.738-2.44a3.5 3.5 0 0 1-.04-1.883");
}

.ep_l14ita {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.75 2.438c.516.135 1.672.653 2.172 1.64");
}

.fsntsib3h {
  d: path("M20.856 9.174h-5.081c-.329 2.394-.62 6.447 2.654 6.697c3.167.242 3.41-2.55 2.92-3.974c-.493-1.432-.518-2.36-.493-2.723");
}

.ft5dv1b6b {
  fill: none;
}

.gai4nlb2s {
  stop-color: var(--svg-color--dd5c6a, #DD5C6A);
  stop-opacity: 0;
}

.gn25u5bzo {
  stop-color: var(--svg-color--bb3b4b, #BB3B4B);
}

.h8euypb6n {
  stop-color: var(--svg-color--ee6372, #EE6372);
}

.h8g61ds9p {
  fill: var(--svg-color--d33939, #D33939);
  d: path("m9.274 8.366l-.768-2.992a.6.6 0 0 1 .581-.749h2.152c.627 0 1.262.097 1.797.424c1.837 1.125 3.732 3.672 4.246 8.515c.427 4.02-1.953 5.233-3.484 5.42h-.628a4.883 4.883 0 0 1-4.674-6.295l.738-2.44a3.5 3.5 0 0 0 .04-1.883");
}

.irxnkms1g {
  stop-color: var(--svg-color--489041, #489041);
}

.iu-jyjd8w {
  stop-color: var(--svg-color--df2c28, #DF2C28);
  stop-opacity: 0;
}

.lnh_zjc4j {
  stop-color: var(--svg-color--65797d, #65797D);
}

.lsvj38b6y {
  stop-color: var(--svg-color--87a837, #87A837);
  stop-opacity: 0;
}

.lw5-k98ke {
  stop-color: var(--svg-color--85ad78, #85AD78);
}

.m9g294tyg {
  stop-color: var(--svg-color--9f0510, #9F0510);
  stop-opacity: 0;
}

.mzg8lac0d {
  stop-color: var(--svg-color--f03954, #F03954);
  stop-opacity: 0;
}

.n39c0ybrs {
  stop-color: var(--svg-color--b01e2e, #B01E2E);
}

.n82an-bxh {
  stop-color: var(--svg-color--d0716f, #D0716F);
  stop-opacity: 0;
}

.nn0i4slpc {
  stop-color: var(--svg-color--d55e6c, #D55E6C);
  stop-opacity: 0;
}

.numszorkx {
  stop-color: var(--svg-color--ce2f5c, #CE2F5C);
}

.o8070tbpv {
  stop-color: var(--svg-color--60826d, #60826D);
  stop-opacity: 0;
}

.ocif3hbty {
  stop-color: var(--svg-color--ce2f5c, #CE2F5C);
  stop-opacity: 0;
}

.osv2jg2js {
  stop-color: var(--svg-color--df2c28, #DF2C28);
}

.piovgebrk {
  stop-color: var(--svg-color--738b32, #738B32);
}

.q1pmlnboh {
  stop-color: var(--svg-color--e42e5e, #E42E5E);
}

.q2zk3jggk {
  stop-color: var(--svg-color--707290, #707290);
}

.qkk30sbcw {
  stop-color: var(--svg-color--7ea242, #7EA242);
}

.qnmjf17fr {
  stop-color: var(--svg-color--5d807a, #5D807A);
}

.qsza63bbq {
  stop-color: var(--svg-color--bb3b4b, #BB3B4B);
  stop-opacity: 0;
}

.qu1y8mf_w {
  stop-color: var(--svg-color--5d807a, #5D807A);
  stop-opacity: 0;
}

.qxbskh0ln {
  fill: var(--svg-color--eb4a49, #EB4A49);
  d: path("m21.591 8.366l.768-2.992a.6.6 0 0 0-.581-.749h-2.152c-.628 0-1.262.097-1.797.424c-1.837 1.125-3.732 3.672-4.246 8.515c-.427 4.02-1.532 5.233 0 5.42h4.112a4.883 4.883 0 0 0 4.674-6.295l-.738-2.44a3.5 3.5 0 0 1-.04-1.883");
}

.r452kub1i {
  d: path("M15.303 18.656H16v10.891h-.697z");
}

.r4ejjd8vc {
  stop-color: var(--svg-color--89c146, #89C146);
  stop-opacity: 0;
}

.r6du9_3ah {
  fill: var(--svg-color--d4505f, #D4505F);
  d: path("M19.715 2.07c-3.948-.32-4.73 2.828-4.73 5.33v2.131h5.439v-6.76c0-.405-.305-.686-.709-.7");
}

.ra7jcxb7k {
  stop-color: var(--svg-color--f56563, #F56563);
  stop-opacity: 0;
}

.ruf0gpbyn {
  stop-color: var(--svg-color--5c9948, #5C9948);
  stop-opacity: 0;
}

.rx0yp3llt {
  stop-color: var(--svg-color--707290, #707290);
  stop-opacity: 0;
}

.sru3d9y4o {
  d: path("M16.438 29.8a.2.2 0 0 1-.2.2h-1.6a.2.2 0 0 1-.2-.2v-2.695a.25.25 0 0 0-.14-.224l-1.21-.601a.362.362 0 0 1 0-.65l1.21-.601a.25.25 0 0 0 .14-.224V18.23h2v1.645a.25.25 0 0 0 .138.224l1.201.601c.27.13.27.52 0 .65l-1.199.582a.25.25 0 0 0-.14.225z");
}

.sw2_kjbon {
  d: path("m9.274 8.366l-.768-2.992a.6.6 0 0 1 .581-.749h2.152c.627 0 1.262.097 1.797.424c1.837 1.125 3.732 3.672 4.246 8.515c.427 4.02-1.953 5.233-3.484 5.42h-.628a4.883 4.883 0 0 1-4.674-6.295l.738-2.44a3.5 3.5 0 0 0 .04-1.883");
}

.tt1tmub5e {
  stop-color: var(--svg-color--87a837, #87A837);
}

.u7n4qabfu {
  stop-color: var(--svg-color--489041, #489041);
  stop-opacity: 0;
}

.uc4_l_vov {
  stop-color: var(--svg-color--9f0510, #9F0510);
}

.v02alnben {
  stop-color: var(--svg-color--f86560, #F86560);
}

.v9ju7lbar {
  d: path("M16.438 26.169L15.5 30h2.804c3.276 0 5.963-2.545 6.133-5.68a.297.297 0 0 0-.3-.32l-3.506.01a5.27 5.27 0 0 0-4.193 2.159");
}

.vs9r38bbu {
  stop-color: var(--svg-color--e42e5e, #E42E5E);
  stop-opacity: 0;
}

.w_mj22bww {
  stop-color: var(--svg-color--f03954, #F03954);
}

.wjsqe42mb {
  stop-color: var(--svg-color--a1d460, #A1D460);
}

.x8yokebfe {
  stop-color: var(--svg-color--c7676b, #C7676B);
}

.xowxu3t4w {
  stop-color: var(--svg-color--738b32, #738B32);
  stop-opacity: 0;
}

.yjpbfuidh {
  stop-color: var(--svg-color--839624, #839624);
  stop-opacity: 0;
}

.yt3mqmbzb {
  stop-color: var(--svg-color--b01e2e, #B01E2E);
  stop-opacity: 0;
}

.z0_idfbys {
  stop-color: var(--svg-color--f86560, #F86560);
  stop-opacity: 0;
}

.z365xob0u {
  stop-color: var(--svg-color--c7676b, #C7676B);
  stop-opacity: 0;
}

.zewz83b9r {
  stop-color: var(--svg-color--a1d460, #A1D460);
  stop-opacity: 0;
}

.zrdtcqboz {
  stop-color: var(--svg-color--94c852, #94C852);
}

</style>
