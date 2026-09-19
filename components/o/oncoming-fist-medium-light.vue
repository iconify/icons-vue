<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(70.668 28.188 17.267)" class="pumriabey"/><rect fill="url(#iQ7Yvie)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><rect fill="url(#ibrweme)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><g filter="url(#ikwMPBd)"><path fill="url(#ipI72Sd)" class="db14t0bwj"/></g><path fill="url(#i7Z1OEI)" class="fb0-_ab0m"/><path fill="url(#iifAXJc)" class="fb0-_ab0m"/><path fill="url(#ivJ24vd)" class="fb0-_ab0m"/><path fill="url(#iAmbvlc)" class="qf7fwj8si"/><path fill="url(#ibyxQje)" class="qf7fwj8si"/><path fill="url(#iV3Ymsb)" class="qf7fwj8si"/><path fill="url(#iLIugsd)" class="qf7fwj8si"/><path fill="url(#i5Ju9Wf)" class="qf7fwj8si"/><rect fill="url(#iVX8Vzs)" class="ow42gabgy"/><rect fill="url(#ikamEdL)" class="ow42gabgy"/><rect fill="url(#iCBOcKc)" class="ow42gabgy"/><rect fill="url(#i9nDhve)" class="ow42gabgy"/><path fill="url(#ipveHme)" class="erfqgldfp"/><path fill="url(#iqrzZAd)" class="erfqgldfp"/><path fill="url(#ivv7B6d)" class="db14t0bwj"/><path fill="url(#icakzRc)" class="db14t0bwj"/><path fill="url(#iNWHXzd)" class="db14t0bwj"/><g filter="url(#iNbgbmc)"><path fill="url(#i5d3vcb)" class="ly3dcpmpn"/></g><g filter="url(#isHXHyU)"><path fill="url(#i0UiJ8W)" class="wmmlx-bzu"/></g><g filter="url(#iw7IGid)"><path fill="url(#irFrNFk)" class="nv5_uv4vf"/></g><g filter="url(#iRfx7YR)"><path fill="url(#iEZC6vb)" class="n_jrau6-o"/></g><defs><linearGradient id="iQ7Yvie" x1="36.113" x2="34.556" y1="24.75" y2="24.795" gradientUnits="userSpaceOnUse"><stop class="fhiyzicak"/><stop offset="1" class="xd8u2z5db"/></linearGradient><linearGradient id="ipI72Sd" x1="30.348" x2="13.997" y1="7.864" y2="14.153" gradientUnits="userSpaceOnUse"><stop class="ca-5h5g2e"/><stop offset="1" class="dw94g7b4q"/></linearGradient><linearGradient id="i7Z1OEI" x1="10.118" x2="10.118" y1="24.891" y2="16.897" gradientUnits="userSpaceOnUse"><stop class="v_2eauo3w"/><stop offset="1" class="wdqz5jbgb"/></linearGradient><linearGradient id="iifAXJc" x1="8.964" x2="7.639" y1="17.929" y2="17.929" gradientUnits="userSpaceOnUse"><stop class="fgbihlf6r"/><stop offset="1" class="l7t5ofpkz"/></linearGradient><linearGradient id="iAmbvlc" x1="17.196" x2="17.196" y1="28.172" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="aabloyh0g"/><stop offset="1" class="jxlq-gbhs"/></linearGradient><linearGradient id="ibyxQje" x1="16" x2="14.627" y1="17.163" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="vjaj-xbxu"/><stop offset="1" class="emqr51biv"/></linearGradient><linearGradient id="iV3Ymsb" x1="12.959" x2="12.959" y1="8.423" y2="14.491" gradientUnits="userSpaceOnUse"><stop class="vcf6-19ps"/><stop offset="1" class="r31w2wblq"/></linearGradient><linearGradient id="iLIugsd" x1="8.188" x2="10.5" y1="21.063" y2="20.938" gradientUnits="userSpaceOnUse"><stop class="rzfzw1b1k"/><stop offset="1" class="phknoybop"/></linearGradient><linearGradient id="iVX8Vzs" x1="14.375" x2="19.392" y1="20.829" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="pu002zbiy"/><stop offset="1" class="ia9fnx9lh"/></linearGradient><linearGradient id="iCBOcKc" x1="19.392" x2="19.392" y1="7.562" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="sy_nr3lgi"/><stop offset="1" class="rcqlxebfg"/></linearGradient><linearGradient id="ipveHme" x1="21.863" x2="25.864" y1="21.329" y2="20.772" gradientUnits="userSpaceOnUse"><stop class="a8kt5ludw"/><stop offset="1" class="y1v15tc7b"/></linearGradient><linearGradient id="ivv7B6d" x1="1.994" x2="4.238" y1="16.017" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="lfwwa2bal"/><stop offset="1" class="v-lj4cg5r"/></linearGradient><linearGradient id="i5d3vcb" x1="6.448" x2="6.448" y1="10.967" y2="26.049" gradientUnits="userSpaceOnUse"><stop class="v-q4z23cd"/><stop offset="1" class="f1lfwq92j"/></linearGradient><linearGradient id="i0UiJ8W" x1="13.26" x2="13.26" y1="8.766" y2="26.554" gradientUnits="userSpaceOnUse"><stop class="ufhxz58kv"/><stop offset="1" class="trqfdsb4k"/></linearGradient><linearGradient id="irFrNFk" x1="20.914" x2="20.914" y1="5.235" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="wzfdw2luh"/><stop offset="1" class="xznyxnbwm"/></linearGradient><linearGradient id="iEZC6vb" x1="27.681" x2="27.681" y1="7.266" y2="28.514" gradientUnits="userSpaceOnUse"><stop class="eyqrs1b7e"/><stop offset="1" class="oixbo9bdy"/></linearGradient><radialGradient id="ibrweme" cx="0" cy="0" r="1" gradientTransform="rotate(-65.982 41.658 -7.46)scale(1.80013 4.07406)" gradientUnits="userSpaceOnUse"><stop class="stwh4ck3g"/><stop offset="1" class="xg78e4v4b"/></radialGradient><radialGradient id="ivJ24vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3638 -10.4214 0 5.927 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="bn1oxquic"/><stop offset="1" class="npd09_nrq"/></radialGradient><radialGradient id="i5Ju9Wf" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.0323 -10.7984 0 12.854 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="x7of0bt9w"/><stop offset="1" class="acs4qdakg"/></radialGradient><radialGradient id="ikamEdL" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.7805 -10.7947 0 19.885 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="agm28q3am"/><stop offset="1" class="sniln6l-o"/><stop offset="1" class="a3ake5buj"/></radialGradient><radialGradient id="i9nDhve" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.6391 -8.29832 0 19.392 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".958" class="iya0u8b6f"/><stop offset="1" class="od6o4ibpf"/></radialGradient><radialGradient id="iqrzZAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.4405 -10.0039 0 26.838 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".831" class="ht8qvccov"/><stop offset="1" class="c2m9ygles"/></radialGradient><radialGradient id="icakzRc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41485 3.40558 -4.95105 -3.51073 29.138 5.984)" gradientUnits="userSpaceOnUse"><stop class="kx8y3lbba"/><stop offset="1" class="om06n0lcb"/></radialGradient><radialGradient id="iNWHXzd" cx="0" cy="0" r="1" gradientTransform="matrix(8.73851 9.61435 -19.6411 17.85186 6.516 5.746)" gradientUnits="userSpaceOnUse"><stop class="htc0336yl"/><stop offset="1" class="gdb3dx6qt"/></radialGradient><filter id="ikwMPBd" width="27.985" height="23.056" x="1.994" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.615686 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5741"/></filter><filter id="iNbgbmc" width="6.044" height="15.266" x="3.426" y="9.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5741" stdDeviation=".75"/></filter><filter id="isHXHyU" width="6.044" height="17.467" x="10.238" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5741" stdDeviation=".75"/></filter><filter id="iw7IGid" width="6.044" height="22.312" x="17.892" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5741" stdDeviation=".75"/></filter><filter id="iRfx7YR" width="5.613" height="20.281" x="24.875" y="5.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5741" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-fist-medium-light" /></template>
<style>
.a3ake5buj {
  stop-color: var(--svg-color--b8718a, #B8718A);
}

.a8kt5ludw {
  stop-color: var(--svg-color--d28b6b, #D28B6B);
}

.aabloyh0g {
  stop-color: var(--svg-color--c38881, #C38881);
}

.acs4qdakg {
  stop-color: var(--svg-color--b6708b, #B6708B);
}

.agm28q3am {
  stop-color: var(--svg-color--b8718a, #B8718A);
  stop-opacity: 0;
}

.bn1oxquic {
  stop-color: var(--svg-color--b87387, #B87387);
  stop-opacity: 0;
}

.c2m9ygles {
  stop-color: var(--svg-color--b56e8c, #B56E8C);
}

.ca-5h5g2e {
  stop-color: var(--svg-color--f7c49a, #F7C49A);
}

.db14t0bwj {
  d: path("M1.994 12.711v8.35a3.83 3.83 0 0 0 6.97 2.194a3.831 3.831 0 0 0 6.79 1.003a3.831 3.831 0 0 0 7.267.027a3.83 3.83 0 0 0 6.957-2.21V9.359a4.25 4.25 0 0 0-4.459-4.245l-1.633.08a5.47 5.47 0 0 1-3.089-.776a4.1 4.1 0 0 0-3.883-.186l-1.297.621a6 6 0 0 1-2.59.588h-1.395a4 4 0 0 0-2.42.814L7.563 7.51c-.369.28-.796.566-1.227.734l-1.774.742c-1.703.691-2.568 2.078-2.568 3.726");
}

.dw94g7b4q {
  stop-color: var(--svg-color--e3ae90, #E3AE90);
}

.emqr51biv {
  stop-color: var(--svg-color--c8886c, #C8886C);
  stop-opacity: 0;
}

.erfqgldfp {
  d: path("M23.021 24.285a3.83 3.83 0 0 0 6.957-2.21v-9.822A3.83 3.83 0 0 0 24.02 9.07c-.975.653-.798 2.01-.798 3.184V23.06c0 .428-.07.84-.2 1.226");
}

.eyqrs1b7e {
  stop-color: var(--svg-color--ffd1ab, #FFD1AB);
}

.f1lfwq92j {
  stop-color: var(--svg-color--ebb89d, #EBB89D);
  stop-opacity: 0;
}

.fb0-_ab0m {
  d: path("M8.778 13.08c0-.466-.15-.931-.507-1.229a3.83 3.83 0 0 0-6.277 2.946v6.265a3.83 3.83 0 0 0 6.97 2.193a3.8 3.8 0 0 1-.186-1.181z");
}

.fgbihlf6r {
  stop-color: var(--svg-color--b37054, #B37054);
}

.fhiyzicak {
  stop-color: var(--svg-color--b6768d, #B6768D);
}

.ft5dv1b6b {
  fill: none;
}

.gdb3dx6qt {
  stop-color: var(--svg-color--cc9b78, #CC9B78);
  stop-opacity: 0;
}

.ht8qvccov {
  stop-color: var(--svg-color--b56e8c, #B56E8C);
  stop-opacity: 0;
}

.htc0336yl {
  stop-color: var(--svg-color--cc9b78, #CC9B78);
}

.ia9fnx9lh {
  stop-color: var(--svg-color--c07f69, #C07F69);
  stop-opacity: 0;
}

.is9-ml1ik {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  rx: 3.83px;
}

.iya0u8b6f {
  stop-color: var(--svg-color--ba7897, #BA7897);
  stop-opacity: 0;
}

.jxlq-gbhs {
  stop-color: var(--svg-color--c38881, #C38881);
  stop-opacity: 0;
}

.kx8y3lbba {
  stop-color: var(--svg-color--ffcea4, #FFCEA4);
}

.l7t5ofpkz {
  stop-color: var(--svg-color--b37054, #B37054);
  stop-opacity: 0;
}

.lfwwa2bal {
  stop-color: var(--svg-color--c8917b, #C8917B);
}

.ly3dcpmpn {
  d: path("M4.926 10.968a3.97 3.97 0 0 1 3.044 3.858v6.885a1.522 1.522 0 1 1-3.044 0z");
}

.n_jrau6-o {
  d: path("m26.375 7.266l.075.03a4 4 0 0 1 2.538 3.723v12.222a1.307 1.307 0 1 1-2.613 0z");
}

.npd09_nrq {
  stop-color: var(--svg-color--b87387, #B87387);
}

.nv5_uv4vf {
  d: path("m19.392 5.235l.455.172a4 4 0 0 1 2.59 3.743v13.876a1.522 1.522 0 0 1-3.044 0z");
}

.od6o4ibpf {
  stop-color: var(--svg-color--ba7897, #BA7897);
}

.oixbo9bdy {
  stop-color: var(--svg-color--ffd1ab, #FFD1AB);
  stop-opacity: 0;
}

.om06n0lcb {
  stop-color: var(--svg-color--ffcea4, #FFCEA4);
  stop-opacity: 0;
}

.ow42gabgy {
  width: 7.66px;
  height: 18.465px;
  x: 15.562px;
  y: 8.423px;
  rx: 3.83px;
}

.phknoybop {
  stop-color: var(--svg-color--b67965, #B67965);
  stop-opacity: 0;
}

.pu002zbiy {
  stop-color: var(--svg-color--c07f69, #C07F69);
}

.pumriabey {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  fill: var(--svg-color--b36f77, #B36F77);
  rx: 3.83px;
}

.qf7fwj8si {
  d: path("M12.608 8.423a3.83 3.83 0 0 0-3.83 3.83v9.82a3.83 3.83 0 0 0 6.976 2.185a3.8 3.8 0 0 1-.192-1.2V12.254c0-.642.159-1.248.438-1.78a3.83 3.83 0 0 0-3.392-2.05");
}

.r31w2wblq {
  stop-color: var(--svg-color--e5b192, #E5B192);
  stop-opacity: 0;
}

.rcqlxebfg {
  stop-color: var(--svg-color--ecb895, #ECB895);
  stop-opacity: 0;
}

.rzfzw1b1k {
  stop-color: var(--svg-color--b67965, #B67965);
}

.sniln6l-o {
  stop-color: var(--svg-color--783d64, #783D64);
}

.stwh4ck3g {
  stop-color: var(--svg-color--d49383, #D49383);
}

.sy_nr3lgi {
  stop-color: var(--svg-color--ecb895, #ECB895);
}

.trqfdsb4k {
  stop-color: var(--svg-color--f4c0a2, #F4C0A2);
  stop-opacity: 0;
}

.ufhxz58kv {
  stop-color: var(--svg-color--f4c0a2, #F4C0A2);
}

.v_2eauo3w {
  stop-color: var(--svg-color--c3897e, #C3897E);
}

.v-lj4cg5r {
  stop-color: var(--svg-color--c8917b, #C8917B);
  stop-opacity: 0;
}

.v-q4z23cd {
  stop-color: var(--svg-color--ebb89d, #EBB89D);
}

.vcf6-19ps {
  stop-color: var(--svg-color--e5b192, #E5B192);
}

.vjaj-xbxu {
  stop-color: var(--svg-color--c8886c, #C8886C);
}

.wdqz5jbgb {
  stop-color: var(--svg-color--c3897e, #C3897E);
  stop-opacity: 0;
}

.wmmlx-bzu {
  d: path("m11.738 8.766l.13.037a4 4 0 0 1 2.914 3.85v9.058a1.522 1.522 0 1 1-3.044 0z");
}

.wzfdw2luh {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
}

.x7of0bt9w {
  stop-color: var(--svg-color--b6708b, #B6708B);
  stop-opacity: 0;
}

.xd8u2z5db {
  stop-color: var(--svg-color--b6768d, #B6768D);
  stop-opacity: 0;
}

.xg78e4v4b {
  stop-color: var(--svg-color--d49383, #D49383);
  stop-opacity: 0;
}

.xznyxnbwm {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
  stop-opacity: 0;
}

.y1v15tc7b {
  stop-color: var(--svg-color--d28b6b, #D28B6B);
  stop-opacity: 0;
}

</style>
