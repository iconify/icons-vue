<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qbmd_7y2p"/><path fill="url(#iB0dsfb)" class="z22fruy5g"/><path fill="url(#iTYqIBe)" class="z22fruy5g"/><path fill="url(#i0tjm5J)" class="z22fruy5g"/><path class="wgouexbiv"/><path fill="url(#ihs9kId)" class="i3dcd48zj"/><path fill="url(#idQ7V0d)" class="i3dcd48zj"/><path fill="url(#if4M8ae)" class="i3dcd48zj"/><path fill="url(#ipFJcIb)" class="i3dcd48zj"/><g filter="url(#i7uoSVd)" class="tozgsv2_d"><path stroke="url(#iOo0fdb)" class="v67zr5bie"/><path stroke="url(#iT9CzHb)" class="v67zr5bie"/></g><g filter="url(#islhfOe)"><path stroke="url(#ilwukue)" class="d2jw3rb0g"/></g><g filter="url(#il3DKIe)"><path class="ib5vvvb1o"/><path fill="url(#iPneF3y)" class="ufdpxem1x"/><path fill="url(#imQMIhe)" class="zhdv-abdd"/><path fill="url(#i1a5Nyc)" class="ufdpxem1x"/><path fill="url(#ifmG0Qc)" class="ufdpxem1x"/></g><g filter="url(#i883dej)"><path class="cjya7z99b"/><path fill="url(#iK2A34b)" class="xhqbnza6p"/><path fill="url(#iLOl37c)" class="xhqbnza6p"/></g><g filter="url(#i0tlyOe)"><path stroke="url(#iLKGWJd)" class="p1mlabu_v"/></g><g filter="url(#iNkL7mt)"><path stroke="url(#i4QFKMe)" class="mpz7ut52e"/></g><g filter="url(#i97kvPd)"><path fill="url(#i1xq8rc)" class="s_sr5lbwb"/></g><g filter="url(#iefFeDe)"><path fill="url(#if4IGgb)" class="eheioum6h"/></g><g filter="url(#iCn2pje)"><path class="dpvpe84ol"/></g><defs><radialGradient id="iB0dsfb" cx="0" cy="0" r="1" gradientTransform="rotate(132.357 9.462 17.964)scale(7.1892 4.90727)" gradientUnits="userSpaceOnUse"><stop offset=".824" class="iiyqncanc"/><stop offset="1" class="vh-g-vbvc"/></radialGradient><radialGradient id="i0tjm5J" cx="0" cy="0" r="1" gradientTransform="matrix(-.56628 1.975 -1.01947 -.2923 27.24 23.951)" gradientUnits="userSpaceOnUse"><stop class="x7rlucchp"/><stop offset="1" class="g8_6xqbqu"/></radialGradient><radialGradient id="ihs9kId" cx="0" cy="0" r="1" gradientTransform="matrix(.92969 4.5 -10.34836 2.13794 5.33 18.57)" gradientUnits="userSpaceOnUse"><stop offset=".544" class="srn-wtbey"/><stop offset="1" class="ooeangkay"/><stop offset="1" class="kwwb2c0wr"/></radialGradient><radialGradient id="ipFJcIb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09374 -5.00001 4.85325 -4.94422 9.518 20.601)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="t-uhq_evu"/><stop offset=".946" class="vwgak1tih"/></radialGradient><radialGradient id="iT9CzHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56252 -2.4375 4.18268 -.96526 18.392 8.32)" gradientUnits="userSpaceOnUse"><stop class="e47ugq69i"/><stop offset="1" class="gcvo3w51o"/></radialGradient><radialGradient id="iPneF3y" cx="0" cy="0" r="1" gradientTransform="rotate(-146.501 15.407 6.028)scale(4.03365 1.21745)" gradientUnits="userSpaceOnUse"><stop class="oyhm_trkz"/><stop offset="1" class="z75afk-6m"/></radialGradient><radialGradient id="imQMIhe" cx="0" cy="0" r="1" gradientTransform="matrix(-.48873 2.7228 -1.082 -.19422 19.575 17.97)" gradientUnits="userSpaceOnUse"><stop class="oyhm_trkz"/><stop offset="1" class="z75afk-6m"/></radialGradient><radialGradient id="i1a5Nyc" cx="0" cy="0" r="1" gradientTransform="rotate(88.394 -1.124 18.266)scale(3.73659 2.45334)" gradientUnits="userSpaceOnUse"><stop class="occj0325a"/><stop offset="1" class="jpa7fx5hh"/></radialGradient><radialGradient id="ifmG0Qc" cx="0" cy="0" r="1" gradientTransform="matrix(2.91687 2.44354 -1.08327 1.2931 20.498 16.33)" gradientUnits="userSpaceOnUse"><stop class="occj0325a"/><stop offset="1" class="jpa7fx5hh"/></radialGradient><radialGradient id="iK2A34b" cx="0" cy="0" r="1" gradientTransform="rotate(-157.813 15.651 6.08)scale(13.4962 10.9747)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="mpy2y5sef"/><stop offset="1" class="phhvu5btv"/></radialGradient><radialGradient id="iLOl37c" cx="0" cy="0" r="1" gradientTransform="matrix(-13.4977 -6.84185 5.95456 -11.74723 27.08 17.55)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="so_ghbbhm"/><stop offset="1" class="doylssbjv"/></radialGradient><linearGradient id="iTYqIBe" x1="23.73" x2="24.517" y1="24.451" y2="24.451" gradientUnits="userSpaceOnUse"><stop class="jyl4068xm"/><stop offset="1" class="vnct225wb"/></linearGradient><linearGradient id="idQ7V0d" x1="8.502" x2="7.643" y1="19.07" y2="19.07" gradientUnits="userSpaceOnUse"><stop class="wh8n1dbsf"/><stop offset="1" class="gjxm3mbag"/></linearGradient><linearGradient id="if4M8ae" x1="7.268" x2="5.799" y1="23.195" y2="21.758" gradientUnits="userSpaceOnUse"><stop class="wh8n1dbsf"/><stop offset="1" class="gjxm3mbag"/></linearGradient><linearGradient id="iOo0fdb" x1="17.736" x2="7.861" y1="4.82" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="h81gcuzsc"/><stop offset="1" class="ynqnmsbwf"/></linearGradient><linearGradient id="ilwukue" x1="10.611" x2="20.174" y1=".508" y2="6.508" gradientUnits="userSpaceOnUse"><stop class="qwcin8b7r"/><stop offset="1" class="x2hzur60y"/></linearGradient><linearGradient id="iLKGWJd" x1="9.694" x2="9.694" y1="5.289" y2="37.414" gradientUnits="userSpaceOnUse"><stop class="en_c4ybpw"/><stop offset=".268" class="n_otmo27f"/><stop offset="1" class="yryj2fb5b"/></linearGradient><linearGradient id="i4QFKMe" x1="26.723" x2="31.136" y1="24.709" y2="25.873" gradientUnits="userSpaceOnUse"><stop class="c1i02ccyu"/><stop offset="1" class="u3apbpbyy"/></linearGradient><linearGradient id="i1xq8rc" x1="24.788" x2="21.32" y1="17.925" y2="1.179" gradientUnits="userSpaceOnUse"><stop class="bmiizgb4n"/><stop offset="1" class="pt02vrbyz"/></linearGradient><linearGradient id="if4IGgb" x1="20.901" x2="17.998" y1="16.643" y2="14.588" gradientUnits="userSpaceOnUse"><stop class="bmiizgb4n"/><stop offset="1" class="pt02vrbyz"/></linearGradient><filter id="i7uoSVd" width="14.789" height="27.728" x="5.394" y="2.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.760784 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7335"/></filter><filter id="islhfOe" width="8.875" height="7.734" x="11.611" y="1.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7335" stdDeviation=".5"/></filter><filter id="il3DKIe" width="9.061" height="9.561" x="15.867" y="12.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.12549 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7335"/></filter><filter id="i883dej" width="12.797" height="13.75" x="13.282" y="6.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-1.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.795833 0 0 0 0 0.102795 0 0 0 0 0.159459 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7335"/></filter><filter id="i0tlyOe" width="6.861" height="25.031" x="6.407" y="4.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7335" stdDeviation=".25"/></filter><filter id="iNkL7mt" width="3.75" height="6.844" x="23.973" y="22.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7335" stdDeviation=".3"/></filter><filter id="i97kvPd" width="6.497" height="11.447" x="20.07" y="7.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7335" stdDeviation=".625"/></filter><filter id="iefFeDe" width="4.874" height="6.654" x="16.16" y="12.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7335" stdDeviation=".625"/></filter><filter id="iCn2pje" width="5.026" height="5.864" x="18.807" y="12.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7335" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wilted-flower" /></template>
<style>
.bmiizgb4n {
  stop-color: var(--svg-color--f06d67, #F06D67);
}

.c1i02ccyu {
  stop-color: var(--svg-color--f2706c, #F2706C);
}

.cjya7z99b {
  fill: var(--svg-color--d94043, #D94043);
  d: path("M19.529 7.473c-.786.152-1.576.281-2.36.44a4.45 4.45 0 0 0-3.5 5.23l1.3 6.53c.06.31.37.52.68.45l.99-.2a4.44 4.44 0 0 0 3.372-3.045c.038-.124.209-.157.291-.057a4.45 4.45 0 0 0 4.317 1.552l.98-.19c.32-.06.53-.38.47-.7l-1.3-6.51a4.46 4.46 0 0 0-5.24-3.5");
}

.d2jw3rb0g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M12.986 3.383c1.604-.25 5.075.387 6.125 4.937");
}

.doylssbjv {
  stop-color: var(--svg-color--c37573, #C37573);
}

.dpvpe84ol {
  fill: var(--svg-color--c72534, #C72534);
  d: path("m19.557 12.968l.454 2.793c.297 1.03 2.723 1.815 3.072 1.5c-2.147-.645-3.177-2.687-3.526-4.293");
}

.e47ugq69i {
  stop-color: var(--svg-color--44804b, #44804B);
}

.eheioum6h {
  d: path("M18.074 17.97c1.284-1.229 1.675-3.281 1.71-4.154c-.167 1.257-1.291 2.443-2.373 3.246z");
}

.en_c4ybpw {
  stop-color: var(--svg-color--7eac6f, #7EAC6F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g8_6xqbqu {
  stop-color: var(--svg-color--ee6b66, #EE6B66);
  stop-opacity: 0;
}

.gcvo3w51o {
  stop-color: var(--svg-color--44804b, #44804B);
  stop-opacity: 0;
}

.gjxm3mbag {
  stop-color: var(--svg-color--63961e, #63961E);
  stop-opacity: 0;
}

.h81gcuzsc {
  stop-color: var(--svg-color--306d5e, #306D5E);
}

.i3dcd48zj {
  d: path("M4.424 17.789a3 3 0 0 1 3-3h.672v5.062a3 3 0 0 1-3 3h-.172a.5.5 0 0 1-.5-.5z");
}

.ib5vvvb1o {
  fill: var(--svg-color--aa3358, #AA3358);
  d: path("m20.299 12.863l-.69.14c-.04.01-.06.03-.1.04a.4.4 0 0 0-.19-.01l-.7.14a3.164 3.164 0 0 0-2.49 3.72l.92 4.64c.04.22.26.37.48.32l.7-.14a3.15 3.15 0 0 0 2.402-2.183a.113.113 0 0 1 .193-.037a3.17 3.17 0 0 0 3.074 1.12l.69-.14c.23-.05.38-.27.33-.5l-.92-4.63c-.32-1.71-1.99-2.82-3.7-2.48");
}

.iiyqncanc {
  stop-color: var(--svg-color--cb294b, #CB294B);
  stop-opacity: 0;
}

.jpa7fx5hh {
  stop-color: var(--svg-color--931f3d, #931F3D);
  stop-opacity: 0;
}

.jyl4068xm {
  stop-color: var(--svg-color--c93233, #C93233);
}

.kwwb2c0wr {
  stop-color: var(--svg-color--6c8e37, #6C8E37);
}

.mpy2y5sef {
  stop-color: var(--svg-color--b83230, #B83230);
  stop-opacity: 0;
}

.mpz7ut52e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M24.723 23.116c.75.26 2.25 1.287 2.25 3.312v2.031");
}

.n_otmo27f {
  stop-color: var(--svg-color--7eac6f, #7EAC6F);
}

.occj0325a {
  stop-color: var(--svg-color--931f3d, #931F3D);
}

.ooeangkay {
  stop-color: var(--svg-color--7da244, #7DA244);
}

.oyhm_trkz {
  stop-color: var(--svg-color--be6376, #BE6376);
}

.p1mlabu_v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.986 5.133c-1.593 1.093-2.906 5.843-.531 8.906c3.211 4.14 4.063 4.812 4.063 8.062c0 3.002-1.542 5.625-2.375 6.563");
}

.phhvu5btv {
  stop-color: var(--svg-color--b83230, #B83230);
}

.pt02vrbyz {
  stop-color: var(--svg-color--f06d67, #F06D67);
  stop-opacity: 0;
}

.qbmd_7y2p {
  fill: var(--svg-color--d94045, #D94045);
  d: path("M26.32 29.326h.5c.23 0 .42-.19.42-.42v-3.79a2.59 2.59 0 0 0-2.59-2.59h-.5c-.23 0-.42.19-.42.42v3.79c-.01 1.43 1.16 2.59 2.59 2.59");
}

.qwcin8b7r {
  stop-color: var(--svg-color--70a176, #70A176);
  stop-opacity: 0;
}

.s_sr5lbwb {
  d: path("m25.317 17.67l-1.509-7.249c-.313-1.607-2.07-1.816-2.488-1.607c.392 1.75 1.223 5.643 1.41 7.21c.189 1.568 1.803 1.75 2.587 1.646");
}

.so_ghbbhm {
  stop-color: var(--svg-color--c37573, #C37573);
  stop-opacity: 0;
}

.srn-wtbey {
  stop-color: var(--svg-color--7da244, #7DA244);
  stop-opacity: 0;
}

.t-uhq_evu {
  stop-color: var(--svg-color--aacc8c, #AACC8C);
  stop-opacity: 0;
}

.tozgsv2_d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-6px, 2.6px);
}

.u3apbpbyy {
  stop-color: var(--svg-color--f2706c, #F2706C);
  stop-opacity: 0;
}

.ufdpxem1x {
  d: path("m20.299 12.863l-.69.14c-.04.01-.06.03-.1.04a.4.4 0 0 0-.19-.01l-.7.14a3.164 3.164 0 0 0-2.49 3.72l.92 4.64c.04.22.26.37.48.32l.7-.14a3.15 3.15 0 0 0 2.402-2.183a.113.113 0 0 1 .193-.037a3.17 3.17 0 0 0 3.074 1.12l.69-.14c.23-.05.38-.27.33-.5l-.92-4.63c-.32-1.71-1.99-2.82-3.7-2.48");
}

.v67zr5bie {
  d: path("M18.783 9.022c-.25-2.313-1.916-5.736-6.266-5.586c-5.278.182-5.988 5.118-5.796 6.648c.342 2.743 1.5 4.125 3.25 6.313s2.819 4.608 2.172 8.187c-.247 1.363-1.297 3.032-2.172 3.875");
}

.vh-g-vbvc {
  stop-color: var(--svg-color--cb294b, #CB294B);
}

.vnct225wb {
  stop-color: var(--svg-color--c93233, #C93233);
  stop-opacity: 0;
}

.vwgak1tih {
  stop-color: var(--svg-color--aacc8c, #AACC8C);
}

.wgouexbiv {
  fill: var(--svg-color--7eab39, #7EAB39);
  d: path("M4.424 17.789a3 3 0 0 1 3-3h.672v5.062a3 3 0 0 1-3 3h-.172a.5.5 0 0 1-.5-.5z");
}

.wh8n1dbsf {
  stop-color: var(--svg-color--63961e, #63961E);
}

.x2hzur60y {
  stop-color: var(--svg-color--70a176, #70A176);
}

.x7rlucchp {
  stop-color: var(--svg-color--ee6b66, #EE6B66);
}

.xhqbnza6p {
  d: path("M19.529 7.473c-.786.152-1.576.281-2.36.44a4.45 4.45 0 0 0-3.5 5.23l1.3 6.53c.06.31.37.52.68.45l.99-.2a4.44 4.44 0 0 0 3.372-3.045c.038-.124.209-.157.291-.057a4.45 4.45 0 0 0 4.317 1.552l.98-.19c.32-.06.53-.38.47-.7l-1.3-6.51a4.46 4.46 0 0 0-5.24-3.5");
}

.ynqnmsbwf {
  stop-color: var(--svg-color--7aab27, #7AAB27);
}

.yryj2fb5b {
  stop-color: var(--svg-color--81a551, #81A551);
  stop-opacity: 0;
}

.z22fruy5g {
  d: path("M26.32 29.326h.5c.23 0 .42-.19.42-.42v-3.79a2.59 2.59 0 0 0-2.59-2.59h-.5c-.23 0-.42.19-.42.42v3.79c-.01 1.43 1.16 2.59 2.59 2.59");
}

.z75afk-6m {
  stop-color: var(--svg-color--be6376, #BE6376);
  stop-opacity: 0;
}

.zhdv-abdd {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m20.299 12.863l-.69.14c-.04.01-.06.03-.1.04a.4.4 0 0 0-.19-.01l-.7.14a3.164 3.164 0 0 0-2.49 3.72l.92 4.64c.04.22.26.37.48.32l.7-.14a3.15 3.15 0 0 0 2.402-2.183a.113.113 0 0 1 .193-.037a3.17 3.17 0 0 0 3.074 1.12l.69-.14c.23-.05.38-.27.33-.5l-.92-4.63c-.32-1.71-1.99-2.82-3.7-2.48");
}

</style>
