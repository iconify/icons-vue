<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYCAy1b)"><circle fill="url(#iXwDdhK)" class="unsysyh-x"/></g><g filter="url(#i3r5BGe)"><circle fill="url(#ivRx42l)" class="dv4i7_lco"/></g><g filter="url(#iC8feip)"><circle fill="url(#i0vSWnd)" class="rfspjwbxe"/><circle fill="url(#iApm66d)" class="rfspjwbxe"/></g><g filter="url(#i5QOf6x)"><circle class="cdbxngt_g"/><circle fill="url(#iQ0sT0c)" class="fsvti5b7i"/><circle fill="url(#ivm85mc)" class="fsvti5b7i"/></g><g filter="url(#iuMFHMP)"><path fill="url(#iNBqQvb)" class="rv5i5x9vr"/><path fill="url(#iPxu7Nb)" class="rv5i5x9vr"/><path fill="url(#i9rKchd)" class="rv5i5x9vr"/><path fill="url(#i9XJemd)" class="rv5i5x9vr"/><path fill="url(#iNXNgNd)" class="rv5i5x9vr"/></g><path fill="url(#iQQHsne)" class="rv5i5x9vr"/><path fill="url(#iBMILme)" class="rv5i5x9vr"/><g filter="url(#ijCAojb)"><path fill="url(#iAVNEXc)" class="rxykf6bsh"/></g><g filter="url(#iotm3hR)"><path class="dalkrn65r"/></g><g filter="url(#ipJRnad)"><path class="hgdwjl92n"/><path fill="url(#ieNfSmc)" class="x17gjmbtf"/><path fill="url(#iw7ZYOb)" class="x17gjmbtf"/><path fill="url(#iGaxOFc)" class="x17gjmbtf"/><path fill="url(#io09pob)" class="x17gjmbtf"/></g><path fill="url(#i6YWzzc)" class="x17gjmbtf"/><path stroke="url(#i9Pqsab)" class="ki7sbpy-d"/><g filter="url(#imTwlRd)"><path class="ck8c5wblo"/><path fill="url(#ixdzqMc)" class="rtbldgbor"/></g><g filter="url(#iETb0Ce)"><path class="i4em6-cuu"/><path fill="url(#ika34id)" class="ei7_0dqxs"/></g><path class="kez4etqvc"/><path fill="url(#iyk4C4d)" class="bz-nmubcj"/><path class="e86iu1bse"/><g filter="url(#iziLHfd)"><path class="xxe2u8bgt"/><path fill="url(#iHEZXHd)" class="potx6jbpr"/></g><g filter="url(#iL9iBkd)"><path fill="url(#iTrvOwb)" class="axwo6-lsa"/></g><path class="jf6p7ucga"/><path fill="url(#ifp8Ued)" class="krjqh8bqz"/><path class="s84lq3bsb"/><g filter="url(#ism2Udd)"><path fill="url(#i61G8Be)" class="ylqsnwb7r"/></g><g filter="url(#iCNVPle)"><ellipse transform="rotate(-27.914 11.367 16.546)" class="ikf8unf1x"/><ellipse fill="url(#i7mdZXc)" transform="rotate(-27.914 11.367 16.546)" class="pombqbc2c"/></g><g filter="url(#ioVV4hR)"><path stroke="url(#iXWdFgc)" class="n2i_v5iqh"/></g><g filter="url(#i5kAMTb)"><path stroke="url(#i15pgHd)" class="ysstz1blv"/></g><defs><radialGradient id="iXwDdhK" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 17.996)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iApm66d" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.526 17.502)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iQ0sT0c" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.528)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ivm85mc" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.464 39.192)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iNBqQvb" cx="0" cy="0" r="1" gradientTransform="rotate(151.408 8.32 10.972)scale(15.8021 24.1166)" gradientUnits="userSpaceOnUse"><stop class="nrl4dtbxe"/><stop offset=".646" class="vaz0packq"/><stop offset=".88" class="svrcrdtnt"/></radialGradient><radialGradient id="iPxu7Nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.39062 2.68091 0 12.031 15.719)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="yk0nzjbvq"/><stop offset="1" class="vkmdw5bme"/></radialGradient><radialGradient id="i9rKchd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78125 3.375 0 20.406 15.594)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="ye4z6-b5j"/><stop offset="1" class="e5bbk1qcb"/></radialGradient><radialGradient id="i9XJemd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.12501 8.87498 -9.7212 -8.89973 24.125 7.5)" gradientUnits="userSpaceOnUse"><stop class="syuavppvq"/><stop offset="1" class="r-h8rsm3t"/></radialGradient><radialGradient id="iNXNgNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.90625 -4.14738 0 17.125 4.156)" gradientUnits="userSpaceOnUse"><stop class="usn4dfbma"/><stop offset="1" class="bvfrupyaf"/></radialGradient><radialGradient id="iQQHsne" cx="0" cy="0" r="1" gradientTransform="rotate(2.78 -608.16 300.86)scale(13.4533 5.34827)" gradientUnits="userSpaceOnUse"><stop class="p644z5b_q"/><stop offset="1" class="fc8p352dj"/></radialGradient><radialGradient id="iBMILme" cx="0" cy="0" r="1" gradientTransform="matrix(4.50363 7.7157 -16.41308 9.58028 8.059 2.721)" gradientUnits="userSpaceOnUse"><stop class="zmwyvccoq"/><stop offset="1" class="ra12oz_kr"/></radialGradient><radialGradient id="io09pob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 20.992)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ixdzqMc" cx="0" cy="0" r="1" gradientTransform="matrix(.1943 -1.125 3.32822 .57484 20.502 14.11)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="ika34id" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.829 .581)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iyk4C4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.01 16.724)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHEZXHd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.926 3.645)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifp8Ued" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.873 16.724)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7mdZXc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.103 2.985)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iYCAy1b" width="6.427" height="6.227" x="3.979" y="14.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19793"/></filter><filter id="i3r5BGe" width="4.711" height="4.711" x="4.737" y="15.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".25"/></filter><filter id="iC8feip" width="6.477" height="6.477" x="21.72" y="14.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19793"/></filter><filter id="i5QOf6x" width="4.711" height="4.711" x="22.478" y="15.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".25"/></filter><filter id="iuMFHMP" width="20.719" height="25.719" x="6.266" y="4.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.372549 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19793"/></filter><filter id="ijCAojb" width="11.918" height="9.719" x="14.252" y="5.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation="1"/></filter><filter id="iotm3hR" width="4.782" height="6.5" x="13.11" y="16.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".375"/></filter><filter id="ipJRnad" width="4" height="5.5" x="13.946" y="16.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".125"/></filter><filter id="imTwlRd" width="5.34" height="3.147" x="18.151" y="11.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19793"/></filter><filter id="iETb0Ce" width="5.341" height="3.147" x="8.551" y="11.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19793"/></filter><filter id="iziLHfd" width="1.294" height="1.125" x="18.727" y="15.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".05"/></filter><filter id="iL9iBkd" width="1.316" height="1.357" x="20.38" y="16.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".1"/></filter><filter id="ism2Udd" width="1.493" height="1.594" x="12.097" y="16.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".1"/></filter><filter id="iCNVPle" width="1.529" height="1.141" x="10.603" y="15.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".05"/></filter><filter id="ioVV4hR" width="4.949" height="2.304" x="18.293" y="11.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".25"/></filter><filter id="i5kAMTb" width="5.094" height="2.41" x="8.56" y="11.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19793" stdDeviation=".25"/></filter><linearGradient id="ivRx42l" x1="7.092" x2="5.898" y1="18.516" y2="18.516" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="i0vSWnd" x1="26.859" x2="25.332" y1="15.96" y2="20.69" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iAVNEXc" x1="14.943" x2="30.131" y1="13.156" y2="7.719" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="ieNfSmc" x1="14.335" x2="16.084" y1="19.952" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iw7ZYOb" x1="17.696" x2="15.784" y1="20.553" y2="20.526" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iGaxOFc" x1="16.309" x2="16.309" y1="21.938" y2="20.869" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="i6YWzzc" x1="16.181" x2="16.181" y1="22.016" y2="21.703" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="i9Pqsab" x1="14.012" x2="14.824" y1="24.949" y2="23.667" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iTrvOwb" x1="21.46" x2="20.875" y1="16.825" y2="17.185" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i61G8Be" x1="13.26" x2="12.675" y1="16.825" y2="17.185" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXWdFgc" x1="21.489" x2="20.706" y1="12.835" y2="11.233" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i15pgHd" x1="11.597" x2="9.379" y1="12.596" y2="11.666" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bald-medium-dark" /></template>
<style>
.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.axwo6-lsa {
  d: path("M21.496 17.28a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.425z");
}

.bvfrupyaf {
  stop-color: var(--svg-color--8e7266, #8E7266);
  stop-opacity: 0;
}

.bz-nmubcj {
  d: path("M20.013 15.835a1.664 1.664 0 0 1 1.604 2.102h-3.215a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.671-1.664");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cdbxngt_g {
  cx: 24.833px;
  cy: 17.996px;
  r: 1.855px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.ck8c5wblo {
  fill: var(--svg-color--352827, #352827);
  d: path("m22.883 12.924l-.002-.002l-.004-.003l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.393a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.536");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dalkrn65r {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.433 17.768l-1.53 3.17c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.702-.527-.702-.736 0");
}

.dv4i7_lco {
  cx: 7.092px;
  cy: 17.996px;
  r: 1.855px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5bbk1qcb {
  stop-color: var(--svg-color--855254, #855254);
  stop-opacity: 0;
}

.e86iu1bse {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.499c0-.53.424-.953.953-.953c.53 0 .953.423.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.44");
}

.ei7_0dqxs {
  d: path("m8.91 12.924l.002-.002l.004-.003l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.116.45-.261.783-.393a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.fc8p352dj {
  stop-color: var(--svg-color--7a406c, #7A406C);
  stop-opacity: 0;
}

.fsvti5b7i {
  cx: 24.833px;
  cy: 17.996px;
  r: 1.855px;
}

.ft5dv1b6b {
  fill: none;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.hgdwjl92n {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.234 17.464l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.303l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.i4em6-cuu {
  fill: var(--svg-color--352827, #352827);
  d: path("m8.91 12.924l.002-.002l.004-.003l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.116.45-.261.783-.393a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.ikf8unf1x {
  cx: 11.367px;
  cy: 16.546px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.jf6p7ucga {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.328c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.636h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.kez4etqvc {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.328c1.217 0 2.245.84 2.525 1.974a.51.51 0 0 1-.499.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.ki7sbpy-d {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.176a.335.335 0 0 0-.4.07a.305.305 0 0 0-.033.392a3.58 3.58 0 0 0 2.993 1.6a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607a5.54 5.54 0 0 1-2.56-.607Z");
}

.krjqh8bqz {
  d: path("M11.87 15.835a1.664 1.664 0 0 0-1.604 2.102h3.214a1.7 1.7 0 0 0 .061-.438a1.675 1.675 0 0 0-1.671-1.664");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.n2i_v5iqh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.654c.802-.14 2.366-.1 3.449.742");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nrl4dtbxe {
  stop-color: var(--svg-color--9b6c5f, #9B6C5F);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p644z5b_q {
  stop-color: var(--svg-color--7a406c, #7A406C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pombqbc2c {
  cx: 11.367px;
  cy: 16.546px;
  rx: 0.726px;
  ry: 0.368px;
}

.potx6jbpr {
  d: path("M19.891 16.187c.119.158-.13.351-.41.562c-.283.21-.492.36-.61.2c-.119-.158.014-.457.295-.668c.282-.21.607-.253.725-.094");
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-h8rsm3t {
  stop-color: var(--svg-color--9c7867, #9C7867);
  stop-opacity: 0;
}

.ra12oz_kr {
  stop-color: var(--svg-color--776058, #776058);
  stop-opacity: 0;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rfspjwbxe {
  cx: 24.833px;
  cy: 17.996px;
  r: 3.113px;
}

.rtbldgbor {
  d: path("m22.883 12.924l-.002-.002l-.004-.003l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.393a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.536");
}

.rv5i5x9vr {
  d: path("m6.344 14.988l.463 9.23a6 6 0 0 0 5.989 5.63h6.408a6 6 0 0 0 5.988-5.63l.464-9.23c.625-6.547-2.515-10.344-8.78-10.61h-1.751c-6.265.266-9.406 4.063-8.781 10.61");
}

.rxykf6bsh {
  d: path("m23.326 7.507l-5.739 1.914a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.s84lq3bsb {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.499a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.037.31.105.439h1.687a.95.95 0 0 0 .114-.44");
}

.svrcrdtnt {
  stop-color: var(--svg-color--704c47, #704C47);
}

.syuavppvq {
  stop-color: var(--svg-color--9c7867, #9C7867);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.unsysyh-x {
  cx: 7.092px;
  cy: 17.996px;
  r: 3.113px;
}

.usn4dfbma {
  stop-color: var(--svg-color--8e7266, #8E7266);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vaz0packq {
  stop-color: var(--svg-color--79524e, #79524E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vkmdw5bme {
  stop-color: var(--svg-color--6f404c, #6F404C);
  stop-opacity: 0;
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.x17gjmbtf {
  d: path("m15.234 17.464l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.303l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xxe2u8bgt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.187c.119.158-.13.351-.41.562c-.283.21-.492.36-.61.2c-.119-.158.014-.457.295-.668c.282-.21.607-.253.725-.094");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.ye4z6-b5j {
  stop-color: var(--svg-color--855254, #855254);
}

.yk0nzjbvq {
  stop-color: var(--svg-color--6f404c, #6F404C);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ylqsnwb7r {
  d: path("M13.39 17.303c0-.537-.438-.896-.556-1.004l-.537.52l.33.673z");
}

.ysstz1blv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.621c.61-.54 1.942-1.107 3.593-.844");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zmwyvccoq {
  stop-color: var(--svg-color--776058, #776058);
}

</style>
