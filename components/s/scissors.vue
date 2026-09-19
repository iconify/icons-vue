<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQSSONo)"><path fill="url(#ixvg80c)" class="zvdwesv-a"/><path fill="url(#iyjSfOd)" class="zvdwesv-a"/></g><g filter="url(#io1K2Zd)"><path fill="url(#igTTqee)" class="k9xrklkbn"/></g><g filter="url(#ic5iZSy)"><path fill="url(#iDeNeHb)" class="hctmw7b3a"/></g><g filter="url(#iHvZk6d)"><path class="mcc-x4b5h"/><path fill="url(#ixiQ3fd)" class="x7xwacb6x"/><path fill="url(#iGbX5Zd)" class="x7xwacb6x"/><path fill="url(#iLRtGRd)" class="x7xwacb6x"/><path fill="url(#ib2Dmgd)" class="x7xwacb6x"/></g><g filter="url(#iMFOD4c)"><path fill="url(#ixMZgYU)" class="lu60sbbrg"/></g><g filter="url(#iuf87pb)"><circle stroke="url(#iIr68rd)" class="tu12e6j2c"/><circle stroke="url(#ikhkgEc)" class="tu12e6j2c"/></g><g filter="url(#igNMboF)"><circle stroke="url(#iolsV5b)" transform="rotate(-4.455 23.693 9.32)" class="y50abw-8k"/><circle stroke="url(#iFKWO4o)" transform="rotate(-4.455 23.693 9.32)" class="y50abw-8k"/></g><g filter="url(#i2vuadd)"><path class="seidu0bmr"/></g><g filter="url(#iZUOn3c)"><path stroke="url(#ipouUCc)" class="ssdwlob0n"/></g><defs><linearGradient id="ixvg80c" x1="8.643" x2="11.924" y1="21.009" y2="24.134" gradientUnits="userSpaceOnUse"><stop class="edivarbxd"/><stop offset="1" class="bemwgefkr"/></linearGradient><linearGradient id="iyjSfOd" x1="14.908" x2="14.315" y1="19.087" y2="19.634" gradientUnits="userSpaceOnUse"><stop offset=".607" class="dt7rchboz"/><stop offset="1" class="aw-my4e9s"/></linearGradient><linearGradient id="igTTqee" x1="29.58" x2="18.904" y1="10.177" y2="10.177" gradientUnits="userSpaceOnUse"><stop class="jqsb4ga_s"/><stop offset="1" class="jiz5jk5hr"/></linearGradient><linearGradient id="iDeNeHb" x1="18.088" x2="20.923" y1="22.384" y2="19.276" gradientUnits="userSpaceOnUse"><stop class="w-b8xp96a"/><stop offset="1" class="bkdraibqt"/></linearGradient><linearGradient id="ixMZgYU" x1="15.815" x2="5.018" y1="10.177" y2="10.177" gradientUnits="userSpaceOnUse"><stop class="jqsb4ga_s"/><stop offset="1" class="jiz5jk5hr"/></linearGradient><linearGradient id="iIr68rd" x1="14.236" x2="9.948" y1="5.856" y2="8.899" gradientUnits="userSpaceOnUse"><stop class="dkc0gmb6n"/><stop offset="1" class="ky6y_6bup"/></linearGradient><linearGradient id="ikhkgEc" x1="4.075" x2="6.398" y1="11.251" y2="10.375" gradientUnits="userSpaceOnUse"><stop class="q1nihq52m"/><stop offset="1" class="ejzxs_9rq"/></linearGradient><linearGradient id="iolsV5b" x1="28.973" x2="24.642" y1="5.875" y2="8.948" gradientUnits="userSpaceOnUse"><stop class="dkc0gmb6n"/><stop offset="1" class="ky6y_6bup"/></linearGradient><linearGradient id="iFKWO4o" x1="18.711" x2="21.057" y1="11.323" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="q1nihq52m"/><stop offset="1" class="ejzxs_9rq"/></linearGradient><linearGradient id="ipouUCc" x1="18.048" x2="20.328" y1="12.661" y2="17.076" gradientUnits="userSpaceOnUse"><stop class="epx7umbpa"/><stop offset="1" class="mqvbfoboq"/></linearGradient><filter id="iQSSONo" width="16.953" height="18.34" x="4.338" y="11.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.521569 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23328"/></filter><filter id="io1K2Zd" width="14.308" height="14.106" x="15.672" y="3.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.211765 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23328"/></filter><filter id="ic5iZSy" width="16.936" height="18.45" x="9.89" y="11.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.592157 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.52549 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23328" result="effect2_innerShadow_18_23328"/></filter><filter id="iHvZk6d" width="2.54" height="2.54" x="14.19" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.419608 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_23328"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_23328" result="shape"/></filter><filter id="iMFOD4c" width="14.469" height="14.111" x="1.58" y="3.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.211765 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23328"/></filter><filter id="iuf87pb" width="11.616" height="11.616" x="3.2" y="3.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23328" stdDeviation=".25"/></filter><filter id="igNMboF" width="11.715" height="11.715" x="17.836" y="3.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23328" stdDeviation=".25"/></filter><filter id="i2vuadd" width="4.09" height="3.897" x="10.195" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23328" stdDeviation=".25"/></filter><filter id="iZUOn3c" width="3.982" height="4.012" x="17.026" y="11.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23328" stdDeviation=".25"/></filter><radialGradient id="ixiQ3fd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 1.04688 -.9606 -.94625 15.643 16.946)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="e16-o6b2v"/><stop offset=".86" class="k49flektc"/></radialGradient><radialGradient id="iGbX5Zd" cx="0" cy="0" r="1" gradientTransform="rotate(-68.142 21.066 -1.984)scale(1.33134 1.18753)" gradientUnits="userSpaceOnUse"><stop class="xt5anpbcw"/><stop offset="1" class="i5b31txkq"/></radialGradient><radialGradient id="iLRtGRd" cx="0" cy="0" r="1" gradientTransform="rotate(139.617 4.867 11.391)scale(.5185)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="bcqtv6biu"/><stop offset="1" class="eq11nvbev"/></radialGradient><radialGradient id="ib2Dmgd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.859 21.426 -3.06)scale(1.91019)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="vr5m0lbje"/><stop offset="1" class="bk2pqqyeb"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scissors" /></template>
<style>
.aw-my4e9s {
  stop-color: var(--svg-color--7c549c, #7C549C);
  stop-opacity: 0;
}

.bcqtv6biu {
  stop-color: var(--svg-color--b9aec4, #B9AEC4);
}

.bemwgefkr {
  stop-color: var(--svg-color--bda7d4, #BDA7D4);
}

.bk2pqqyeb {
  stop-color: var(--svg-color--a49ea6, #A49EA6);
}

.bkdraibqt {
  stop-color: var(--svg-color--879, #879);
}

.dkc0gmb6n {
  stop-color: var(--svg-color--ff8c72, #FF8C72);
}

.dt7rchboz {
  stop-color: var(--svg-color--7c549c, #7C549C);
}

.e16-o6b2v {
  stop-color: var(--svg-color--988098, #988098);
  stop-opacity: 0;
}

.edivarbxd {
  stop-color: var(--svg-color--877697, #877697);
}

.ejzxs_9rq {
  stop-color: var(--svg-color--ff638f, #FF638F);
  stop-opacity: 0;
}

.epx7umbpa {
  stop-color: var(--svg-color--db236e, #DB236E);
}

.eq11nvbev {
  stop-color: var(--svg-color--b9aec4, #B9AEC4);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hctmw7b3a {
  d: path("M25.16 29.7L9.94 14.48l3-3.13l12.84 12.84c1.32 1.32 1.33 3.57.02 4.88z");
}

.i5b31txkq {
  stop-color: var(--svg-color--926bb4, #926BB4);
  stop-opacity: 0;
}

.jiz5jk5hr {
  stop-color: var(--svg-color--f63178, #F63178);
}

.jqsb4ga_s {
  stop-color: var(--svg-color--ff7415, #FF7415);
}

.k49flektc {
  stop-color: var(--svg-color--988098, #988098);
}

.k9xrklkbn {
  d: path("M15.792 13.652a.4.4 0 0 0-.002.568l2.809 2.809a.4.4 0 0 0 .568-.003l1.135-1.157a.42.42 0 0 1 .465-.086c4.037 1.714 8.813-1.994 8.813-6.223c0-3.6-2.9-6.52-6.5-6.52s-6.52 2.92-6.52 6.52c0 .897.162 1.707.491 2.47a.42.42 0 0 1-.084.464zM20.04 9.56c0-1.67 1.36-3.03 3.03-3.03s3.03 1.36 3.03 3.03s-1.36 3.03-3.03 3.03s-3.03-1.35-3.03-3.03");
}

.ky6y_6bup {
  stop-color: var(--svg-color--ff8c72, #FF8C72);
  stop-opacity: 0;
}

.lu60sbbrg {
  d: path("M14.387 12.37a.42.42 0 0 1-.088-.444C16.164 7.144 12.334 3.04 8.08 3.04c-3.6 0-6.5 2.92-6.5 6.52s2.9 6.52 6.5 6.52c.896 0 1.543-.004 2.271-.3a.43.43 0 0 1 .461.084L12 17.036a.4.4 0 0 0 .563-.001l2.969-2.953a.4.4 0 0 0 0-.567zm-6.297.22c-1.67 0-3.03-1.36-3.03-3.03s1.36-3.03 3.03-3.03s3.03 1.36 3.03 3.03c0 1.68-1.36 3.03-3.03 3.03");
}

.mcc-x4b5h {
  fill: var(--svg-color--a79aac, #A79AAC);
  d: path("M15.56 18.14a1.07 1.07 0 1 0 0-2.14a1.07 1.07 0 0 0 0 2.14");
}

.mqvbfoboq {
  stop-color: var(--svg-color--db236e, #DB236E);
  stop-opacity: 0;
}

.q1nihq52m {
  stop-color: var(--svg-color--ff638f, #FF638F);
}

.seidu0bmr {
  stroke: var(--svg-color--ff683c, #FF683C);
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M10.901 14.872c.498-.327 1.714-1.255 2.592-2.349");
}

.ssdwlob0n {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.284 15.142c-.479-.355-1.639-1.351-2.453-2.493");
}

.tu12e6j2c {
  cx: 9.008px;
  cy: 9.268px;
  r: 4.933px;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.vr5m0lbje {
  stop-color: var(--svg-color--a49ea6, #A49EA6);
  stop-opacity: 0;
}

.w-b8xp96a {
  stop-color: var(--svg-color--b59fca, #B59FCA);
}

.x7xwacb6x {
  d: path("M15.56 18.14a1.07 1.07 0 1 0 0-2.14a1.07 1.07 0 0 0 0 2.14");
}

.xt5anpbcw {
  stop-color: var(--svg-color--926bb4, #926BB4);
}

.y50abw-8k {
  cx: 23.693px;
  cy: 9.321px;
  r: 4.982px;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.zvdwesv-a {
  d: path("m6.02 29.7l15.22-15.22l-3.07-3.07L5.32 24.25a3.36 3.36 0 0 0 0 4.75z");
}

</style>
