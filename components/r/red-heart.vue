<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEx5FNb)" class="y3rxnc3lc"/><path fill="url(#iwE8krb)" class="y3rxnc3lc"/><path fill="url(#iwg7QMb)" class="y3rxnc3lc"/><path fill="url(#icgMi7d)" class="y3rxnc3lc"/><path fill="url(#i0J7rue)" class="y3rxnc3lc"/><path fill="url(#inqS43c)" class="y3rxnc3lc"/><path fill="url(#i4Fhese)" class="hfzolqbjp"/><g filter="url(#iXy5vHe)"><path class="eybminb0h"/></g><g filter="url(#iFO6tTS)"><ellipse fill="url(#iVzAqlb)" transform="rotate(-44.19 24.663 11.377)" class="hedrbvmca"/></g><g filter="url(#iD5OjHd)"><ellipse transform="rotate(7.165 23.46 6.067)" class="zt8-exbxc"/></g><g filter="url(#iV5UgQd)"><ellipse transform="rotate(-.697 9.389 6.053)" class="l6k0cpboo"/></g><g filter="url(#ipkacue)"><path fill="url(#iSrIs3d)" class="djjihnv5t"/></g><g filter="url(#ivp7vPb)"><path class="zi533cb8k"/></g><defs><radialGradient id="iEx5FNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 22.9845 -24.4021 0 15.883 5.634)" gradientUnits="userSpaceOnUse"><stop class="bgm48eb1h"/><stop offset=".528" class="xg2pw8btp"/><stop offset="1" class="cebkaqcsn"/></radialGradient><radialGradient id="iwE8krb" cx="0" cy="0" r="1" gradientTransform="matrix(-14.87866 15.19253 -28.45705 -27.86914 23.025 11.363)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="yxe22fjbx"/><stop offset=".908" class="wqy7avhvk"/></radialGradient><radialGradient id="iwg7QMb" cx="0" cy="0" r="1" gradientTransform="matrix(-21.1897 -8.27729 11.70114 -29.9547 19.997 17.789)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="icgMi7d" cx="0" cy="0" r="1" gradientTransform="rotate(90 .872 14.688)scale(19.7992)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="i4Fhese" cx="0" cy="0" r="1" gradientTransform="matrix(-16.59795 4.56623 -4.82236 -17.52896 18.347 12.896)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="qnbh2pn9v"/><stop offset="1" class="pl211ybaw"/></radialGradient><radialGradient id="iVzAqlb" cx="0" cy="0" r="1" gradientTransform="rotate(172.927 14.212 6.526)scale(7.29137 9.69562)" gradientUnits="userSpaceOnUse"><stop class="cxeng1orw"/><stop offset="1" class="w8w692bzr"/></radialGradient><radialGradient id="iSrIs3d" cx="0" cy="0" r="1" gradientTransform="matrix(-9.06248 -8.87742 15.75895 -16.08745 16.345 13.84)" gradientUnits="userSpaceOnUse"><stop class="q33d6wblp"/><stop offset="1" class="zt-mh1x9f"/></radialGradient><filter id="iXy5vHe" width="7.923" height="12.608" x="13.908" y="7.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7305_6094" stdDeviation="1"/></filter><filter id="iFO6tTS" width="11.219" height="11.176" x="19.054" y="5.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7305_6094" stdDeviation=".75"/></filter><filter id="iD5OjHd" width="7.36" height="4.823" x="19.78" y="3.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7305_6094" stdDeviation="1"/></filter><filter id="iV5UgQd" width="6.037" height="3.5" x="6.37" y="4.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7305_6094" stdDeviation=".75"/></filter><filter id="ipkacue" width="12.825" height="18.745" x="5.333" y="4.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7305_6094" stdDeviation="1.5"/></filter><filter id="ivp7vPb" width="3.125" height="3.15" x="12.22" y="7.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7305_6094" stdDeviation=".5"/></filter><linearGradient id="i0J7rue" x1="17.745" x2="25.758" y1="16.133" y2="25.669" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="inqS43c" x1="16.752" x2="7.349" y1="16.53" y2="27.125" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:red-heart" /></template>
<style>
.bgm48eb1h {
  stop-color: var(--svg-color--fc0000, #FC0000);
}

.cebkaqcsn {
  stop-color: var(--svg-color--f724b3, #F724B3);
}

.cxeng1orw {
  stop-color: var(--svg-color--ff7383, #FF7383);
}

.djjihnv5t {
  d: path("m14.845 9.962l.313 10.25C8.283 13.524 6.96 8.828 9.595 7.774c2.5-1 4.5.625 5.25 2.188");
}

.eybminb0h {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M15.908 10.54v6.823c0 .905 1.096 1.334 1.66.627c1.745-2.19 3.153-4.851 1.582-7.025c-.602-.834-1.756-1.368-2.699-1.198c-.352.063-.543.415-.543.774");
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hedrbvmca {
  cx: 24.663px;
  cy: 11.377px;
  rx: 4.462px;
  ry: 3.7px;
}

.hfzolqbjp {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.217 29.202a1.73 1.73 0 0 0 1.71-.023c3.584-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.025-1.897 1.542c-.238.234-.657.258-.904.034c-.69-.63-1.771-1.436-2.465-1.905c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.109 12.476");
}

.l6k0cpboo {
  cx: 9.389px;
  cy: 6.053px;
  fill: var(--svg-color--ff93ba, #FF93BA);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 1.519px;
  ry: 0.249px;
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.q33d6wblp {
  stop-color: var(--svg-color--ff6274, #FF6274);
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.w8w692bzr {
  stop-color: var(--svg-color--ff7383, #FF7383);
  stop-opacity: 0;
}

.wqy7avhvk {
  stop-color: var(--svg-color--c82092, #C82092);
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.y3rxnc3lc {
  d: path("M15.217 29.202a1.73 1.73 0 0 0 1.71-.023c3.584-2.047 9.81-6.761 12.255-12.884c3.59-7.973-4.838-14.337-10.662-9.76c-.608.478-1.372 1.025-1.897 1.542c-.238.234-.657.258-.904.034c-.69-.63-1.771-1.436-2.465-1.905c-4.965-3.36-14 1.069-10.146 10.52c1.412 4.242 8.14 10.26 12.109 12.476");
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.yxe22fjbx {
  stop-color: var(--svg-color--c82092, #C82092);
  stop-opacity: 0;
}

.zi533cb8k {
  fill: var(--svg-color--ff7383, #FF7383);
  d: path("M14.345 9.362c-.84-.12-1.1-.817-1.125-1.15c.48.5.95.542 1.125.5z");
}

.zt-mh1x9f {
  stop-color: var(--svg-color--ff6274, #FF6274);
  stop-opacity: 0;
}

.zt8-exbxc {
  cx: 23.46px;
  cy: 6.067px;
  fill: var(--svg-color--ff7383, #FF7383);
  rx: 1.693px;
  ry: 0.356px;
}

</style>
