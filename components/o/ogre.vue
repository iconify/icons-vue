<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRP5dtJ)" class="rr85xtvtm"/><g filter="url(#iu7uErc)"><path class="xjhf-wbud"/></g><path fill="url(#iTyFmte)" class="q8pg0-bhx"/><g filter="url(#ikgQknd)"><path class="w7dn5sdew"/></g><g filter="url(#ih1AmJd)"><path fill="url(#i0B3sgd)" class="dddl3q12p"/></g><g filter="url(#iKfiIWb)"><circle class="khyo0ckwg"/></g><g filter="url(#iEVv0Uc)"><circle class="vfwkojiia"/></g><path fill="url(#ieArFje)" class="boff_8bhq"/><path fill="url(#iCy05fD)" class="boff_8bhq"/><g filter="url(#iCzKpMe)"><path class="kq-du_b5t"/></g><path fill="url(#i4IyEFc)" class="hmgfnlb5z"/><path fill="url(#iBwlR2o)" class="hmgfnlb5z"/><g filter="url(#iF83tfc)"><ellipse transform="rotate(37.755 26.281 4.523)" class="buok4mv1x"/></g><g filter="url(#i8050ic)"><path stroke="url(#iy8zUvd)" class="lxv89sbje"/></g><circle class="k80h9tb_q"/><circle fill="url(#ij0AqWM)" class="yu_8jsbhj"/><circle class="x0kwcrb3p"/><circle fill="url(#isKODVb)" class="tqp9m8bme"/><g filter="url(#iPdPiWK)"><path stroke="url(#iA2lJeQ)" class="qkfzoz8_b"/></g><path fill="url(#iGzwZsc)" class="wc4ium5jt"/><path fill="url(#ijqbyEc)" class="iwb_fz4-n"/><path fill="url(#igLC6yc)" class="iwb_fz4-n"/><g filter="url(#iCCxrfd)"><path class="qe0bk-n4j"/></g><path fill="url(#is0N7Oe)" class="fpwgktulx"/><path fill="url(#iG7ovUD)" class="fmaob3bxk"/><path fill="url(#iHVBPtb)" class="zvkq04bgb"/><path fill="url(#ipDNJue)" class="zvkq04bgb"/><path fill="url(#iX2TTHc)" class="zvkq04bgb"/><path fill="url(#imYtpjd)" class="zvkq04bgb"/><g filter="url(#iulLJOc)"><path clip-rule="evenodd" class="ag180dy6s"/></g><g filter="url(#icO4YZc)"><path clip-rule="evenodd" class="pd-ecdcak"/></g><path fill="url(#iicj1id)" clip-rule="evenodd" class="cv1gpmb_p"/><path fill="url(#i0DYqIb)" clip-rule="evenodd" class="cv1gpmb_p"/><path fill="url(#ie9Ssqr)" clip-rule="evenodd" class="qca164blt"/><path fill="url(#iup4HqP)" clip-rule="evenodd" class="qca164blt"/><g filter="url(#itsQ0Ee)"><path class="ca-pwf-6i"/></g><g filter="url(#i785N6S)"><ellipse transform="rotate(-36.756 12.667 4.72)" class="i8wzljb_u"/></g><g filter="url(#ipku1xb)"><ellipse transform="rotate(-36.756 16.603 4.467)" class="n8wg2nbbd"/></g><g filter="url(#iPgB6wd)"><ellipse transform="rotate(-36.756 20.078 4.863)" class="tst0j8xqm"/></g><g filter="url(#igJigwh)"><ellipse transform="rotate(16.056 25.846 9.224)" class="fj0zjmbnn"/></g><g filter="url(#inuJ1me)"><ellipse transform="rotate(50.11 27.293 12.518)" class="d2f_clbso"/></g><g filter="url(#iHRnRcc)"><ellipse transform="scale(1 -1)rotate(77.194 23.67 9.393)" class="eohpd2i9b"/></g><g filter="url(#iZ5855b)"><ellipse transform="scale(1 -1)rotate(66.061 28.497 11.314)" class="om13zejys"/></g><g filter="url(#ijYkV9c)"><ellipse transform="scale(1 -1)rotate(52.241 35.913 14.974)" class="hcmugabho"/></g><g filter="url(#ijVunMd)"><ellipse transform="scale(1 -1)rotate(18.01 91.419 61.214)" class="s52fmur8t"/></g><g filter="url(#ir7r6pe)"><ellipse fill="url(#imIphyx)" class="cp-xst11a"/></g><g filter="url(#iUfVz1b)"><circle fill="url(#ioJI5Vc)" transform="rotate(-90 16.73 17.73)" class="v7s9jtb3q"/></g><path fill="url(#iwTawRb)" class="tsxn1d77p"/><path fill="url(#i3YBxNb)" class="ntgg_xbqk"/><path fill="url(#iW5gSzU)" class="rwozfg5fg"/><defs><filter id="iu7uErc" width="20.398" height="20.338" x="5.114" y="6.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="ikgQknd" width="5.898" height="5.665" x="19.54" y="6.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="ih1AmJd" width="5.839" height="7.803" x="12.205" y="13.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".375"/></filter><filter id="iKfiIWb" width="8" height="8" x="16.832" y="12.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="iEVv0Uc" width="8" height="8" x="6.504" y="12.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="iCzKpMe" width="5.984" height="6.266" x="5.25" y="3.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="iF83tfc" width="1.497" height="1.524" x="25.533" y="3.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".25"/></filter><filter id="i8050ic" width="5.5" height="7.5" x="13.25" y="13.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".25"/></filter><filter id="iPdPiWK" width="11.3" height="6.3" x="10.35" y="19.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".2"/></filter><filter id="iCCxrfd" width="1.901" height="1.994" x="13.187" y="22.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".25"/></filter><filter id="iulLJOc" width="7.868" height="4.592" x="16.898" y="9.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="icO4YZc" width="7.776" height="4.838" x="6.353" y="9.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="itsQ0Ee" width="1.822" height="1.666" x="12.128" y="10.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".25"/></filter><filter id="i785N6S" width="3.238" height="3.338" x="11.048" y="3.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="ipku1xb" width="3.238" height="3.338" x="14.985" y="2.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="iPgB6wd" width="3.238" height="3.338" x="18.459" y="3.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="igJigwh" width="3.13" height="3.43" x="24.281" y="7.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="inuJ1me" width="3.238" height="3.132" x="25.674" y="10.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="iHRnRcc" width="3.43" height="2.877" x="25.867" y="14.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="iZ5855b" width="3.372" height="2.966" x="25.589" y="17.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="ijYkV9c" width="3.259" height="3.109" x="24.13" y="21.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="ijVunMd" width="2.888" height="3.238" x="21.962" y="23.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".5"/></filter><filter id="ir7r6pe" width="1.672" height="3.609" x="13.664" y="15.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".25"/></filter><filter id="iUfVz1b" width="2.552" height="2.552" x="15.454" y="16.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6816_5279" stdDeviation=".25"/></filter><radialGradient id="iRP5dtJ" cx="0" cy="0" r="1" gradientTransform="matrix(10.5 -24.5 27.01404 11.57745 14 25.77)" gradientUnits="userSpaceOnUse"><stop class="mx_ru4b-l"/><stop offset="1" class="ce2ys6b-o"/></radialGradient><radialGradient id="i0B3sgd" cx="0" cy="0" r="1" gradientTransform="matrix(3.36566 -3.69281 11.9067 10.85186 13.197 22.1)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="k8bsv-t1u"/><stop offset=".845" class="jii98ynbe"/></radialGradient><radialGradient id="ieArFje" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71874 3.12501 -5.06304 -4.4048 9.813 5.563)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="ss1h-7bsz"/><stop offset="1" class="e7-czq9jw"/></radialGradient><radialGradient id="iCy05fD" cx="0" cy="0" r="1" gradientTransform="matrix(-5.73953 2.9063 -4.70868 -9.299 9.813 5.563)" gradientUnits="userSpaceOnUse"><stop offset=".531" class="c-521lbov"/><stop offset=".798" class="rdgf_0b4j"/></radialGradient><radialGradient id="i4IyEFc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.15628 4.43746 -1.12353 -1.05233 26.906 4.375)" gradientUnits="userSpaceOnUse"><stop class="ss1h-7bsz"/><stop offset="1" class="bw7s0bbva"/></radialGradient><radialGradient id="iy8zUvd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26565 4.03124 -2.12898 -1.19654 17.438 14.703)" gradientUnits="userSpaceOnUse"><stop class="ifii67-qc"/><stop offset="1" class="n9f88rb4m"/></radialGradient><radialGradient id="ij0AqWM" cx="0" cy="0" r="1" gradientTransform="rotate(117 0 11)scale(1.1)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="wehfmpbxf"/><stop offset="1" class="dvjh-j01i"/></radialGradient><radialGradient id="isKODVb" cx="0" cy="0" r="1" gradientTransform="rotate(125.446 7.09 13.832)scale(1.1316)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="wehfmpbxf"/><stop offset="1" class="dvjh-j01i"/></radialGradient><radialGradient id="iA2lJeQ" cx="0" cy="0" r="1" gradientTransform="matrix(6.29688 -2.57812 2.1243 5.18845 10.656 23.844)" gradientUnits="userSpaceOnUse"><stop class="g0bmz7kix"/><stop offset="1" class="n9f88rb4m"/></radialGradient><radialGradient id="iGzwZsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96875 10.2882 0 16 24.5)" gradientUnits="userSpaceOnUse"><stop class="cgjme7_4e"/><stop offset="1" class="fi4iq9b6r"/></radialGradient><radialGradient id="iHVBPtb" cx="0" cy="0" r="1" gradientTransform="rotate(115.596 3.825 12.534)scale(5.78665 7.4398)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="zb8ghzb5k"/><stop offset=".547" class="kr1ypmn0o"/><stop offset=".964" class="jii98ynbe"/></radialGradient><radialGradient id="ipDNJue" cx="0" cy="0" r="1" gradientTransform="rotate(-179.334 8.877 8.292)scale(5.37536 17.1675)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="k8bsv-t1u"/><stop offset="1" class="jii98ynbe"/></radialGradient><radialGradient id="iX2TTHc" cx="0" cy="0" r="1" gradientTransform="matrix(-3 -1.125 2.8613 -7.63014 16.5 17.156)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="k8bsv-t1u"/><stop offset="1" class="jii98ynbe"/></radialGradient><radialGradient id="imYtpjd" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 4.9375 -3.6248 2.5236 14.563 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="ewispferf"/><stop offset=".721" class="ewispferf"/><stop offset=".896" class="qq25rtvif"/></radialGradient><radialGradient id="iicj1id" cx="0" cy="0" r="1" gradientTransform="matrix(1.39175 -3.8125 4.75704 1.73655 21.327 13.422)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="ln_ryhb8k"/><stop offset=".715" class="ek9x88buf"/><stop offset=".823" class="dwv9sjy2u"/></radialGradient><radialGradient id="ie9Ssqr" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -4.09375 5.10797 1.59868 10.156 13)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="ln_ryhb8k"/><stop offset=".823" class="dwv9sjy2u"/></radialGradient><radialGradient id="imIphyx" cx="0" cy="0" r="1" gradientTransform="rotate(178.043 7.372 9.025)scale(.94295 4.58247)" gradientUnits="userSpaceOnUse"><stop class="n9f88rb4m"/><stop offset="1" class="o53ap5b2m"/></radialGradient><radialGradient id="ioJI5Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64063 -3.30783 0 16.616 16.125)" gradientUnits="userSpaceOnUse"><stop class="n9f88rb4m"/><stop offset="1" class="o53ap5b2m"/></radialGradient><linearGradient id="iTyFmte" x1="24.5" x2="9" y1="14" y2="24" gradientUnits="userSpaceOnUse"><stop class="yhi7ofb_k"/><stop offset=".327" class="zb8ghzb5k"/><stop offset="1" class="jii98ynbe"/></linearGradient><linearGradient id="iBwlR2o" x1="25.5" x2="21" y1="8.875" y2="4.563" gradientUnits="userSpaceOnUse"><stop offset=".454" class="c-521lbov"/><stop offset=".67" class="rdgf_0b4j"/></linearGradient><linearGradient id="ijqbyEc" x1="21.578" x2="12.354" y1="19.781" y2="16.21" gradientUnits="userSpaceOnUse"><stop offset=".13" class="q7naokbib"/><stop offset=".276" class="vc--wpv5i"/><stop offset=".604" class="vc--wpv5i"/><stop offset=".786" class="q7naokbib"/></linearGradient><linearGradient id="igLC6yc" x1="14.984" x2="15.359" y1="18.813" y2="22.01" gradientUnits="userSpaceOnUse"><stop class="q7naokbib"/><stop offset=".667" class="vlntctbah"/></linearGradient><linearGradient id="is0N7Oe" x1="14.688" x2="13.797" y1="23.094" y2="23.469" gradientUnits="userSpaceOnUse"><stop offset=".282" class="vc--wpv5i"/><stop offset=".849" class="q7naokbib"/></linearGradient><linearGradient id="iG7ovUD" x1="18.25" x2="16.875" y1="23.109" y2="23.297" gradientUnits="userSpaceOnUse"><stop offset=".282" class="vc--wpv5i"/><stop offset=".849" class="q7naokbib"/></linearGradient><linearGradient id="i0DYqIb" x1="17.297" x2="19.859" y1="11.891" y2="9.906" gradientUnits="userSpaceOnUse"><stop class="mx_ru4b-l"/><stop offset=".979" class="x09681b_t"/></linearGradient><linearGradient id="iup4HqP" x1="9.469" x2="11.406" y1="14.25" y2="11.156" gradientUnits="userSpaceOnUse"><stop class="mx_ru4b-l"/><stop offset=".979" class="x09681b_t"/></linearGradient><linearGradient id="iwTawRb" x1="17.477" x2="18.99" y1="22.18" y2="21.601" gradientUnits="userSpaceOnUse"><stop offset=".588" class="q7naokbib"/><stop offset=".877" class="vlntctbah"/></linearGradient><linearGradient id="i3YBxNb" x1="14.523" x2="13.01" y1="22.18" y2="21.601" gradientUnits="userSpaceOnUse"><stop offset=".552" class="q7naokbib"/><stop offset=".829" class="vlntctbah"/></linearGradient><linearGradient id="iW5gSzU" x1="18.809" x2="18.864" y1="20.258" y2="19.828" gradientUnits="userSpaceOnUse"><stop class="vlntctbah"/><stop offset="1" class="q7naokbib"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ogre" /></template>
<style>
.ag180dy6s {
  fill: var(--svg-color--80144a, #80144A);
  fill-rule: evenodd;
  d: path("M20.62 11.86c-.774-.048-1.467.205-1.802.47a.568.568 0 1 1-.704-.89c.581-.46 1.56-.776 2.575-.713c1.045.064 2.168.533 2.975 1.691a.568.568 0 0 1-.932.65c-.584-.839-1.368-1.162-2.113-1.208");
}

.boff_8bhq {
  d: path("M9.82 9.727c-.866.692-1.735.686-2.136.634a.42.42 0 0 1-.32-.257l-2.2-5.042c-.305-.699.505-1.354 1.124-.91l4.444 3.19c.123.088.2.228.185.378A2.92 2.92 0 0 1 9.82 9.727");
}

.buok4mv1x {
  cx: 26.281px;
  cy: 4.523px;
  fill: var(--svg-color--fff5c1, #FFF5C1);
  rx: 0.227px;
  ry: 0.281px;
}

.bw7s0bbva {
  stop-color: var(--svg-color--f5a629, #F5A629);
}

.c-521lbov {
  stop-color: var(--svg-color--be7b12, #BE7B12);
  stop-opacity: 0;
}

.ca-pwf-6i {
  stroke: var(--svg-color--974d96, #974D96);
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.25 11.438c-.135-.11-.266-.266-.422-.266");
}

.ce2ys6b-o {
  stop-color: var(--svg-color--943490, #943490);
}

.cgjme7_4e {
  stop-color: var(--svg-color--5f1c9e, #5F1C9E);
}

.cp-xst11a {
  cx: 14.5px;
  cy: 17.43px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.336px;
  ry: 1.305px;
}

.cv1gpmb_p {
  fill-rule: evenodd;
  d: path("M21.102 11.468c-.816-.051-1.549.216-1.903.496a.6.6 0 0 1-.744-.941c.614-.486 1.648-.82 2.722-.753c1.103.068 2.29.563 3.142 1.787a.6.6 0 0 1-.984.686c-.617-.886-1.446-1.227-2.233-1.275");
}

.d2f_clbso {
  cx: 27.293px;
  cy: 12.518px;
  fill: var(--svg-color--a354a0, #A354A0);
  rx: 0.418px;
  ry: 0.727px;
}

.dddl3q12p {
  d: path("M13.004 17.826c.202-1.568 1.536-3.52 2.6-3.383c1.065.138 1.86 2.364 1.659 3.932c-.202 1.567-.87 2.543-2.467 2.337s-1.995-1.32-1.792-2.886");
}

.dvjh-j01i {
  stop-color: var(--svg-color--3e1c66, #3E1C66);
}

.dwv9sjy2u {
  stop-color: var(--svg-color--91349d, #91349D);
}

.e7-czq9jw {
  stop-color: var(--svg-color--e6920e, #E6920E);
}

.ek9x88buf {
  stop-color: var(--svg-color--974d96, #974D96);
}

.eohpd2i9b {
  fill: var(--svg-color--a354a0, #A354A0);
  rx: 0.418px;
  ry: 0.727px;
}

.ewispferf {
  stop-color: var(--svg-color--f3829a, #F3829A);
  stop-opacity: 0;
}

.fi4iq9b6r {
  stop-color: var(--svg-color--4e038a, #4E038A);
}

.fj0zjmbnn {
  cx: 25.846px;
  cy: 9.224px;
  fill: var(--svg-color--a354a0, #A354A0);
  rx: 0.549px;
  ry: 0.727px;
}

.fmaob3bxk {
  d: path("M18 23.804v-.495a.31.31 0 0 0-.585-.138l-.282.564a.41.41 0 0 0 .658.474l.07-.07a.47.47 0 0 0 .139-.335");
}

.fpwgktulx {
  d: path("M14 23.804v-.495a.31.31 0 0 1 .585-.138l.282.564a.41.41 0 0 1-.658.474l-.07-.07a.47.47 0 0 1-.139-.335");
}

.ft5dv1b6b {
  fill: none;
}

.g0bmz7kix {
  stop-color: var(--svg-color--fc9bb3, #FC9BB3);
  stop-opacity: 0.4;
}

.hcmugabho {
  fill: var(--svg-color--a354a0, #A354A0);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.418px;
  ry: 0.727px;
}

.hmgfnlb5z {
  d: path("M22.107 9.727c.866.692 1.735.686 2.136.634a.42.42 0 0 0 .32-.257l2.2-5.042c.305-.699-.505-1.354-1.124-.91l-4.444 3.19a.42.42 0 0 0-.185.378a2.92 2.92 0 0 0 1.097 2.007");
}

.i8wzljb_u {
  cx: 12.667px;
  cy: 4.72px;
  fill: var(--svg-color--a354a0, #A354A0);
  rx: 0.549px;
  ry: 0.727px;
}

.ifii67-qc {
  stop-color: var(--svg-color--fc9bb3, #FC9BB3);
}

.iwb_fz4-n {
  d: path("M13 21.84V20h6v1.84a.2.2 0 0 1-.366.11L18 21h-4l-.634.95a.2.2 0 0 1-.366-.11");
}

.jii98ynbe {
  stop-color: var(--svg-color--7c124a, #7C124A);
}

.k80h9tb_q {
  cx: 11px;
  cy: 16px;
  r: 3px;
  fill: var(--svg-color--fff, #fff);
}

.k8bsv-t1u {
  stop-color: var(--svg-color--7c124a, #7C124A);
  stop-opacity: 0;
}

.khyo0ckwg {
  cx: 20.832px;
  cy: 16.339px;
  r: 3px;
  fill: var(--svg-color--80144a, #80144A);
}

.kq-du_b5t {
  stroke: var(--svg-color--ffea99, #FFEA99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m6.5 4.906l3.484 3.766");
}

.kr1ypmn0o {
  stop-color: var(--svg-color--bc1b51, #BC1B51);
}

.ln_ryhb8k {
  stop-color: var(--svg-color--56235f, #56235F);
}

.lxv89sbje {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16 13.875c-.292 0-.571.146-.818.368a3.4 3.4 0 0 0-.667.885c-.383.703-.64 1.598-.64 2.372c0 .76.126 1.416.46 1.885c.342.478.884.74 1.665.74c.78 0 1.323-.262 1.664-.74c.335-.469.461-1.125.461-1.885c0-.774-.257-1.67-.64-2.372a3.4 3.4 0 0 0-.667-.885c-.247-.222-.526-.368-.818-.368Z");
}

.mx_ru4b-l {
  stop-color: var(--svg-color--211965, #211965);
}

.n8wg2nbbd {
  cx: 16.603px;
  cy: 4.467px;
  fill: var(--svg-color--a354a0, #A354A0);
  rx: 0.549px;
  ry: 0.727px;
}

.n9f88rb4m {
  stop-color: var(--svg-color--de5073, #DE5073);
  stop-opacity: 0;
}

.ntgg_xbqk {
  d: path("m13.344 21.984l.219-1.336l.068.128c.073.136.215.22.369.22z");
}

.o53ap5b2m {
  stop-color: var(--svg-color--fc9bb3, #FC9BB3);
  stop-opacity: 0.75;
}

.om13zejys {
  fill: var(--svg-color--a354a0, #A354A0);
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  rx: 0.418px;
  ry: 0.727px;
}

.pd-ecdcak {
  fill: var(--svg-color--80144a, #80144A);
  fill-rule: evenodd;
  d: path("M10.414 11.79c.766-.115 1.478.078 1.835.313a.568.568 0 0 0 .625-.948c-.619-.408-1.62-.64-2.627-.489c-1.035.154-2.114.717-2.818 1.941a.568.568 0 1 0 .984.566c.51-.885 1.263-1.274 2.001-1.384");
}

.q7naokbib {
  stop-color: var(--svg-color--bab6c2, #BAB6C2);
}

.q8pg0-bhx {
  d: path("m7.145 11.273l-.262 1.31a20 20 0 0 0 .21 8.786a5.46 5.46 0 0 0 4.62 4.095l1.558.195c1.812.226 3.646.226 5.458 0l1.557-.195a5.46 5.46 0 0 0 4.622-4.095c.719-2.877.79-5.877.209-8.785l-.276-1.38a6 6 0 0 0-5.09-4.77l-.515-.07a22 22 0 0 0-5.478-.041l-1.43.168a6 6 0 0 0-5.183 4.782");
}

.qca164blt {
  fill-rule: evenodd;
  d: path("M10.825 11.468c.816-.051 1.549.216 1.903.496a.6.6 0 0 0 .744-.941c-.614-.486-1.648-.82-2.722-.753c-1.103.068-2.29.563-3.142 1.787a.6.6 0 0 0 .984.686c.617-.886 1.446-1.227 2.233-1.275");
}

.qe0bk-n4j {
  fill: var(--svg-color--281b68, #281B68);
  d: path("m14.035 24.005l-.313-.487a.22.22 0 0 1 .347-.266l.453.497a.254.254 0 0 1-.302.398l-.06-.03a.3.3 0 0 1-.125-.112");
}

.qkfzoz8_b {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11 19.875h-.125V20H11h-.125v.016l.001.044q.002.058.01.164a6.3 6.3 0 0 0 .627 2.332c.32.64.802 1.283 1.527 1.767c.726.484 1.688.802 2.96.802s2.234-.318 2.96-.802c.725-.484 1.207-1.127 1.527-1.767s.479-1.277.558-1.754a6 6 0 0 0 .08-.786v-.015L21 20h.125v-.125z");
}

.qq25rtvif {
  stop-color: var(--svg-color--ffc5d1, #FFC5D1);
}

.rdgf_0b4j {
  stop-color: var(--svg-color--be7b12, #BE7B12);
}

.rr85xtvtm {
  d: path("M17.09 3.195a1.61 1.61 0 0 0 1.76.279a1.61 1.61 0 0 1 2.073.674c.318.565.943.883 1.587.81a1.61 1.61 0 0 1 1.763 1.28a1.61 1.61 0 0 0 1.26 1.259a1.61 1.61 0 0 1 1.28 1.764a1.61 1.61 0 0 0 .81 1.587a1.61 1.61 0 0 1 .673 2.072c-.269.59-.16 1.282.279 1.76a1.61 1.61 0 0 1 0 2.18a1.61 1.61 0 0 0-.279 1.76a1.61 1.61 0 0 1-.674 2.073a1.61 1.61 0 0 0-.809 1.587a1.61 1.61 0 0 1-1.28 1.764a1.61 1.61 0 0 0-1.26 1.26a1.61 1.61 0 0 1-1.763 1.28a1.61 1.61 0 0 0-1.587.809a1.61 1.61 0 0 1-2.073.674a1.61 1.61 0 0 0-1.76.278a1.61 1.61 0 0 1-2.18 0a1.61 1.61 0 0 0-1.76-.278a1.61 1.61 0 0 1-2.073-.674a1.61 1.61 0 0 0-1.587-.81a1.61 1.61 0 0 1-1.764-1.28a1.61 1.61 0 0 0-1.259-1.26a1.61 1.61 0 0 1-1.28-1.763a1.61 1.61 0 0 0-.81-1.587a1.61 1.61 0 0 1-.673-2.073a1.61 1.61 0 0 0-.279-1.76a1.61 1.61 0 0 1 0-2.18a1.61 1.61 0 0 0 .279-1.76a1.61 1.61 0 0 1 .674-2.072c.564-.319.882-.944.809-1.587a1.61 1.61 0 0 1 1.28-1.764a1.61 1.61 0 0 0 1.26-1.26a1.61 1.61 0 0 1 1.763-1.28a1.61 1.61 0 0 0 1.587-.81a1.61 1.61 0 0 1 2.073-.673c.59.269 1.282.16 1.76-.279a1.61 1.61 0 0 1 2.18 0");
}

.rwozfg5fg {
  d: path("M19.008 20.805v-.813h-.399z");
}

.s52fmur8t {
  fill: var(--svg-color--a354a0, #A354A0);
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  rx: 0.418px;
  ry: 0.636px;
}

.ss1h-7bsz {
  stop-color: var(--svg-color--fcd53f, #FCD53F);
}

.tqp9m8bme {
  cx: 22.25px;
  cy: 16.25px;
  r: 0.75px;
}

.tst0j8xqm {
  cx: 20.078px;
  cy: 4.863px;
  fill: var(--svg-color--a354a0, #A354A0);
  rx: 0.549px;
  ry: 0.727px;
}

.tsxn1d77p {
  d: path("m18.656 21.984l-.187-1.601l-.037.242a.44.44 0 0 1-.432.371z");
}

.v7s9jtb3q {
  cx: 16.73px;
  cy: 17.73px;
  r: 0.776px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vfwkojiia {
  cx: 10.504px;
  cy: 16.339px;
  r: 3px;
  fill: var(--svg-color--80144a, #80144A);
}

.vlntctbah {
  stop-color: var(--svg-color--bab6c2, #BAB6C2);
  stop-opacity: 0;
}

.w7dn5sdew {
  fill: var(--svg-color--87164b, #87164B);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M23.656 10.773c-.444.064-1.247-.224-2.015-.984c-.582-.575-1.056-1.423-1.094-1.89c-.012-.152-.022-.21.101-.297l.727-.485c1.5.69 2.537 1.797 3.063 3.394l-.258.15c-.211.042-.378.091-.524.112");
}

.wc4ium5jt {
  d: path("M21 20H11s0 5 5 5s5-5 5-5");
}

.wehfmpbxf {
  stop-color: var(--svg-color--6d2c78, #6D2C78);
}

.x09681b_t {
  stop-color: var(--svg-color--211965, #211965);
  stop-opacity: 0;
}

.x0kwcrb3p {
  cx: 21px;
  cy: 16px;
  r: 3px;
  fill: var(--svg-color--fff, #fff);
}

.xjhf-wbud {
  fill: var(--svg-color--341a4f, #341A4F);
  d: path("m6.68 12.53l-.182.873a18.4 18.4 0 0 0 .206 8.356a5.01 5.01 0 0 0 4.252 3.717l1.728.208a22 22 0 0 0 5.258 0l1.727-.208a5.01 5.01 0 0 0 4.253-3.717c.709-2.733.78-5.592.205-8.356l-.195-.94a6 6 0 0 0-5.11-4.73l-.389-.05a22 22 0 0 0-5.277-.04l-1.278.145a6 6 0 0 0-5.199 4.741");
}

.yhi7ofb_k {
  stop-color: var(--svg-color--de3c65, #DE3C65);
}

.yu_8jsbhj {
  cx: 9.75px;
  cy: 16.25px;
  r: 0.75px;
}

.zb8ghzb5k {
  stop-color: var(--svg-color--cc2a4c, #CC2A4C);
}

.zvkq04bgb {
  d: path("M14 17.5c0-1.5 1-3.5 2-3.5s2 2 2 3.5s-.5 2.5-2 2.5s-2-1-2-2.5");
}

</style>
