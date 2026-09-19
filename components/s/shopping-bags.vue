<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioVyUfb)"><path fill="url(#i4oaeXc)" class="tl943lb2g"/><path fill="url(#i87pqPc)" class="tl943lb2g"/></g><g filter="url(#iQNUMlb)"><path class="a5hfp6blm"/></g><g filter="url(#iWlvoid)"><path class="e6dcqnw5k"/></g><g filter="url(#iQEVP3d)"><path fill="url(#ih5qVJc)" class="z623i4xes"/><path fill="url(#io6f2Xd)" class="z623i4xes"/></g><rect fill="url(#iyRyCqc)" class="j5a5pvo4h"/><rect fill="url(#iKZxx4t)" class="j5a5pvo4h"/><rect fill="url(#iDJ7c6d)" class="j5a5pvo4h"/><rect fill="url(#itSlnLc)" class="j5a5pvo4h"/><g filter="url(#iPtAz8I)"><path stroke="url(#iBJgFWb)" class="bix4b59ep"/></g><path class="olitc_bqg"/><path fill="url(#iQlAkDO)" class="hx5cvtbpl"/><path fill="url(#iTzmTWI)" class="hx5cvtbpl"/><path fill="url(#irOvWPc)" class="hx5cvtbpl"/><path class="o6pd3ebyj"/><path fill="url(#i7yapme)" class="h7nqx8rsn"/><path fill="url(#iHQyrnd)" class="h7nqx8rsn"/><path fill="url(#i9yf0zc)" class="h7nqx8rsn"/><path class="ikv5qbc8z"/><path fill="url(#i4vpLjc)" class="oiv5cdc3u"/><path fill="url(#iIcknFc)" class="oiv5cdc3u"/><path fill="url(#iYfgg3b)" class="oiv5cdc3u"/><g filter="url(#imIwqZb)"><path stroke="url(#iPshgMb)" class="m5fk4bciy"/></g><g filter="url(#iyAEyqt)"><path class="hgwakwbbh"/></g><g filter="url(#i6V4iPd)"><path class="s2m5nbc2b"/></g><g filter="url(#ibOF1Bb)"><path fill="url(#iiW1kwb)" class="hy0iv7tth"/></g><g filter="url(#imaCOXD)"><path fill="url(#i0AMXZb)" class="ujj09ub8r"/><path fill="url(#iGZQklb)" class="ujj09ub8r"/></g><defs><linearGradient id="i4oaeXc" x1="18.547" x2="23.609" y1="17.063" y2="25.813" gradientUnits="userSpaceOnUse"><stop class="jwqh-tbfi"/><stop offset="1" class="cqhoskb0n"/></linearGradient><linearGradient id="ih5qVJc" x1="26.086" x2="26.086" y1="15.781" y2="22.047" gradientUnits="userSpaceOnUse"><stop class="d00hsibjq"/><stop offset="1" class="immhlubge"/></linearGradient><linearGradient id="io6f2Xd" x1="18.891" x2="25.203" y1="22.047" y2="22.047" gradientUnits="userSpaceOnUse"><stop class="d00hsibjq"/><stop offset="1" class="immhlubge"/></linearGradient><linearGradient id="iyRyCqc" x1="10.953" x2="10.953" y1="7.688" y2="27.781" gradientUnits="userSpaceOnUse"><stop class="se9sxzbgl"/><stop offset="1" class="lao90mtbh"/></linearGradient><linearGradient id="iKZxx4t" x1="2.016" x2="3.766" y1="25.469" y2="25.469" gradientUnits="userSpaceOnUse"><stop class="cbj39egmk"/><stop offset="1" class="oauwgw41f"/></linearGradient><linearGradient id="iDJ7c6d" x1="10.609" x2="10.609" y1="28.25" y2="23.875" gradientUnits="userSpaceOnUse"><stop class="zc42hlb7j"/><stop offset="1" class="lwza2_i5q"/></linearGradient><linearGradient id="itSlnLc" x1="10.953" x2="10.953" y1="7.688" y2="9.844" gradientUnits="userSpaceOnUse"><stop offset=".159" class="jlnx-zlxn"/><stop offset="1" class="r-_3tt1tt"/></linearGradient><linearGradient id="iBJgFWb" x1="653657" x2="653657" y1="8.685" y2="25.716" gradientUnits="userSpaceOnUse"><stop class="xsbkopblm"/><stop offset=".739" class="akuxfhbtq"/><stop offset="1" class="fwrrxmb2k"/></linearGradient><linearGradient id="iQlAkDO" x1="2.016" x2="3.859" y1="15.5" y2="15.5" gradientUnits="userSpaceOnUse"><stop offset=".196" class="y6uz7nb_y"/><stop offset="1" class="fh0lszbtd"/></linearGradient><linearGradient id="iTzmTWI" x1="19.891" x2="18.141" y1="15.5" y2="15.5" gradientUnits="userSpaceOnUse"><stop class="un_ui33fu"/><stop offset="1" class="k_nm50b8n"/></linearGradient><linearGradient id="irOvWPc" x1="19.891" x2="19.078" y1="16.188" y2="16.188" gradientUnits="userSpaceOnUse"><stop class="exxs6q5se"/><stop offset="1" class="svolzxpbr"/></linearGradient><linearGradient id="i7yapme" x1="2.016" x2="3.859" y1="20.156" y2="20.156" gradientUnits="userSpaceOnUse"><stop offset=".196" class="y6uz7nb_y"/><stop offset="1" class="fh0lszbtd"/></linearGradient><linearGradient id="iHQyrnd" x1="19.891" x2="18.141" y1="20.156" y2="20.156" gradientUnits="userSpaceOnUse"><stop class="un_ui33fu"/><stop offset="1" class="k_nm50b8n"/></linearGradient><linearGradient id="i9yf0zc" x1="19.891" x2="19.078" y1="20.844" y2="20.844" gradientUnits="userSpaceOnUse"><stop class="exxs6q5se"/><stop offset="1" class="svolzxpbr"/></linearGradient><linearGradient id="i4vpLjc" x1="2.016" x2="3.859" y1="24.813" y2="24.813" gradientUnits="userSpaceOnUse"><stop offset=".196" class="y6uz7nb_y"/><stop offset="1" class="fh0lszbtd"/></linearGradient><linearGradient id="iIcknFc" x1="19.891" x2="18.141" y1="24.813" y2="24.813" gradientUnits="userSpaceOnUse"><stop class="un_ui33fu"/><stop offset="1" class="k_nm50b8n"/></linearGradient><linearGradient id="iYfgg3b" x1="19.891" x2="19.078" y1="25.5" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="exxs6q5se"/><stop offset="1" class="svolzxpbr"/></linearGradient><linearGradient id="iPshgMb" x1="653667" x2="653667" y1="14.423" y2="27.43" gradientUnits="userSpaceOnUse"><stop class="r312gcclj"/><stop offset="1" class="wwxufp7st"/></linearGradient><linearGradient id="i0AMXZb" x1="12.438" x2="12.438" y1="11.344" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="m1pycd5cf"/><stop offset="1" class="kqj7iygrg"/></linearGradient><linearGradient id="iGZQklb" x1="15.797" x2="13.828" y1="4.188" y2="6.563" gradientUnits="userSpaceOnUse"><stop class="jwmgrzbfr"/><stop offset="1" class="am1wvfbuu"/></linearGradient><filter id="ioVyUfb" width="15.531" height="16.625" x="14.766" y="13.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.556863 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17099"/></filter><filter id="iQNUMlb" width="12.344" height="10.844" x="15.484" y="14.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17099" stdDeviation=".5"/></filter><filter id="iWlvoid" width="10.544" height="8.141" x="17.016" y="15.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.321569 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17099"/></filter><filter id="iQEVP3d" width="9.894" height="7.691" x="17.412" y="15.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17099" stdDeviation=".075"/></filter><filter id="iPtAz8I" width="2.25" height="19.75" x="17.797" y="7.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17099" stdDeviation=".375"/></filter><filter id="imIwqZb" width="1.75" height="16.035" x="28.134" y="13.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17099" stdDeviation=".25"/></filter><filter id="iyAEyqt" width="2.75" height="5.875" x="14.109" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17099" stdDeviation=".5"/></filter><filter id="i6V4iPd" width="2.75" height="5.875" x="4.047" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17099" stdDeviation=".5"/></filter><filter id="ibOF1Bb" width="11.094" height="9.662" x="5.406" y="1.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.560784 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17099"/></filter><filter id="imaCOXD" width="11.016" height="9.313" x="5.531" y="1.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17099" stdDeviation=".125"/></filter><radialGradient id="i87pqPc" cx="0" cy="0" r="1" gradientTransform="rotate(52.08 -19.944 29.603)scale(3.50299 4.76486)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="ypw50d7lf"/><stop offset="1" class="ron72-byx"/></radialGradient><radialGradient id="iiW1kwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 8.0625 -9.50433 2.91025 8.484 2.781)" gradientUnits="userSpaceOnUse"><stop class="ef6m0q_mb"/><stop offset="1" class="lttlxrb1r"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shopping-bags" /></template>
<style>
.a5hfp6blm {
  fill: var(--svg-color--f19a39, #F19A39);
  d: path("M17.484 16.766a.5.5 0 1 0-1 0zm9.344-.703a.5.5 0 1 0-1 0zm-.5 2.843h-.5zm-8.844 0v-2.14h-1v2.14zm8.344-2.844v2.844h1v-2.843zm-4.172 7.344c-2.25 0-4.172-1.984-4.172-4.5h-1c0 3.007 2.31 5.5 5.172 5.5zm0 1c2.862 0 5.172-2.493 5.172-5.5h-1c0 2.516-1.922 4.5-4.172 4.5z");
}

.akuxfhbtq {
  stop-color: var(--svg-color--5bb8ff, #5BB8FF);
}

.am1wvfbuu {
  stop-color: var(--svg-color--61b2f2, #61B2F2);
  stop-opacity: 0;
}

.bix4b59ep {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M18.922 8.656v17.5");
}

.cbj39egmk {
  stop-color: var(--svg-color--419ce0, #419CE0);
}

.cqhoskb0n {
  stop-color: var(--svg-color--fdb046, #FDB046);
}

.d00hsibjq {
  stop-color: var(--svg-color--f38362, #F38362);
}

.e6dcqnw5k {
  fill: var(--svg-color--e45a3b, #E45A3B);
  d: path("M18.016 16.14a.5.5 0 1 0-1 0zm9.343 0a.5.5 0 0 0-1 0zm-.5 2.141h-.5zm-8.843 0v-2.14h-1v2.14zm8.343-2.14v2.14h1v-2.14zm-4.172 6.64c-2.25 0-4.171-1.984-4.171-4.5h-1c0 3.007 2.31 5.5 5.172 5.5zm0 1c2.863 0 5.172-2.493 5.172-5.5h-1c0 2.516-1.921 4.5-4.172 4.5z");
}

.ef6m0q_mb {
  stop-color: var(--svg-color--2c94e3, #2C94E3);
}

.exxs6q5se {
  stop-color: var(--svg-color--3c97ee, #3C97EE);
}

.fh0lszbtd {
  stop-color: var(--svg-color--2a81cd, #2A81CD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwrrxmb2k {
  stop-color: var(--svg-color--54afff, #54AFFF);
}

.h7nqx8rsn {
  d: path("M2.016 20.844v-2.219H19.89v2.219z");
}

.hgwakwbbh {
  stroke: var(--svg-color--4eb7f5, #4EB7F5);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M15.484 8.25v3.125");
}

.hx5cvtbpl {
  d: path("M2.016 16.188v-2.22H19.89v2.22z");
}

.hy0iv7tth {
  d: path("M15.5 10.844a.5.5 0 0 0 1 0zm-10.094 0a.5.5 0 0 0 1 0zM15.5 7.28v3.563h1V7.28zm-9.094 3.563V7.28h-1v3.563zm4.547-8.063c2.492 0 4.547 2.021 4.547 4.5h1c0-3.043-2.515-5.5-5.547-5.5zm0-1c-3.031 0-5.547 2.457-5.547 5.5h1c0-2.479 2.056-4.5 4.547-4.5z");
}

.ikv5qbc8z {
  fill: var(--svg-color--3a8ff0, #3A8FF0);
  d: path("M2.016 25.5v-2.219H19.89V25.5z");
}

.immhlubge {
  stop-color: var(--svg-color--f38362, #F38362);
  stop-opacity: 0;
}

.j5a5pvo4h {
  width: 17.875px;
  height: 20.094px;
  x: 2.016px;
  y: 7.688px;
  rx: 1px;
}

.jlnx-zlxn {
  stop-color: var(--svg-color--61c9e8, #61C9E8);
}

.jwmgrzbfr {
  stop-color: var(--svg-color--61b2f2, #61B2F2);
}

.jwqh-tbfi {
  stop-color: var(--svg-color--fec243, #FEC243);
}

.k_nm50b8n {
  stop-color: var(--svg-color--51a9f3, #51A9F3);
  stop-opacity: 0;
}

.kqj7iygrg {
  stop-color: var(--svg-color--53a9f2, #53A9F2);
  stop-opacity: 0;
}

.lao90mtbh {
  stop-color: var(--svg-color--49a8ff, #49A8FF);
}

.lttlxrb1r {
  stop-color: var(--svg-color--2c9ceb, #2C9CEB);
}

.lwza2_i5q {
  stop-color: var(--svg-color--439aff, #439AFF);
  stop-opacity: 0;
}

.m1pycd5cf {
  stop-color: var(--svg-color--53a9f2, #53A9F2);
}

.m5fk4bciy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m29.01 14.697l-.001 14.285");
}

.o6pd3ebyj {
  fill: var(--svg-color--3a91ed, #3A91ED);
  d: path("M2.016 20.844v-2.219H19.89v2.219z");
}

.oauwgw41f {
  stop-color: var(--svg-color--449fee, #449FEE);
  stop-opacity: 0;
}

.oiv5cdc3u {
  d: path("M2.016 25.5v-2.219H19.89V25.5z");
}

.olitc_bqg {
  fill: var(--svg-color--3a92ea, #3A92EA);
  d: path("M2.016 16.188v-2.22H19.89v2.22z");
}

.r-_3tt1tt {
  stop-color: var(--svg-color--61c9e8, #61C9E8);
  stop-opacity: 0;
}

.r312gcclj {
  stop-color: var(--svg-color--ffd262, #FFD262);
}

.ron72-byx {
  stop-color: var(--svg-color--d38d3c, #D38D3C);
  stop-opacity: 0;
}

.s2m5nbc2b {
  stroke: var(--svg-color--4eb7f5, #4EB7F5);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M5.422 8.25v3.125");
}

.se9sxzbgl {
  stop-color: var(--svg-color--59c1fa, #59C1FA);
}

.svolzxpbr {
  stop-color: var(--svg-color--3c97ee, #3C97EE);
  stop-opacity: 0;
}

.tl943lb2g {
  d: path("M14.766 14.781a1 1 0 0 1 1-1h13.03a1 1 0 0 1 1 1v14.125a1 1 0 0 1-1 1h-13.03a1 1 0 0 1-1-1z");
}

.ujj09ub8r {
  d: path("M16.047 10.844a.125.125 0 1 0 .25 0zm-10.266 0a.125.125 0 0 0 .25 0zM16.047 7.28v3.563h.25V7.28zM6.03 10.844V7.28h-.25v3.563zm5.008-8.438c2.743 0 5.008 2.186 5.008 4.875h.25c0-2.834-2.384-5.125-5.258-5.125zm0-.25c-2.874 0-5.258 2.291-5.258 5.125h.25c0-2.689 2.265-4.875 5.008-4.875z");
}

.un_ui33fu {
  stop-color: var(--svg-color--51a9f3, #51A9F3);
}

.wwxufp7st {
  stop-color: var(--svg-color--ffb84a, #FFB84A);
}

.xsbkopblm {
  stop-color: var(--svg-color--80e8ff, #80E8FF);
}

.y6uz7nb_y {
  stop-color: var(--svg-color--2a81cd, #2A81CD);
}

.ypw50d7lf {
  stop-color: var(--svg-color--d38d3c, #D38D3C);
}

.z623i4xes {
  d: path("M17.812 16.14a.125.125 0 0 0-.25 0zm9.344 0a.125.125 0 0 0-.25 0zm-.125 2.141h.125zm-9.219 0v-2.14h-.25v2.14zm9.094-2.14v2.14h.25v-2.14zm-4.547 7.015c-2.48 0-4.547-2.175-4.547-4.875h-.25c0 2.823 2.164 5.125 4.797 5.125zm0 .25c2.633 0 4.797-2.302 4.797-5.125h-.25c0 2.7-2.067 4.875-4.547 4.875z");
}

.zc42hlb7j {
  stop-color: var(--svg-color--4676f8, #4676F8);
}

</style>
