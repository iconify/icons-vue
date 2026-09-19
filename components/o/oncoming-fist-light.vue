<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(70.668 28.188 17.267)" class="iy9cbtobf"/><rect fill="url(#iNVeHPb)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><rect fill="url(#iSgsCqe)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><g filter="url(#iFM67oc)"><path fill="url(#iMCkZld)" class="db14t0bwj"/></g><path fill="url(#iVHGxEc)" class="fb0-_ab0m"/><path fill="url(#id7Ckqe)" class="fb0-_ab0m"/><path fill="url(#iD7YLXb)" class="fb0-_ab0m"/><path fill="url(#iiNHfTc)" class="qf7fwj8si"/><path fill="url(#iEJUieF)" class="qf7fwj8si"/><path fill="url(#iVzKrYa)" class="qf7fwj8si"/><path fill="url(#ikqAppe)" class="qf7fwj8si"/><path fill="url(#iggp8Bd)" class="qf7fwj8si"/><rect fill="url(#i8dGQKe)" class="ow42gabgy"/><rect fill="url(#iCLNUWH)" class="ow42gabgy"/><rect fill="url(#i4LfjqX)" class="ow42gabgy"/><path fill="url(#iXQrxZb)" class="erfqgldfp"/><path fill="url(#iZ7IZec)" class="erfqgldfp"/><path fill="url(#iC7hpVd)" class="db14t0bwj"/><path fill="url(#iARscyd)" class="db14t0bwj"/><path fill="url(#iNNAu9r)" class="db14t0bwj"/><g filter="url(#ihW3vcr)"><path fill="url(#i4Etmyb)" class="ly3dcpmpn"/></g><g filter="url(#ixvACJC)"><path fill="url(#il0L6ed)" class="wmmlx-bzu"/></g><g filter="url(#iZ9Xqge)"><path fill="url(#iBidIob)" class="nv5_uv4vf"/></g><g filter="url(#iB7VXac)"><path fill="url(#iVbGLry)" class="n_jrau6-o"/></g><defs><linearGradient id="iNVeHPb" x1="36.113" x2="34.556" y1="24.75" y2="24.795" gradientUnits="userSpaceOnUse"><stop class="dclw95buf"/><stop offset="1" class="zovn6ubhu"/></linearGradient><linearGradient id="iMCkZld" x1="30.348" x2="7.448" y1="7.864" y2="16.603" gradientUnits="userSpaceOnUse"><stop class="omsrl3lne"/><stop offset="1" class="cgecbbbox"/></linearGradient><linearGradient id="iVHGxEc" x1="10.118" x2="10.118" y1="24.891" y2="16.897" gradientUnits="userSpaceOnUse"><stop class="jjt0yqe3j"/><stop offset="1" class="aj3anlyyj"/></linearGradient><linearGradient id="id7Ckqe" x1="8.964" x2="7.639" y1="17.929" y2="17.929" gradientUnits="userSpaceOnUse"><stop class="to8sjfbpp"/><stop offset="1" class="k6z2i6bfa"/></linearGradient><linearGradient id="iiNHfTc" x1="17.196" x2="17.196" y1="28.172" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="jjfvu29un"/><stop offset="1" class="u_8agtbdg"/></linearGradient><linearGradient id="iEJUieF" x1="16" x2="14.627" y1="17.163" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="p76hbmbng"/><stop offset="1" class="zildo9bce"/></linearGradient><linearGradient id="iVzKrYa" x1="12.959" x2="12.959" y1="8.423" y2="14.491" gradientUnits="userSpaceOnUse"><stop class="m9m08nbqo"/><stop offset="1" class="vpl-z0vcy"/></linearGradient><linearGradient id="ikqAppe" x1="8.188" x2="10.5" y1="21.063" y2="20.938" gradientUnits="userSpaceOnUse"><stop class="gxcmiy8qs"/><stop offset="1" class="r9ok29nmt"/></linearGradient><linearGradient id="i8dGQKe" x1="14.709" x2="19.392" y1="21.163" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="jlcz9zbzy"/><stop offset="1" class="ihuivobat"/></linearGradient><linearGradient id="i4LfjqX" x1="19.392" x2="19.392" y1="7.562" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="my877_zgd"/><stop offset="1" class="b4_cqjb1k"/></linearGradient><linearGradient id="iXQrxZb" x1="22.77" x2="26.863" y1="21.311" y2="20.5" gradientUnits="userSpaceOnUse"><stop class="rmafavb5l"/><stop offset="1" class="hj-qv1bda"/></linearGradient><linearGradient id="iC7hpVd" x1="1.994" x2="4.238" y1="16.017" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="u7vuv-bie"/><stop offset="1" class="hq0fndblf"/></linearGradient><linearGradient id="i4Etmyb" x1="6.448" x2="6.448" y1="10.967" y2="26.049" gradientUnits="userSpaceOnUse"><stop class="ljjudac9l"/><stop offset="1" class="e60w9f6ec"/></linearGradient><linearGradient id="il0L6ed" x1="13.26" x2="13.26" y1="8.766" y2="26.554" gradientUnits="userSpaceOnUse"><stop class="cnnf9s-0l"/><stop offset="1" class="bvpo-tbla"/></linearGradient><linearGradient id="iBidIob" x1="20.914" x2="20.914" y1="5.235" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="wysldqoja"/><stop offset="1" class="h578k2bla"/></linearGradient><linearGradient id="iVbGLry" x1="27.681" x2="27.681" y1="7.266" y2="28.514" gradientUnits="userSpaceOnUse"><stop class="yt0xribym"/><stop offset="1" class="l-gqjgbqw"/></linearGradient><radialGradient id="iSgsCqe" cx="0" cy="0" r="1" gradientTransform="rotate(-65.982 41.658 -7.46)scale(1.80013 4.07406)" gradientUnits="userSpaceOnUse"><stop class="wv55p4b8o"/><stop offset="1" class="bf10s_k8l"/></radialGradient><radialGradient id="iD7YLXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3638 -10.4214 0 5.927 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="yf8w89b_m"/><stop offset="1" class="aoyv5l83x"/></radialGradient><radialGradient id="iggp8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.0323 -10.7984 0 12.854 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="q243-ibuk"/><stop offset="1" class="xhxr-t-5v"/></radialGradient><radialGradient id="iCLNUWH" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.7599 -10.2377 0 19.885 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="ppuz5506w"/><stop offset="1" class="mimhhkbcz"/></radialGradient><radialGradient id="iZ7IZec" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.4405 -10.0039 0 26.838 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".831" class="nqmaiub-f"/><stop offset="1" class="c2m9ygles"/><stop offset="1" class="w281gn8wn"/></radialGradient><radialGradient id="iARscyd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41485 3.40558 -4.95105 -3.51073 29.138 5.984)" gradientUnits="userSpaceOnUse"><stop class="d9jmjybry"/><stop offset="1" class="wseic249b"/></radialGradient><radialGradient id="iNNAu9r" cx="0" cy="0" r="1" gradientTransform="matrix(9.4703 10.37916 -21.20347 19.34678 6.516 5.746)" gradientUnits="userSpaceOnUse"><stop class="ki80q0bga"/><stop offset="1" class="k-p53ip3b"/></radialGradient><filter id="iFM67oc" width="27.985" height="23.056" x="1.994" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.678431 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5753"/></filter><filter id="ihW3vcr" width="6.044" height="15.266" x="3.426" y="9.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5753" stdDeviation=".75"/></filter><filter id="ixvACJC" width="6.044" height="17.467" x="10.238" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5753" stdDeviation=".75"/></filter><filter id="iZ9Xqge" width="6.044" height="22.312" x="17.892" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5753" stdDeviation=".75"/></filter><filter id="iB7VXac" width="5.613" height="20.281" x="24.875" y="5.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5753" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-fist-light" /></template>
<style>
.aj3anlyyj {
  stop-color: var(--svg-color--d7a199, #D7A199);
  stop-opacity: 0;
}

.aoyv5l83x {
  stop-color: var(--svg-color--b97d94, #B97D94);
}

.b4_cqjb1k {
  stop-color: var(--svg-color--f2c7ab, #F2C7AB);
  stop-opacity: 0;
}

.bf10s_k8l {
  stop-color: var(--svg-color--e3a395, #E3A395);
  stop-opacity: 0;
}

.bvpo-tbla {
  stop-color: var(--svg-color--ffd4bd, #FFD4BD);
  stop-opacity: 0;
}

.c2m9ygles {
  stop-color: var(--svg-color--b56e8c, #B56E8C);
}

.cgecbbbox {
  stop-color: var(--svg-color--e2b098, #E2B098);
}

.cnnf9s-0l {
  stop-color: var(--svg-color--ffd4bd, #FFD4BD);
}

.d9jmjybry {
  stop-color: var(--svg-color--bisque, bisque);
}

.db14t0bwj {
  d: path("M1.994 12.711v8.35a3.83 3.83 0 0 0 6.97 2.194a3.831 3.831 0 0 0 6.79 1.003a3.831 3.831 0 0 0 7.267.027a3.83 3.83 0 0 0 6.957-2.21V9.359a4.25 4.25 0 0 0-4.459-4.245l-1.633.08a5.47 5.47 0 0 1-3.089-.776a4.1 4.1 0 0 0-3.883-.186l-1.297.621a6 6 0 0 1-2.59.588h-1.395a4 4 0 0 0-2.42.814L7.563 7.51c-.369.28-.796.566-1.227.734l-1.774.742c-1.703.691-2.568 2.078-2.568 3.726");
}

.dclw95buf {
  stop-color: var(--svg-color--ba8296, #BA8296);
}

.e60w9f6ec {
  stop-color: var(--svg-color--fdcab7, #FDCAB7);
  stop-opacity: 0;
}

.erfqgldfp {
  d: path("M23.021 24.285a3.83 3.83 0 0 0 6.957-2.21v-9.822A3.83 3.83 0 0 0 24.02 9.07c-.975.653-.798 2.01-.798 3.184V23.06c0 .428-.07.84-.2 1.226");
}

.fb0-_ab0m {
  d: path("M8.778 13.08c0-.466-.15-.931-.507-1.229a3.83 3.83 0 0 0-6.277 2.946v6.265a3.83 3.83 0 0 0 6.97 2.193a3.8 3.8 0 0 1-.186-1.181z");
}

.ft5dv1b6b {
  fill: none;
}

.gxcmiy8qs {
  stop-color: var(--svg-color--ca9082, #CA9082);
}

.h578k2bla {
  stop-color: var(--svg-color--ffe7cb, #FFE7CB);
  stop-opacity: 0;
}

.hj-qv1bda {
  stop-color: var(--svg-color--eba38b, #EBA38B);
  stop-opacity: 0;
}

.hq0fndblf {
  stop-color: var(--svg-color--e0a893, #E0A893);
  stop-opacity: 0;
}

.ihuivobat {
  stop-color: var(--svg-color--d69683, #D69683);
  stop-opacity: 0;
}

.is9-ml1ik {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  rx: 3.83px;
}

.iy9cbtobf {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  fill: var(--svg-color--be7e87, #BE7E87);
  rx: 3.83px;
}

.jjfvu29un {
  stop-color: var(--svg-color--d29b99, #D29B99);
}

.jjt0yqe3j {
  stop-color: var(--svg-color--d7a199, #D7A199);
}

.jlcz9zbzy {
  stop-color: var(--svg-color--d69683, #D69683);
}

.k-p53ip3b {
  stop-color: var(--svg-color--deae92, #DEAE92);
  stop-opacity: 0;
}

.k6z2i6bfa {
  stop-color: var(--svg-color--ce886e, #CE886E);
  stop-opacity: 0;
}

.ki80q0bga {
  stop-color: var(--svg-color--deae92, #DEAE92);
}

.l-gqjgbqw {
  stop-color: var(--svg-color--ffe7ca, #FFE7CA);
  stop-opacity: 0;
}

.ljjudac9l {
  stop-color: var(--svg-color--fdcab7, #FDCAB7);
}

.ly3dcpmpn {
  d: path("M4.926 10.968a3.97 3.97 0 0 1 3.044 3.858v6.885a1.522 1.522 0 1 1-3.044 0z");
}

.m9m08nbqo {
  stop-color: var(--svg-color--ebbda3, #EBBDA3);
}

.mimhhkbcz {
  stop-color: var(--svg-color--ba7c94, #BA7C94);
}

.my877_zgd {
  stop-color: var(--svg-color--f2c7ab, #F2C7AB);
}

.n_jrau6-o {
  d: path("m26.375 7.266l.075.03a4 4 0 0 1 2.538 3.723v12.222a1.307 1.307 0 1 1-2.613 0z");
}

.nqmaiub-f {
  stop-color: var(--svg-color--bc7b92, #BC7B92);
  stop-opacity: 0;
}

.nv5_uv4vf {
  d: path("m19.392 5.235l.455.172a4 4 0 0 1 2.59 3.743v13.876a1.522 1.522 0 0 1-3.044 0z");
}

.omsrl3lne {
  stop-color: var(--svg-color--ffd9ba, #FFD9BA);
}

.ow42gabgy {
  width: 7.66px;
  height: 18.465px;
  x: 15.562px;
  y: 8.423px;
  rx: 3.83px;
}

.p76hbmbng {
  stop-color: var(--svg-color--e19c82, #E19C82);
}

.ppuz5506w {
  stop-color: var(--svg-color--ba7c94, #BA7C94);
  stop-opacity: 0;
}

.q243-ibuk {
  stop-color: var(--svg-color--b97d96, #B97D96);
  stop-opacity: 0;
}

.qf7fwj8si {
  d: path("M12.608 8.423a3.83 3.83 0 0 0-3.83 3.83v9.82a3.83 3.83 0 0 0 6.976 2.185a3.8 3.8 0 0 1-.192-1.2V12.254c0-.642.159-1.248.438-1.78a3.83 3.83 0 0 0-3.392-2.05");
}

.r9ok29nmt {
  stop-color: var(--svg-color--ca9082, #CA9082);
  stop-opacity: 0;
}

.rmafavb5l {
  stop-color: var(--svg-color--eba38b, #EBA38B);
}

.to8sjfbpp {
  stop-color: var(--svg-color--ce886e, #CE886E);
}

.u_8agtbdg {
  stop-color: var(--svg-color--d29b99, #D29B99);
  stop-opacity: 0;
}

.u7vuv-bie {
  stop-color: var(--svg-color--e0a893, #E0A893);
}

.vpl-z0vcy {
  stop-color: var(--svg-color--ebbda3, #EBBDA3);
  stop-opacity: 0;
}

.w281gn8wn {
  stop-color: var(--svg-color--bc7b92, #BC7B92);
}

.wmmlx-bzu {
  d: path("m11.738 8.766l.13.037a4 4 0 0 1 2.914 3.85v9.058a1.522 1.522 0 1 1-3.044 0z");
}

.wseic249b {
  stop-color: var(--svg-color--bisque, bisque);
  stop-opacity: 0;
}

.wv55p4b8o {
  stop-color: var(--svg-color--e3a395, #E3A395);
}

.wysldqoja {
  stop-color: var(--svg-color--ffe7cb, #FFE7CB);
}

.xhxr-t-5v {
  stop-color: var(--svg-color--b97d96, #B97D96);
}

.yf8w89b_m {
  stop-color: var(--svg-color--b97d94, #B97D94);
  stop-opacity: 0;
}

.yt0xribym {
  stop-color: var(--svg-color--ffe7ca, #FFE7CA);
}

.zildo9bce {
  stop-color: var(--svg-color--e19c82, #E19C82);
  stop-opacity: 0;
}

.zovn6ubhu {
  stop-color: var(--svg-color--ba8296, #BA8296);
  stop-opacity: 0;
}

</style>
