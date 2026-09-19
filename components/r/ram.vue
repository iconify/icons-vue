<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#itK30Ub)" class="qt9-tkv3s"/><path fill="url(#i7JXvqe)" class="qt9-tkv3s"/><path fill="url(#ifpcMPe)" class="qt9-tkv3s"/><path fill="url(#iUPGupb)" class="ng9iboboh"/><path class="klesbsb_s"/><path fill="url(#ibgbCad)" class="rbwqcwoeo"/><path fill="url(#idRZDfd)" class="rbwqcwoeo"/><path fill="url(#i0BHeoc)" class="rbwqcwoeo"/><path fill="url(#i2X7lve)" class="sxozi3eqk"/><path fill="url(#itU6WVd)" class="sxozi3eqk"/><path fill="url(#iwkItxe)" class="mctqtjbly"/><path fill="url(#i2uNi5c)" class="lpo37bcji"/><path fill="url(#iApAEid)" class="lpo37bcji"/><path fill="url(#iXLuFXO)" class="lpo37bcji"/><path fill="url(#iYFNXte)" class="zrjftsb1r"/><path fill="url(#i7IHfud)" class="zrjftsb1r"/><path fill="url(#iJlwBsc)" class="zrjftsb1r"/><path fill="url(#izCKq5c)" class="zrjftsb1r"/><path fill="url(#iU5KC6c)" class="zrjftsb1r"/><path fill="url(#iCo0TPd)" class="zrjftsb1r"/><path fill="url(#iXr6M0p)" class="zrjftsb1r"/><path fill="url(#iMZe7Rc)" class="qd83mn53m"/><path class="thu42b21s"/><path fill="url(#ipXVOQs)" class="verqr6d9s"/><path fill="url(#ivvLW3d)" class="verqr6d9s"/><path fill="url(#iRdSQGd)" class="verqr6d9s"/><path fill="url(#iPL1C8c)" class="verqr6d9s"/><path fill="url(#i6vaaGb)" class="verqr6d9s"/><path fill="url(#idtMvSb)" class="verqr6d9s"/><path fill="url(#i7Ss2Bc)" class="kkf54hb5u"/><g filter="url(#iHQXPmk)"><path class="ohejymb9g"/></g><path fill="url(#i4LpQzN)" class="p86ioqb6l"/><path fill="url(#i0EMugd)" class="p86ioqb6l"/><path fill="url(#it0a3Jc)" class="p86ioqb6l"/><g filter="url(#is7PSJB)"><path fill="url(#i9OBrqM)" class="lqa2ynbzj"/></g><path class="r2h4ldu6y"/><path fill="url(#ie51Zwb)" class="xgnsnxhzl"/><path fill="url(#iEsBk7b)" class="xgnsnxhzl"/><path fill="url(#iVWDdZc)" class="xgnsnxhzl"/><g filter="url(#iDWo2xd)"><ellipse fill="url(#iEuKi8c)" transform="rotate(-33.22 9.719 3.935)" class="pjsc0zbzt"/></g><path fill="url(#icjECVb)" class="kntlfkv-v"/><path fill="url(#ik5M1hz)" class="kntlfkv-v"/><path fill="url(#icyODPA)" class="kntlfkv-v"/><g filter="url(#iscISvc)"><path stroke="url(#iCIul8d)" class="wowy27lya"/></g><g filter="url(#iqYqxNe)"><ellipse fill="url(#i6B11Nc)" class="m8l6_fabl"/></g><g filter="url(#i5pU0gc)"><path fill="url(#iummQJe)" class="vl1fqcc7d"/></g><g filter="url(#iDsNMnb)"><path class="sdlseac5k"/></g><g filter="url(#inL2eoF)"><path class="j6k7mc-xr"/></g><path fill="url(#ieXA4Ar)" class="ga1wb-mqq"/><g filter="url(#iYEmblb)"><path class="kqwiwabiz"/></g><path fill="url(#itablPd)" class="a_8_hq-po"/><path fill="url(#iQDEIGd)" class="a_8_hq-po"/></g><defs><linearGradient id="itK30Ub" x1="13.891" x2="16.271" y1="30.5" y2="24.213" gradientUnits="userSpaceOnUse"><stop class="buw4dgb_j"/><stop offset="1" class="l7hbqablt"/></linearGradient><linearGradient id="i7JXvqe" x1="13.153" x2="13.153" y1="23.688" y2="26.23" gradientUnits="userSpaceOnUse"><stop class="k8y3kowsr"/><stop offset="1" class="hsskl9bju"/></linearGradient><linearGradient id="ifpcMPe" x1="13.828" x2="13.736" y1="30.313" y2="28.832" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="iUPGupb" x1="13.828" x2="13.14" y1="25.344" y2="23.293" gradientUnits="userSpaceOnUse"><stop class="fmz_f8qqq"/><stop offset="1" class="qlqq2obzs"/></linearGradient><linearGradient id="ibgbCad" x1="12.846" x2="12.846" y1="30.709" y2="28.832" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="idRZDfd" x1="14.797" x2="13.823" y1="24.625" y2="27.25" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset="1" class="a9c-4wbgb"/></linearGradient><linearGradient id="i0BHeoc" x1="10.516" x2="11.391" y1="28.125" y2="28.125" gradientUnits="userSpaceOnUse"><stop class="teo6molgj"/><stop offset="1" class="hgxobmb-y"/></linearGradient><linearGradient id="itU6WVd" x1="21.346" x2="21.346" y1="30.82" y2="28.675" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="i2uNi5c" x1="23.703" x2="28.703" y1="23.313" y2="27.153" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset="1" class="a9u15mwkd"/></linearGradient><linearGradient id="iApAEid" x1="24.234" x2="26.422" y1="25.031" y2="26.344" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset="1" class="a9c-4wbgb"/></linearGradient><linearGradient id="iXLuFXO" x1="27.922" x2="27.922" y1="30.547" y2="29.125" gradientUnits="userSpaceOnUse"><stop class="hkmrfsbjj"/><stop offset=".716" class="a9c-4wbgb"/></linearGradient><linearGradient id="iYFNXte" x1="15.703" x2="15.703" y1="9.813" y2="23.75" gradientUnits="userSpaceOnUse"><stop class="aax035blr"/><stop offset="1" class="dq6us_b-i"/></linearGradient><linearGradient id="i7IHfud" x1="22.703" x2="22.703" y1="8.469" y2="11.719" gradientUnits="userSpaceOnUse"><stop class="yxv_occkk"/><stop offset="1" class="sdcjwitxu"/></linearGradient><linearGradient id="iMZe7Rc" x1="10.521" x2="10.521" y1="7.102" y2="8.594" gradientUnits="userSpaceOnUse"><stop class="jyq5bpp7u"/><stop offset="1" class="mh358hkmc"/></linearGradient><linearGradient id="ipXVOQs" x1="5.473" x2="5.473" y1="12.466" y2="9.84" gradientUnits="userSpaceOnUse"><stop class="yo241sqmu"/><stop offset="1" class="rn62-xjwu"/></linearGradient><linearGradient id="iPL1C8c" x1="7.797" x2="7.797" y1="4.969" y2="6.141" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rmbm6ijew"/><stop offset="1" class="sc_kftb0t"/></linearGradient><linearGradient id="i6vaaGb" x1="3.026" x2="4.077" y1="7.357" y2="8.46" gradientUnits="userSpaceOnUse"><stop class="ivqt5abwx"/><stop offset="1" class="y12gb1bbj"/></linearGradient><linearGradient id="i4LpQzN" x1="6.637" x2="6.018" y1="8.711" y2="8.711" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="i0EMugd" x1="6.958" x2="6.958" y1="9.869" y2="9.183" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="it0a3Jc" x1="5.578" x2="6.034" y1="8.827" y2="8.827" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="ie51Zwb" x1="9.438" x2="9.438" y1="6.297" y2="4.675" gradientUnits="userSpaceOnUse"><stop offset=".117" class="yxv_occkk"/><stop offset="1" class="sdcjwitxu"/></linearGradient><linearGradient id="iEsBk7b" x1="9.438" x2="9.438" y1=".656" y2="2.5" gradientUnits="userSpaceOnUse"><stop offset=".117" class="yxv_occkk"/><stop offset="1" class="sdcjwitxu"/></linearGradient><linearGradient id="icjECVb" x1="11.141" x2="17.766" y1="11.45" y2="6.375" gradientUnits="userSpaceOnUse"><stop class="hr35c4bbp"/><stop offset=".574" class="paqgis_0i"/><stop offset="1" class="yjl2xdbhz"/></linearGradient><linearGradient id="icyODPA" x1="12.341" x2="12.341" y1="11.906" y2="10.531" gradientUnits="userSpaceOnUse"><stop class="ej5f6mb-g"/><stop offset="1" class="s8yb_58_y"/></linearGradient><linearGradient id="iCIul8d" x1="25.828" x2="30.422" y1="11.406" y2="18.781" gradientUnits="userSpaceOnUse"><stop class="mmi_gfead"/><stop offset="1" class="zzpvmbbrw"/></linearGradient><linearGradient id="iummQJe" x1="23.234" x2="29.901" y1="18.188" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="zzpvmbbrw"/><stop offset="1" class="mmi_gfead"/></linearGradient><linearGradient id="itablPd" x1="11.285" x2="11.285" y1="7.859" y2="6.429" gradientUnits="userSpaceOnUse"><stop class="ej5f6mb-g"/><stop offset="1" class="s8yb_58_y"/></linearGradient><radialGradient id="i2X7lve" cx="0" cy="0" r="1" gradientTransform="matrix(4.0825 -4.90624 2.8865 2.40188 18.89 29.124)" gradientUnits="userSpaceOnUse"><stop class="buw4dgb_j"/><stop offset="1" class="l7hbqablt"/></radialGradient><radialGradient id="iwkItxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.09376 -2.4375 3.68374 1.65298 20.172 24.344)" gradientUnits="userSpaceOnUse"><stop class="fmz_f8qqq"/><stop offset="1" class="qlqq2obzs"/></radialGradient><radialGradient id="iJlwBsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8125 -2.6375 2.80602 -1.9283 29.703 17.563)" gradientUnits="userSpaceOnUse"><stop class="yxv_occkk"/><stop offset="1" class="sdcjwitxu"/></radialGradient><radialGradient id="izCKq5c" cx="0" cy="0" r="1" gradientTransform="matrix(4.0625 0 0 8.5 3.578 17.25)" gradientUnits="userSpaceOnUse"><stop class="bsn89kbbo"/><stop offset=".8" class="y73ckd63t"/></radialGradient><radialGradient id="iU5KC6c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.93752 -6.74998 4.28364 -4.40266 20.266 25.438)" gradientUnits="userSpaceOnUse"><stop class="n-j0v00sa"/><stop offset="1" class="tldtf8bjt"/></radialGradient><radialGradient id="iCo0TPd" cx="0" cy="0" r="1" gradientTransform="rotate(-51.34 32.347 8.803)scale(10.8053 6.69183)" gradientUnits="userSpaceOnUse"><stop class="n-j0v00sa"/><stop offset="1" class="tldtf8bjt"/></radialGradient><radialGradient id="iXr6M0p" cx="0" cy="0" r="1" gradientTransform="matrix(7.68747 10.56247 -8.60291 6.26129 .89 1.875)" gradientUnits="userSpaceOnUse"><stop class="n-j0v00sa"/><stop offset="1" class="tldtf8bjt"/></radialGradient><radialGradient id="ivvLW3d" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -2.15625 3.89854 3.22054 3.328 12.781)" gradientUnits="userSpaceOnUse"><stop class="yo241sqmu"/><stop offset="1" class="rn62-xjwu"/></radialGradient><radialGradient id="iRdSQGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5625 1.1875 -1.158 -1.52367 9.14 6.625)" gradientUnits="userSpaceOnUse"><stop class="rmbm6ijew"/><stop offset="1" class="sc_kftb0t"/></radialGradient><radialGradient id="idtMvSb" cx="0" cy="0" r="1" gradientTransform="matrix(2.26826 0 0 2.33989 1.068 9.888)" gradientUnits="userSpaceOnUse"><stop class="ivqt5abwx"/><stop offset="1" class="y12gb1bbj"/></radialGradient><radialGradient id="i7Ss2Bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .53125 -2.33594 0 3.191 9.875)" gradientUnits="userSpaceOnUse"><stop class="mqpbk469p"/><stop offset="1" class="ldgjpwb0m"/></radialGradient><radialGradient id="i9OBrqM" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 1.65624 -3.38922 -1.7266 12.14 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="on-344uno"/><stop offset="1" class="q0d84hbfo"/></radialGradient><radialGradient id="iVWDdZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 0 0 2.52747 3.234 4.531)" gradientUnits="userSpaceOnUse"><stop class="tzvv4qbzz"/><stop offset="1" class="spzlpgbtz"/></radialGradient><radialGradient id="iEuKi8c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.61567 .24398 -.23562 -2.52601 10.881 3.848)" gradientUnits="userSpaceOnUse"><stop class="tzvv4qbzz"/><stop offset="1" class="spzlpgbtz"/></radialGradient><radialGradient id="ik5M1hz" cx="0" cy="0" r="1" gradientTransform="matrix(5.625 0 0 2.55 10.422 8.225)" gradientUnits="userSpaceOnUse"><stop class="hbi65xbgo"/><stop offset="1" class="fqgm7bc4b"/></radialGradient><radialGradient id="i6B11Nc" cx="0" cy="0" r="1" gradientTransform="rotate(134.582 11.852 11.827)scale(6.92606 6.5475)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="mmi_gfead"/><stop offset="1" class="zzpvmbbrw"/></radialGradient><radialGradient id="ieXA4Ar" cx="0" cy="0" r="1" gradientTransform="rotate(-116.946 19.99 .231)scale(4.2067 1.22851)" gradientUnits="userSpaceOnUse"><stop class="rxl0apb0s"/><stop offset="1" class="bf8oenbmn"/></radialGradient><radialGradient id="iQDEIGd" cx="0" cy="0" r="1" gradientTransform="rotate(-164.638 7.793 2.815)scale(1.47456 1.70652)" gradientUnits="userSpaceOnUse"><stop class="pa0ipvkqg"/><stop offset="1" class="tpmmre21e"/></radialGradient><filter id="iHQXPmk" width="2.01" height="2.89" x="5.149" y="7.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".25"/></filter><filter id="is7PSJB" width="6.684" height="3.431" x="9.316" y="9.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".25"/></filter><filter id="iDWo2xd" width="3.898" height="4.051" x="7.77" y="1.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".25"/></filter><filter id="iscISvc" width="5.625" height="7.375" x="24.234" y="9.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".5"/></filter><filter id="iqYqxNe" width="11.079" height="10.562" x="18.516" y="9.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".5"/></filter><filter id="i5pU0gc" width="7.188" height="13.922" x="23.016" y="11.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".5"/></filter><filter id="iDsNMnb" width="1.5" height="5.325" x="28.359" y="24.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".3"/></filter><filter id="inL2eoF" width="1.3" height="3.203" x="12.537" y="26.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".25"/></filter><filter id="iYEmblb" width="3.777" height="4.24" x="13.123" y="4.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3115" stdDeviation=".35"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ram" /></template>
<style>
.a_8_hq-po {
  d: path("M13.423 5c.699 0 1.14.666 1.14 1.364V8.16h-.021a1.093 1.093 0 0 0-1.099-1.009h-4.28c-.59 0-1.06-.47-1.07-1.05c-.02-.61.5-1.1 1.1-1.1z");
}

.a9c-4wbgb {
  stop-color: var(--svg-color--b56551, #B56551);
  stop-opacity: 0;
}

.a9u15mwkd {
  stop-color: var(--svg-color--db8e59, #DB8E59);
}

.aax035blr {
  stop-color: var(--svg-color--d6d1d5, #D6D1D5);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bf8oenbmn {
  stop-color: var(--svg-color--bfb4c9, #BFB4C9);
  stop-opacity: 0;
}

.bsn89kbbo {
  stop-color: var(--svg-color--e7e1ec, #E7E1EC);
}

.buw4dgb_j {
  stop-color: var(--svg-color--b97654, #B97654);
}

.c_lfom8in {
  stop-color: var(--svg-color--574d50, #574D50);
  stop-opacity: 0;
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.dq6us_b-i {
  stop-color: var(--svg-color--cbb9dc, #CBB9DC);
}

.ej5f6mb-g {
  stop-color: var(--svg-color--c07557, #C07557);
}

.fmz_f8qqq {
  stop-color: var(--svg-color--b197c1, #B197C1);
}

.fqgm7bc4b {
  stop-color: var(--svg-color--d88e69, #D88E69);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ga1wb-mqq {
  d: path("m29.703 15.282l-2.422-2.766l-1.875 1.078l2.297 5.89V17.25a.25.25 0 0 1 .25-.25h.832c.476-.008.918-.455.918-1.03z");
}

.hbi65xbgo {
  stop-color: var(--svg-color--d88e69, #D88E69);
}

.hgxobmb-y {
  stop-color: var(--svg-color--eaa566, #EAA566);
  stop-opacity: 0;
}

.hkmrfsbjj {
  stop-color: var(--svg-color--b56551, #B56551);
}

.hr35c4bbp {
  stop-color: var(--svg-color--d49075, #D49075);
}

.hsskl9bju {
  stop-color: var(--svg-color--684234, #684234);
  stop-opacity: 0;
}

.ivqt5abwx {
  stop-color: var(--svg-color--dca980, #DCA980);
}

.j6k7mc-xr {
  stroke: var(--svg-color--b07851, #B07851);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.188 29.453V27.25");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jyq5bpp7u {
  stop-color: var(--svg-color--b09da1, #B09DA1);
}

.k8y3kowsr {
  stop-color: var(--svg-color--684234, #684234);
}

.kfeabacio {
  stop-color: var(--svg-color--574d50, #574D50);
}

.kkf54hb5u {
  d: path("M2.725 10.62h.06c.69-.04.64-1.08-.05-1.08H1.88a.19.19 0 0 0-.18.128a1.2 1.2 0 0 0-.055.342c0 .162.023.324.067.477a.185.185 0 0 0 .182.133z");
}

.klesbsb_s {
  fill: var(--svg-color--db8d58, #DB8D58);
  d: path("M10.703 29.66c0 .19.15.34.34.34h1.36c.19 0 .34-.15.34-.34v-2.61c0-.18.07-.35.2-.48c.56-.56.88-1.33.88-2.12v-1.99h-3.12z");
}

.kntlfkv-v {
  d: path("M13.423 5h-4.23c-.6 0-1.12.49-1.1 1.1c.01.58.48 1.05 1.07 1.05h4.28c.59 0 1.08.46 1.1 1.04c.02.61-.47 1.11-1.08 1.11h-2.63c-.3 0-.49.33-.34.59c.58.94 1.62 1.56 2.8 1.56h.18c1.8 0 3.26-1.48 3.23-3.29c-.03-1.76-1.51-3.16-3.28-3.16");
}

.kqwiwabiz {
  stroke: var(--svg-color--ffe4a3, #FFE4A3);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.844 5.797c.713.073 2.156.54 2.156 2.64");
}

.l7hbqablt {
  stop-color: var(--svg-color--70423a, #70423A);
}

.ldgjpwb0m {
  stop-color: var(--svg-color--3c2b34, #3C2B34);
}

.lpo37bcji {
  d: path("m24.016 24.297l3.377 2.283c.18.13.28.33.28.55v2.54c0 .19.15.34.34.34h1.35c.19 0 .34-.15.34-.34v-4.873a.5.5 0 0 0-.5-.5z");
}

.lqa2ynbzj {
  d: path("M13.568 9.569a1.08 1.08 0 0 1-.73.281h-2.63c-.3 0-.49.33-.34.59c.58.94 1.62 1.56 2.8 1.56h.18c.729 0 1.855-.5 2.652-1.42c-.278-.16-1.224.375-1.387.08q-.008-.021-.02-.04a.2.2 0 0 1-.02-.04z");
}

.m8l6_fabl {
  cx: 24.055px;
  cy: 14.901px;
  rx: 4.539px;
  ry: 4.281px;
}

.mctqtjbly {
  d: path("M23.303 24.62h-3.35c-.56 0-1.02-.46-1.02-1.02v-2.54h5.38v2.54c.01.56-.45 1.02-1.01 1.02");
}

.mh358hkmc {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
  stop-opacity: 0;
}

.mmi_gfead {
  stop-color: var(--svg-color--ede9f0, #EDE9F0);
}

.mqpbk469p {
  stop-color: var(--svg-color--67545f, #67545F);
}

.n-j0v00sa {
  stop-color: var(--svg-color--a381c0, #A381C0);
}

.ng9iboboh {
  d: path("M10.703 23.6c0 .56.46 1.02 1.02 1.02h2.98c.56 0 1.02-.46 1.02-1.02v-1.13h-5.02z");
}

.ohejymb9g {
  fill: var(--svg-color--a55b34, #A55B34);
  d: path("M6.154 9.813c-.28 0-.505-.24-.505-.54v-.81c0-.3.224-.54.505-.54c.28 0 .505.24.505.54v.81c0 .3-.234.54-.505.54");
}

.on-344uno {
  stop-color: var(--svg-color--b5a1b0, #B5A1B0);
}

.p86ioqb6l {
  d: path("M6.295 9.656c-.28 0-.505-.24-.505-.54v-.81c0-.3.224-.54.505-.54c.28 0 .505.24.505.54v.81c0 .3-.234.54-.505.54");
}

.pa0ipvkqg {
  stop-color: var(--svg-color--f5c082, #F5C082);
}

.paqgis_0i {
  stop-color: var(--svg-color--f9c27f, #F9C27F);
}

.pjsc0zbzt {
  cx: 9.719px;
  cy: 3.935px;
  rx: 1.389px;
  ry: 1.58px;
}

.q0d84hbfo {
  stop-color: var(--svg-color--b5a1b1, #B5A1B1);
  stop-opacity: 0;
}

.qd83mn53m {
  d: path("M11.707 6.094H8.203V8.11h4.635l-.695-1.39a2.7 2.7 0 0 0-.436-.626");
}

.qlqq2obzs {
  stop-color: var(--svg-color--857097, #857097);
}

.qt9-tkv3s {
  d: path("M11.593 29.66c0 .19.15.34.34.34h1.36c.19 0 .34-.15.34-.34v-2.61c0-.18.07-.35.2-.48c.56-.56.88-1.33.88-2.12v-1.99h-3.12z");
}

.r2h4ldu6y {
  fill: var(--svg-color--cbc3ce, #CBC3CE);
  d: path("M11.403 5.87V4.105c0-1.225-.94-2.232-2.11-2.253c-.69-.01-1.31.25-1.71.737a.81.81 0 0 1-.64.301h-1.58c-.73 0-1.38.54-1.49 1.298c-.13.903.54 1.682 1.38 1.682z");
}

.rbwqcwoeo {
  d: path("M10.703 29.66c0 .19.15.34.34.34h1.36c.19 0 .34-.15.34-.34v-2.61c0-.18.07-.35.2-.48c.56-.56.88-1.33.88-2.12v-1.99h-3.12z");
}

.rmbm6ijew {
  stop-color: var(--svg-color--8d401e, #8D401E);
}

.rn62-xjwu {
  stop-color: var(--svg-color--b66d52, #B66D52);
  stop-opacity: 0;
}

.rxl0apb0s {
  stop-color: var(--svg-color--bfb4c9, #BFB4C9);
}

.s8yb_58_y {
  stop-color: var(--svg-color--c07557, #C07557);
  stop-opacity: 0;
}

.sc_kftb0t {
  stop-color: var(--svg-color--8d401e, #8D401E);
  stop-opacity: 0;
}

.sdcjwitxu {
  stop-color: var(--svg-color--c2bdbe, #C2BDBE);
  stop-opacity: 0;
}

.sdlseac5k {
  stroke: var(--svg-color--eaa566, #EAA566);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M29.11 25.156v4.125");
}

.spzlpgbtz {
  stop-color: var(--svg-color--ddd9dd, #DDD9DD);
  stop-opacity: 0;
}

.sxozi3eqk {
  d: path("M19.723 21.39v5.15c0 .16-.04.31-.11.45l-1.8 2.53c-.11.22.05.49.3.49h1.12c.32 0 .55-.16.81-.4l2.59-2.37c.29-.25.34-.65.34-1.01v-4.82z");
}

.teo6molgj {
  stop-color: var(--svg-color--eaa566, #EAA566);
}

.thu42b21s {
  fill: var(--svg-color--d38e5d, #D38E5D);
  d: path("M9.243 5.23h-2.26c-.62 0-1.22.25-1.67.69l-3.28 3.29c-.21.21-.33.5-.33.8c0 .93.75 1.68 1.68 1.68h3.5c1.3 0 2.35-1.05 2.35-2.35V5.23z");
}

.tldtf8bjt {
  stop-color: var(--svg-color--ad93c4, #AD93C4);
  stop-opacity: 0;
}

.tpmmre21e {
  stop-color: var(--svg-color--f5c082, #F5C082);
  stop-opacity: 0;
}

.tzvv4qbzz {
  stop-color: var(--svg-color--ddd9dd, #DDD9DD);
}

.verqr6d9s {
  d: path("M9.243 5.23h-2.26c-.62 0-1.22.25-1.67.69l-3.28 3.29c-.21.21-.33.5-.33.8c0 .93.75 1.68 1.68 1.68h3.5c1.3 0 2.35-1.05 2.35-2.35V5.23z");
}

.vl1fqcc7d {
  d: path("M27.203 21.797v-9.61h-3.187v7.804a3 3 0 0 0 1.877 2.782l3.31 1.336z");
}

.wowy27lya {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.484 11c.953.125 3.125 1.35 3.125 4.875");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xgnsnxhzl {
  d: path("M11.403 5.87V4.105c0-1.225-.94-2.232-2.11-2.253c-.69-.01-1.31.25-1.71.737a.81.81 0 0 1-.64.301h-1.58c-.73 0-1.38.54-1.49 1.298c-.13.903.54 1.682 1.38 1.682z");
}

.y12gb1bbj {
  stop-color: var(--svg-color--dca980, #DCA980);
  stop-opacity: 0;
}

.y73ckd63t {
  stop-color: var(--svg-color--e7e1ec, #E7E1EC);
  stop-opacity: 0;
}

.yjl2xdbhz {
  stop-color: var(--svg-color--ffe4a3, #FFE4A3);
}

.yo241sqmu {
  stop-color: var(--svg-color--b66d52, #B66D52);
}

.yxv_occkk {
  stop-color: var(--svg-color--c2bdbe, #C2BDBE);
}

.zrjftsb1r {
  d: path("M24.183 10.07h-8.581c-.84.24-1.069 1.35-1.489.59a.2.2 0 0 0-.02-.04q-.011-.018-.02-.04l-1.93-3.86a2.7 2.7 0 0 0-2.41-1.49h-2.75c-.62 0-1.22.25-1.67.69l-3.28 3.29c-.21.21-.33.5-.33.8c0 .93.75 1.68 1.68 1.68a.32.32 0 0 1 .32.32v1.36c0 .9.36 1.247 1.281 1.63c.36.133.72.375.72.969v3.501c0 1.65 1.34 3 3 3a1 1 0 0 1 1 1v.13c0 .56.46 1.02 1.02 1.02h2.98c.56 0 1.02-.46 1.02-1.02c0-.624.505-1.13 1.13-1.13h5.15c.623 0 1.13.506 1.13 1.13c0 .56.46 1.02 1.02 1.02h6.18a.37.37 0 0 0 .37-.37c0-.45-.18-.87-.49-1.19l-1.21-1.37c-.19-.19-.3-.45-.3-.71v-3.73a.25.25 0 0 1 .25-.25h.831c.476-.008.918-.455.918-1.03v-.91c0-3.05-2.47-4.99-5.52-4.99");
}

.zzpvmbbrw {
  stop-color: var(--svg-color--ede9f0, #EDE9F0);
  stop-opacity: 0;
}

</style>
