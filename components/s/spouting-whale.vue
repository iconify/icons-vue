<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vrdwxussr"/><path fill="url(#ixAV0eX)" class="w3b25ubed"/><path fill="url(#i0uoNfc)" class="w3b25ubed"/><path class="ttes9lb2s"/><path fill="url(#iYXPBsd)" class="ekfwxce8e"/><path fill="url(#iTH5qzb)" class="ekfwxce8e"/><path fill="url(#iHGHvAb)" class="ekfwxce8e"/><path fill="url(#iekC7Fc)" class="ekfwxce8e"/><path fill="url(#i6o6P3c)" class="ekfwxce8e"/><path fill="url(#iBkAtyc)" class="ekfwxce8e"/><path fill="url(#iuypQbd)" class="ekfwxce8e"/><path fill="url(#iJwNeBe)" class="rfwb5yb1b"/><path fill="url(#iH9DNYd)" class="ekfwxce8e"/><path fill="url(#iIxZhWd)" class="ekfwxce8e"/><path fill="url(#iaXGYgb)" class="ekfwxce8e"/><g filter="url(#iIvnwEb)"><path fill="url(#ia9Jk2c)" class="f0vgg2xqd"/></g><path fill="url(#i1aPCzc)" class="rz069gxzj"/><path fill="url(#iSBZSSd)" class="rz069gxzj"/><path fill="url(#i683Rpb)" class="ke9ydz2on"/><path fill="url(#iU52Vpc)" class="ke9ydz2on"/><path fill="url(#iAhuTAb)" class="ke9ydz2on"/><path fill="url(#ik74Fuc)" class="quaymfbgj"/><path fill="url(#iAvWmBb)" class="quaymfbgj"/><path fill="url(#itjlTGc)" class="quaymfbgj"/><path fill="url(#iINShPc)" class="quaymfbgj"/><path fill="url(#iE1kt6b)" class="quaymfbgj"/><path fill="url(#iMIIDdB)" class="quaymfbgj"/><path fill="url(#iPlLW6w)" class="quaymfbgj"/><path fill="url(#ikeVaZy)" class="quaymfbgj"/><path fill="url(#iTy7y4b)" clip-rule="evenodd" class="moia-pxqs"/><path fill="url(#iVjyxce)" clip-rule="evenodd" class="moia-pxqs"/><path fill="url(#iOdNGvc)" clip-rule="evenodd" class="moia-pxqs"/><path fill="url(#iR9L3gv)" clip-rule="evenodd" class="moia-pxqs"/><path fill="url(#iqGjD8b)" clip-rule="evenodd" class="moia-pxqs"/><g filter="url(#i9uD2Rd)"><rect class="ckk9u0b6o"/></g><rect fill="url(#iLuCV5c)" class="kcptipb5r"/><rect fill="url(#izWq1Pq)" class="kcptipb5r"/><rect fill="url(#ik6DLMk)" class="kcptipb5r"/><g filter="url(#ib9weze)"><path stroke="url(#ila1MQd)" class="eyg6k3rpa"/></g><g filter="url(#iSkn8Ie)"><path stroke="url(#ixPEqBe)" class="pylso49mr"/></g><path fill="url(#iUKMHUL)" class="tfpnsz75a"/><g filter="url(#ijai4Wb)"><path class="qov12mbvm"/></g><g filter="url(#iuydWac)"><path stroke="url(#iErMygc)" class="tiqsh0b-x"/></g><path fill="url(#iOgSKde)" class="c4fnxk4qp"/><path fill="url(#iNWhBkc)" class="c4fnxk4qp"/><path fill="url(#iaAjT7b)" class="c4fnxk4qp"/><g filter="url(#iVYorXd)"><path stroke="url(#i8qRZUd)" class="ohl1r9i_j"/></g><g filter="url(#iEKMmxc)"><path fill="url(#iHv6JXd)" class="hc96dbbbl"/></g><g filter="url(#iek6Ykc)"><path stroke="url(#ib2SPjd)" class="aoi8p1bwy"/></g><defs><radialGradient id="i0uoNfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53123 -3.1875 4.18224 -2.0091 7.25 30.799)" gradientUnits="userSpaceOnUse"><stop class="og--5td9h"/><stop offset="1" class="n1axymduk"/></radialGradient><radialGradient id="iYXPBsd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31253 -6.81249 6.43613 -2.18477 17.25 24.549)" gradientUnits="userSpaceOnUse"><stop class="uad4m6b5q"/><stop offset="1" class="lopv8fbmk"/></radialGradient><radialGradient id="iTH5qzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56245 10.0665 -7.10801 -.39715 24.188 6.048)" gradientUnits="userSpaceOnUse"><stop class="x_pv3sf4t"/><stop offset="1" class="fa8ea7bop"/></radialGradient><radialGradient id="iHGHvAb" cx="0" cy="0" r="1" gradientTransform="matrix(3.3125 2.8125 -4.61089 5.4306 3.25 11.986)" gradientUnits="userSpaceOnUse"><stop class="sdai-tsgn"/><stop offset="1" class="bbubqtb2u"/></radialGradient><radialGradient id="iekC7Fc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 23.868 3.788)scale(6.27557 4.38106)" gradientUnits="userSpaceOnUse"><stop class="s6314fb-d"/><stop offset="1" class="fo4vqjbkf"/></radialGradient><radialGradient id="i6o6P3c" cx="0" cy="0" r="1" gradientTransform="rotate(91.909 3.59 19.488)scale(3.75208 3.49806)" gradientUnits="userSpaceOnUse"><stop class="fq4l2lbhq"/><stop offset="1" class="yjz3xubja"/></radialGradient><radialGradient id="iBkAtyc" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 6.4375 -2.39117 .78932 22.625 11.986)" gradientUnits="userSpaceOnUse"><stop class="fq4l2lbhq"/><stop offset="1" class="yjz3xubja"/></radialGradient><radialGradient id="iuypQbd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.78124 -3.09376 3.52565 -3.1695 19.938 28.33)" gradientUnits="userSpaceOnUse"><stop class="zvbcy9_1n"/><stop offset="1" class="bo9lsbq4t"/></radialGradient><radialGradient id="iJwNeBe" cx="0" cy="0" r="1" gradientTransform="matrix(5.0625 -3.1875 2.43582 3.86866 23.313 23.486)" gradientUnits="userSpaceOnUse"><stop class="d488k4bvr"/><stop offset="1" class="d5ixqnxpw"/></radialGradient><radialGradient id="iH9DNYd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.621 12.693 2.464)scale(2.03737 1.5227)" gradientUnits="userSpaceOnUse"><stop class="b4lrzy-of"/><stop offset="1" class="xw5qqnbnj"/></radialGradient><radialGradient id="iIxZhWd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.27644 4.87502 -5.28831 -7.89333 15.558 14.268)" gradientUnits="userSpaceOnUse"><stop class="joxkjnbrh"/><stop offset="1" class="zhvex1b1e"/></radialGradient><radialGradient id="iaXGYgb" cx="0" cy="0" r="1" gradientTransform="matrix(5.8125 -5.75 1.7741 1.79338 25.813 27.236)" gradientUnits="userSpaceOnUse"><stop class="qzn7wnb9t"/><stop offset="1" class="h-9q925vy"/></radialGradient><radialGradient id="i1aPCzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.41816 .95313 -1.00116 -.43923 4.422 7.845)" gradientUnits="userSpaceOnUse"><stop class="k36-60dbo"/><stop offset="1" class="zdrq-zbxw"/></radialGradient><radialGradient id="iSBZSSd" cx="0" cy="0" r="1" gradientTransform="rotate(143.242 1.08 4.532)scale(2.06265 1.48739)" gradientUnits="userSpaceOnUse"><stop offset=".783" class="pg4690b2t"/><stop offset="1" class="v1c4xrvpw"/></radialGradient><radialGradient id="i683Rpb" cx="0" cy="0" r="1" gradientTransform="rotate(107.735 8.445 8.119)scale(2.14797)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="t9tz0ga-k"/><stop offset="1" class="rx67ufbbf"/></radialGradient><radialGradient id="iU52Vpc" cx="0" cy="0" r="1" gradientTransform="rotate(81.335 7.032 12.087)scale(1.15379 1.40042)" gradientUnits="userSpaceOnUse"><stop class="puqvhxbxj"/><stop offset="1" class="wpq9c4ojt"/></radialGradient><radialGradient id="iAhuTAb" cx="0" cy="0" r="1" gradientTransform="rotate(90 8 10.096)scale(2.14844 1.75764)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="wx7ul1f3m"/><stop offset="1" class="wuvwvwb4q"/></radialGradient><radialGradient id="iAvWmBb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.59376 -3.02955 -1.90087 15.281 2.049)" gradientUnits="userSpaceOnUse"><stop class="sl07m5gza"/><stop offset="1" class="v69x5ccnn"/></radialGradient><radialGradient id="itjlTGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3125 -2.78125 3.52699 -1.66441 15.531 7.611)" gradientUnits="userSpaceOnUse"><stop class="cxpqwpbzp"/><stop offset="1" class="dpmmubb4e"/></radialGradient><radialGradient id="iINShPc" cx="0" cy="0" r="1" gradientTransform="rotate(-75.854 8.644 -.193)scale(3.96395 2.63779)" gradientUnits="userSpaceOnUse"><stop class="cxpqwpbzp"/><stop offset="1" class="dpmmubb4e"/></radialGradient><radialGradient id="iE1kt6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.51562 -3.82812 1.03457 -.13935 10.047 7.908)" gradientUnits="userSpaceOnUse"><stop class="cxpqwpbzp"/><stop offset="1" class="dpmmubb4e"/></radialGradient><radialGradient id="iMIIDdB" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -3.76563 .7715 .03521 12.11 8.252)" gradientUnits="userSpaceOnUse"><stop class="cxpqwpbzp"/><stop offset="1" class="dpmmubb4e"/></radialGradient><radialGradient id="iPlLW6w" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 .8906 -2.12309 5.51271 4.734 3.658)" gradientUnits="userSpaceOnUse"><stop class="c3596-jtt"/><stop offset="1" class="j6hxi8u-g"/></radialGradient><radialGradient id="ikeVaZy" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -2.04279 0 11.004 2.681)" gradientUnits="userSpaceOnUse"><stop class="tyd-m2k1p"/><stop offset="1" class="pw0-c8b9g"/></radialGradient><radialGradient id="iTy7y4b" cx="0" cy="0" r="1" gradientTransform="rotate(98.032 -.808 15.573)scale(20.5768 29.4257)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="drbvgx_ol"/><stop offset=".753" class="fvxdhbcqy"/></radialGradient><radialGradient id="iVjyxce" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.1875 -24.3041 0 17.377 14.352)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="y6csecs4r"/><stop offset="1" class="h70c5nb_w"/></radialGradient><radialGradient id="iOdNGvc" cx="0" cy="0" r="1" gradientTransform="rotate(162.597 8.53 9.678)scale(17.5535 25.1022)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="be27xibtd"/><stop offset="1" class="uzfcx4tgg"/></radialGradient><radialGradient id="iR9L3gv" cx="0" cy="0" r="1" gradientTransform="matrix(-16.3437 5.46884 -6.24615 -18.6667 19.563 16.361)" gradientUnits="userSpaceOnUse"><stop offset=".915" class="idy3msb7e"/><stop offset="1" class="h033-lb-j"/></radialGradient><radialGradient id="iqGjD8b" cx="0" cy="0" r="1" gradientTransform="matrix(4.96874 .78128 -.07645 .48622 9.531 29.05)" gradientUnits="userSpaceOnUse"><stop class="ex0wrrppy"/><stop offset="1" class="bowct8qcs"/></radialGradient><radialGradient id="ik6DLMk" cx="0" cy="0" r="1" gradientTransform="rotate(-104.924 13.274 1.106)scale(1.15519 1.25088)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iUKMHUL" cx="0" cy="0" r="1" gradientTransform="matrix(.21094 -.00781 .0668 1.80351 11.016 3.619)" gradientUnits="userSpaceOnUse"><stop class="nlkedu7pf"/><stop offset="1" class="j32_up70w"/></radialGradient><radialGradient id="iaAjT7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78124 4.28126 -7.09019 -2.9499 23.094 24.455)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="i7bqgpb0c"/><stop offset="1" class="fv_y_ib6c"/></radialGradient><linearGradient id="ixAV0eX" x1="5.75" x2="6.844" y1="25.986" y2="27.361" gradientUnits="userSpaceOnUse"><stop class="l2yscmb5i"/><stop offset="1" class="lhgzk8vtq"/></linearGradient><linearGradient id="ia9Jk2c" x1="17.438" x2="22.313" y1="13.049" y2="21.267" gradientUnits="userSpaceOnUse"><stop class="j9hleub8k"/><stop offset="1" class="ejdeakb-m"/></linearGradient><linearGradient id="ik74Fuc" x1="11.004" x2="11.004" y1="2.549" y2="8.674" gradientUnits="userSpaceOnUse"><stop class="h8lqkl8ob"/><stop offset="1" class="sbcl68ibs"/></linearGradient><linearGradient id="iLuCV5c" x1="16.015" x2="15.438" y1="13.939" y2="13.939" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="izWq1Pq" x1="16.171" x2="16.171" y1="14.956" y2="14.017" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ila1MQd" x1="14.438" x2="12.469" y1="3.596" y2="4.036" gradientUnits="userSpaceOnUse"><stop class="klg-94bnl"/><stop offset="1" class="lnxg8ybdu"/></linearGradient><linearGradient id="ixPEqBe" x1="8.051" x2="10.019" y1="3.596" y2="4.036" gradientUnits="userSpaceOnUse"><stop class="klg-94bnl"/><stop offset="1" class="lnxg8ybdu"/></linearGradient><linearGradient id="iErMygc" x1="25.526" x2="28.469" y1="7.054" y2="25.642" gradientUnits="userSpaceOnUse"><stop class="aho0t9bks"/><stop offset="1" class="gw4rabc8u"/></linearGradient><linearGradient id="iOgSKde" x1="26.125" x2="19.188" y1="29.799" y2="21.267" gradientUnits="userSpaceOnUse"><stop class="d0lrq-0hn"/><stop offset="1" class="ic-gp7bjv"/></linearGradient><linearGradient id="iNWhBkc" x1="23.25" x2="22.563" y1="24.299" y2="25.267" gradientUnits="userSpaceOnUse"><stop class="pz1pkfklf"/><stop offset="1" class="e4k05p_iw"/></linearGradient><linearGradient id="i8qRZUd" x1="20.406" x2="20.406" y1="21.83" y2="22.986" gradientUnits="userSpaceOnUse"><stop class="i_c6_qb_r"/><stop offset="1" class="f1_hbs8dd"/></linearGradient><linearGradient id="iHv6JXd" x1="18.891" x2="21.047" y1="7.799" y2="8.892" gradientUnits="userSpaceOnUse"><stop class="lsespyspd"/><stop offset="1" class="g79g43e5m"/></linearGradient><linearGradient id="ib2SPjd" x1="23.948" x2="23.948" y1="2.392" y2="6.142" gradientUnits="userSpaceOnUse"><stop class="dfl2lab_p"/><stop offset="1" class="lgu5i2bpv"/></linearGradient><filter id="iIvnwEb" width="11.629" height="11.843" x="13.996" y="10.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".75"/></filter><filter id="i9uD2Rd" width="1.996" height="2.973" x="14.146" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".25"/></filter><filter id="ib9weze" width="6.875" height="5.182" x="9.859" y="1.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".625"/></filter><filter id="iSkn8Ie" width="6.875" height="5.182" x="5.754" y="1.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".625"/></filter><filter id="ijai4Wb" width="1.634" height="3.759" x="10.503" y="5.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".25"/></filter><filter id="iuydWac" width="6.874" height="17.265" x="22.469" y="6.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".5"/></filter><filter id="iVYorXd" width="11.246" height="7.762" x="17.143" y="21.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".125"/></filter><filter id="iEKMmxc" width="5.656" height="3.704" x="17.25" y="6.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".25"/></filter><filter id="iek6Ykc" width="2.02" height="5" x="22.938" y="1.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5795" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:spouting-whale" /></template>
<style>
.aho0t9bks {
  stop-color: var(--svg-color--6ad3ff, #6AD3FF);
}

.aoi8p1bwy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.875 2.392c.406.636.913 2.275-.312 3.75");
}

.b4lrzy-of {
  stop-color: var(--svg-color--6ccaff, #6CCAFF);
}

.bbubqtb2u {
  stop-color: var(--svg-color--8bc7ea, #8BC7EA);
  stop-opacity: 0;
}

.be27xibtd {
  stop-color: var(--svg-color--84b1ff, #84B1FF);
  stop-opacity: 0;
}

.bo9lsbq4t {
  stop-color: var(--svg-color--4766ff, #4766FF);
  stop-opacity: 0;
}

.bowct8qcs {
  stop-color: var(--svg-color--d3a1ff, #D3A1FF);
  stop-opacity: 0;
}

.c3596-jtt {
  stop-color: var(--svg-color--c7ebf7, #C7EBF7);
}

.c4fnxk4qp {
  d: path("M27.438 27.642s-6.36-4.953-7.594-5.25c-1.235-.296-2.532.36-2.125 2.157c.193.854 1.718 2.625 2.562 3.28c.675.526 1.407.923 2.532 1.126s2.265.11 4.093.11c1.375 0 1.063-.933.532-1.423");
}

.ckk9u0b6o {
  width: 0.996px;
  height: 1.973px;
  x: 14.646px;
  y: 13.217px;
  fill: var(--svg-color--2da6ff, #2DA6FF);
  rx: 0.498px;
}

.cxpqwpbzp {
  stop-color: var(--svg-color--3fbef0, #3FBEF0);
}

.d0lrq-0hn {
  stop-color: var(--svg-color--4884ff, #4884FF);
}

.d488k4bvr {
  stop-color: var(--svg-color--5dbfff, #5DBFFF);
}

.d5ixqnxpw {
  stop-color: var(--svg-color--5dbfff, #5DBFFF);
  stop-opacity: 0;
}

.dfl2lab_p {
  stop-color: var(--svg-color--6ccfff, #6CCFFF);
}

.dpmmubb4e {
  stop-color: var(--svg-color--3fbef0, #3FBEF0);
  stop-opacity: 0;
}

.drbvgx_ol {
  stop-color: var(--svg-color--acdbff, #ACDBFF);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e4k05p_iw {
  stop-color: var(--svg-color--58b4ff, #58B4FF);
  stop-opacity: 0;
}

.ejdeakb-m {
  stop-color: var(--svg-color--68ddff, #68DDFF);
  stop-opacity: 0;
}

.ekfwxce8e {
  d: path("M29 16.518c-.04-4.26-1.716-7.526-4.916-9.876c-.135-.099-.144-.278 0-.445c.908-1.054.846-2.48.354-3.625c-.157-.363-.594-1.05-1.165-.554c-.57.496-1.52 1.7-1.52 1.7c-.503.706-.526 1.237-.362 2.112c0 0 .03.203.086.367c.054.164-.207 0-.555-.094c-.348-.093-1.094-.273-2.125.743c0 0-1.355 1.464-1.469 1.968c-.113.504.358.653.54.696c1.69.398 2.738.238 3.995-1.02c.137-.093.255-.098.38.059c1.843 2.328 2.724 5.645 2.23 8.54c-.446 2.626-3.989 1.632-3.82-.78c0-3.46-2.81-6.27-6.27-6.27H6.782c-2.35 0-4.66 2.24-4.66 4.9c-.215 7.766 5.652 15.775 13.895 15.205C25.353 29.497 29 25.299 29 16.518");
}

.ex0wrrppy {
  stop-color: var(--svg-color--d3a1ff, #D3A1FF);
}

.eyg6k3rpa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M11.484 3.94c.334-.454 1.194-1.106 2.235-.782c1.203.375 1.338 1.422 1.39 1.844");
}

.f0vgg2xqd {
  d: path("M19.938 18.58c-.765-1.166-1.31-3.068-1.524-4.724c-.103-.787-.745-1.432-1.539-1.432s-1.446.647-1.374 1.437c.46 5.045 3.318 7.117 5.124 7.375c1.575.225 3.115-.844 3.5-1.656c-.98.302-3.187.525-4.187-1");
}

.f1_hbs8dd {
  stop-color: var(--svg-color--65c5ff, #65C5FF);
  stop-opacity: 0;
}

.fa8ea7bop {
  stop-color: var(--svg-color--40a9ff, #40A9FF);
  stop-opacity: 0;
}

.fo4vqjbkf {
  stop-color: var(--svg-color--3c95ef, #3C95EF);
  stop-opacity: 0;
}

.fq4l2lbhq {
  stop-color: var(--svg-color--2a95f1, #2A95F1);
}

.ft5dv1b6b {
  fill: none;
}

.fv_y_ib6c {
  stop-color: var(--svg-color--547bff, #547BFF);
}

.fvxdhbcqy {
  stop-color: var(--svg-color--cb98ff, #CB98FF);
}

.g79g43e5m {
  stop-color: var(--svg-color--5bbcff, #5BBCFF);
  stop-opacity: 0;
}

.gw4rabc8u {
  stop-color: var(--svg-color--6ad3ff, #6AD3FF);
  stop-opacity: 0;
}

.h-9q925vy {
  stop-color: var(--svg-color--4e97ff, #4E97FF);
  stop-opacity: 0;
}

.h033-lb-j {
  stop-color: var(--svg-color--b6e3ff, #B6E3FF);
}

.h70c5nb_w {
  stop-color: var(--svg-color--ca99ff, #CA99FF);
}

.h8lqkl8ob {
  stop-color: var(--svg-color--b6e1ed, #B6E1ED);
}

.hc96dbbbl {
  d: path("m21.215 6.67l1.191.488c-1.812 2.734-3.89 2.084-4.655 1.844h-.001L19.183 7.2a1.75 1.75 0 0 1 2.032-.53");
}

.i_c6_qb_r {
  stop-color: var(--svg-color--65c5ff, #65C5FF);
}

.i7bqgpb0c {
  stop-color: var(--svg-color--547bff, #547BFF);
  stop-opacity: 0;
}

.ic-gp7bjv {
  stop-color: var(--svg-color--47a9f3, #47A9F3);
}

.idy3msb7e {
  stop-color: var(--svg-color--b6e3ff, #B6E3FF);
  stop-opacity: 0;
}

.j32_up70w {
  stop-color: var(--svg-color--a1d2f0, #A1D2F0);
  stop-opacity: 0;
}

.j6hxi8u-g {
  stop-color: var(--svg-color--c7ebf7, #C7EBF7);
  stop-opacity: 0;
}

.j9hleub8k {
  stop-color: var(--svg-color--68ddff, #68DDFF);
}

.joxkjnbrh {
  stop-color: var(--svg-color--4cccff, #4CCCFF);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.k36-60dbo {
  stop-color: var(--svg-color--7fdafe, #7FDAFE);
}

.kcptipb5r {
  width: 0.996px;
  height: 1.973px;
  x: 15.019px;
  y: 13.076px;
  rx: 0.498px;
}

.ke9ydz2on {
  d: path("M18.096 4.174a1.217 1.217 0 1 0 0-2.434a1.217 1.217 0 0 0 0 2.434");
}

.klg-94bnl {
  stop-color: var(--svg-color--c8f2ff, #C8F2FF);
}

.l2yscmb5i {
  stop-color: var(--svg-color--7bb2ff, #7BB2FF);
}

.lgu5i2bpv {
  stop-color: var(--svg-color--6ccfff, #6CCFFF);
  stop-opacity: 0;
}

.lhgzk8vtq {
  stop-color: var(--svg-color--7bb2ff, #7BB2FF);
  stop-opacity: 0;
}

.lnxg8ybdu {
  stop-color: var(--svg-color--b7d4ff, #B7D4FF);
}

.lopv8fbmk {
  stop-color: var(--svg-color--489af9, #489AF9);
  stop-opacity: 0;
}

.lsespyspd {
  stop-color: var(--svg-color--5bbcff, #5BBCFF);
}

.moia-pxqs {
  fill-rule: evenodd;
  d: path("M22.398 28.813c-5.539-1.635-5.618-3.053-5.882-7.765l-.016-.28c-.164-2.912-3.766-4.61-5.687-4.72c-1.839-.104-8.138-.008-8.682 0c.339 7.4 6.034 14.64 13.885 14.095c2.533-.175 4.646-.612 6.382-1.33");
}

.n1axymduk {
  stop-color: var(--svg-color--bb9fff, #BB9FFF);
  stop-opacity: 0;
}

.nlkedu7pf {
  stop-color: var(--svg-color--a1d2f0, #A1D2F0);
}

.og--5td9h {
  stop-color: var(--svg-color--bb9fff, #BB9FFF);
}

.ohl1r9i_j {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m27.522 27.55l-.008-.006l-.076.098l.076-.098v-.001l-.004-.003l-.014-.01l-.054-.042a173 173 0 0 0-.942-.724a151 151 0 0 0-2.323-1.736a66 66 0 0 0-2.557-1.794a18 18 0 0 0-1.034-.64c-.292-.164-.54-.282-.713-.323c-.643-.155-1.32-.066-1.786.318c-.474.39-.7 1.056-.49 1.987c.053.234.193.52.379.82c.187.301.425.627.683.946c.514.636 1.113 1.25 1.546 1.587c.688.535 1.438.942 2.585 1.149c.846.153 1.705.14 2.833.123c.392-.006.816-.012 1.283-.012c.355 0 .62-.06.803-.171a.6.6 0 0 0 .302-.47a1 1 0 0 0-.128-.535a1.8 1.8 0 0 0-.36-.463Z");
}

.pg4690b2t {
  stop-color: var(--svg-color--9fe1fe, #9FE1FE);
  stop-opacity: 0;
}

.puqvhxbxj {
  stop-color: var(--svg-color--b2dbff, #B2DBFF);
}

.pw0-c8b9g {
  stop-color: var(--svg-color--b1ddec, #B1DDEC);
  stop-opacity: 0;
}

.pylso49mr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M11.004 3.94c-.334-.454-1.194-1.106-2.235-.782c-1.203.375-1.338 1.422-1.39 1.844");
}

.pz1pkfklf {
  stop-color: var(--svg-color--58b4ff, #58B4FF);
}

.qov12mbvm {
  stroke: var(--svg-color--82d6ff, #82D6FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m11.438 6.002l-.235 2.36");
}

.quaymfbgj {
  d: path("M13.004 2.049c-.77 0-1.47.32-2 .83c-.53-.51-1.23-.83-2-.83c-1.66 0-3 1.34-3 3v.47c0 .84.69 1.55 1.53 1.53c.81-.02 1.47-.68 1.47-1.5c0-.27.23-.5.5-.5c.26 0 .47.19.5.43l.43 3.07c.04.29.28.5.57.5s.53-.21.57-.5l.43-3.07c.03-.24.24-.43.5-.43c.27 0 .5.23.5.5c0 .82.66 1.48 1.47 1.5c.84.02 1.53-.69 1.53-1.53v-.47c0-1.66-1.34-3-3-3");
}

.qzn7wnb9t {
  stop-color: var(--svg-color--4e97ff, #4E97FF);
}

.rfwb5yb1b {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M29 16.518c-.04-4.26-1.716-7.526-4.916-9.876c-.135-.099-.144-.278 0-.445c.908-1.054.846-2.48.354-3.625c-.157-.363-.594-1.05-1.165-.554c-.57.496-1.52 1.7-1.52 1.7c-.503.706-.526 1.237-.362 2.112c0 0 .03.203.086.367c.054.164-.207 0-.555-.094c-.348-.093-1.094-.273-2.125.743c0 0-1.355 1.464-1.469 1.968c-.113.504.358.653.54.696c1.69.398 2.738.238 3.995-1.02c.137-.093.255-.098.38.059c1.843 2.328 2.724 5.645 2.23 8.54c-.446 2.626-3.989 1.632-3.82-.78c0-3.46-2.81-6.27-6.27-6.27H6.782c-2.35 0-4.66 2.24-4.66 4.9c-.215 7.766 5.652 15.775 13.895 15.205C25.353 29.497 29 25.299 29 16.518");
}

.rx67ufbbf {
  stop-color: var(--svg-color--64d1f2, #64D1F2);
}

.rz069gxzj {
  d: path("M4.004 9.049a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.s6314fb-d {
  stop-color: var(--svg-color--3c95ef, #3C95EF);
}

.sbcl68ibs {
  stop-color: var(--svg-color--4ccaee, #4CCAEE);
}

.sdai-tsgn {
  stop-color: var(--svg-color--8bc7ea, #8BC7EA);
}

.sl07m5gza {
  stop-color: var(--svg-color--c1edfd, #C1EDFD);
}

.t9tz0ga-k {
  stop-color: var(--svg-color--caf1ff, #CAF1FF);
}

.tfpnsz75a {
  d: path("M11.016 5.392V2.877l1.39-.5l.735 1.578z");
}

.tiqsh0b-x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M23.844 7.486c2.5 2.094 5.569 6.328 3.372 14.515");
}

.ttes9lb2s {
  fill: var(--svg-color--44c0ff, #44C0FF);
  d: path("M29 16.518c-.04-4.26-1.716-7.526-4.916-9.876c-.135-.099-.144-.278 0-.445c.908-1.054.846-2.48.354-3.625c-.157-.363-.594-1.05-1.165-.554c-.57.496-1.52 1.7-1.52 1.7c-.503.706-.526 1.237-.362 2.112c0 0 .03.203.086.367c.054.164-.207 0-.555-.094c-.348-.093-1.094-.273-2.125.743c0 0-1.355 1.464-1.469 1.968c-.113.504.358.653.54.696c1.69.398 2.738.238 3.995-1.02c.137-.093.255-.098.38.059c1.843 2.328 2.724 5.645 2.23 8.54c-.446 2.626-3.989 1.632-3.82-.78c0-3.46-2.81-6.27-6.27-6.27H6.782c-2.35 0-4.66 2.24-4.66 4.9c-.215 7.766 5.652 15.775 13.895 15.205C25.353 29.497 29 25.299 29 16.518");
}

.tyd-m2k1p {
  stop-color: var(--svg-color--7fcfea, #7FCFEA);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.uad4m6b5q {
  stop-color: var(--svg-color--489af9, #489AF9);
}

.uzfcx4tgg {
  stop-color: var(--svg-color--84b1ff, #84B1FF);
}

.v1c4xrvpw {
  stop-color: var(--svg-color--9fe1fe, #9FE1FE);
}

.v69x5ccnn {
  stop-color: var(--svg-color--c1edfd, #C1EDFD);
  stop-opacity: 0;
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vrdwxussr {
  fill: var(--svg-color--a0a7ff, #A0A7FF);
  d: path("M7.194 25.049h7.02l-3.73 2.84c-.99.75-2.19 1.16-3.43 1.16H3.672c-.51 0-.73-.65-.32-.96z");
}

.w3b25ubed {
  d: path("M7.194 25.049h7.02l-3.73 2.84c-.99.75-2.19 1.16-3.43 1.16H3.672c-.51 0-.73-.65-.32-.96z");
}

.wpq9c4ojt {
  stop-color: var(--svg-color--b2dbff, #B2DBFF);
  stop-opacity: 0;
}

.wuvwvwb4q {
  stop-color: var(--svg-color--9ac5ff, #9AC5FF);
}

.wx7ul1f3m {
  stop-color: var(--svg-color--9ac5ff, #9AC5FF);
  stop-opacity: 0;
}

.x_pv3sf4t {
  stop-color: var(--svg-color--40a9ff, #40A9FF);
}

.xw5qqnbnj {
  stop-color: var(--svg-color--6ccaff, #6CCAFF);
  stop-opacity: 0;
}

.y6csecs4r {
  stop-color: var(--svg-color--ca99ff, #CA99FF);
  stop-opacity: 0;
}

.yjz3xubja {
  stop-color: var(--svg-color--2a95f1, #2A95F1);
  stop-opacity: 0;
}

.zdrq-zbxw {
  stop-color: var(--svg-color--5fc4f4, #5FC4F4);
}

.zhvex1b1e {
  stop-color: var(--svg-color--4cccff, #4CCCFF);
  stop-opacity: 0;
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.zvbcy9_1n {
  stop-color: var(--svg-color--4766ff, #4766FF);
}

</style>
