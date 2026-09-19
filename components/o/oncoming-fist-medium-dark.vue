<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(70.668 28.188 17.267)" class="v-999jmkf"/><rect fill="url(#ipIryXb)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><rect fill="url(#i7mqx4d)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><g filter="url(#iRXefdc)"><path fill="url(#icFfmNF)" class="db14t0bwj"/></g><path fill="url(#itebYCb)" class="db14t0bwj"/><path fill="url(#iTNZXne)" class="db14t0bwj"/><path fill="url(#iaEhdhd)" class="fb0-_ab0m"/><path fill="url(#iGNJM9b)" class="fb0-_ab0m"/><path fill="url(#i6WXnnS)" class="fb0-_ab0m"/><path fill="url(#iNjdpDc)" class="qf7fwj8si"/><path fill="url(#i2aAf5O)" class="qf7fwj8si"/><path fill="url(#iXZvBce)" class="qf7fwj8si"/><path fill="url(#iihI5cc)" class="qf7fwj8si"/><path fill="url(#i7YtLLb)" class="qf7fwj8si"/><rect fill="url(#ivgfsfs)" class="ow42gabgy"/><rect fill="url(#iHhBLZb)" class="ow42gabgy"/><rect fill="url(#i2hP6Fd)" class="ow42gabgy"/><rect fill="url(#i63aZtd)" class="ow42gabgy"/><path fill="url(#ix5rlrb)" class="erfqgldfp"/><path fill="url(#iVh88rc)" class="erfqgldfp"/><path fill="url(#iVdlRUb)" class="erfqgldfp"/><g filter="url(#iEQBSrc)"><path fill="url(#iE3Ifkz)" class="ly3dcpmpn"/></g><g filter="url(#iFqnCcc)"><path fill="url(#i16Y3Pe)" class="wmmlx-bzu"/></g><g filter="url(#ispMrBc)"><path fill="url(#iJyAqqV)" class="nv5_uv4vf"/></g><g filter="url(#iHeMwDc)"><path fill="url(#iiOIate)" class="n_jrau6-o"/></g><defs><linearGradient id="ipIryXb" x1="36.113" x2="34.556" y1="24.75" y2="24.795" gradientUnits="userSpaceOnUse"><stop class="n3j2o9bka"/><stop offset="1" class="q06hynbqf"/></linearGradient><linearGradient id="icFfmNF" x1="32.977" x2="17.783" y1="7.313" y2="19.415" gradientUnits="userSpaceOnUse"><stop class="r0q1ucbcl"/><stop offset="1" class="tg8dncaxu"/></linearGradient><linearGradient id="itebYCb" x1="1.994" x2="4.238" y1="16.017" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="m1k3k0bqs"/><stop offset="1" class="ksru84u1i"/></linearGradient><linearGradient id="iaEhdhd" x1="10.118" x2="10.118" y1="24.891" y2="16.897" gradientUnits="userSpaceOnUse"><stop class="bbgdpmb4d"/><stop offset="1" class="tnclz_bha"/></linearGradient><linearGradient id="iGNJM9b" x1="8.964" x2="7.639" y1="17.929" y2="17.929" gradientUnits="userSpaceOnUse"><stop class="aa4-qmblq"/><stop offset="1" class="fu44scc_w"/></linearGradient><linearGradient id="iNjdpDc" x1="17.196" x2="17.196" y1="28.172" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="aw8qrjbpp"/><stop offset="1" class="c3lo31rgp"/></linearGradient><linearGradient id="iXZvBce" x1="16" x2="14.627" y1="17.163" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="cqglgbu3a"/><stop offset="1" class="pwi46db6j"/></linearGradient><linearGradient id="i7YtLLb" x1="13.975" x2="13.975" y1="10.89" y2="16.528" gradientUnits="userSpaceOnUse"><stop class="vhei7_ecu"/><stop offset="1" class="wx_1lpbxx"/></linearGradient><linearGradient id="ivgfsfs" x1="14.375" x2="19.392" y1="20.829" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="ph7p82b_t"/><stop offset="1" class="xz_i-xa1b"/></linearGradient><linearGradient id="i2hP6Fd" x1="19.392" x2="19.392" y1="7.563" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="s28fv4bdt"/><stop offset="1" class="cpznn9bja"/></linearGradient><linearGradient id="ix5rlrb" x1="21.863" x2="25.864" y1="21.329" y2="20.772" gradientUnits="userSpaceOnUse"><stop class="b49y7dr4w"/><stop offset="1" class="os8zuf0sl"/></linearGradient><linearGradient id="iE3Ifkz" x1="6.448" x2="6.448" y1="10.967" y2="26.049" gradientUnits="userSpaceOnUse"><stop class="ef9rs0bph"/><stop offset="1" class="c-by0kbgf"/></linearGradient><linearGradient id="i16Y3Pe" x1="13.26" x2="13.26" y1="8.766" y2="26.554" gradientUnits="userSpaceOnUse"><stop class="bue1pzc7i"/><stop offset="1" class="vhdi0jbww"/></linearGradient><linearGradient id="iJyAqqV" x1="20.914" x2="20.914" y1="5.235" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="d_syq5qya"/><stop offset="1" class="no4na2b-l"/></linearGradient><linearGradient id="iiOIate" x1="27.681" x2="27.681" y1="7.266" y2="28.514" gradientUnits="userSpaceOnUse"><stop class="pgj76mb-f"/><stop offset="1" class="oaopunb0a"/></linearGradient><radialGradient id="i7mqx4d" cx="0" cy="0" r="1" gradientTransform="rotate(-65.982 41.658 -7.46)scale(1.80013 4.07406)" gradientUnits="userSpaceOnUse"><stop class="fxa0vko6x"/><stop offset="1" class="vobj_cc7n"/></radialGradient><radialGradient id="iTNZXne" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41485 3.40558 -4.95105 -3.51073 29.138 5.984)" gradientUnits="userSpaceOnUse"><stop class="ci-glpb1o"/><stop offset="1" class="p57s7tbpu"/></radialGradient><radialGradient id="i6WXnnS" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3638 -10.4214 0 5.927 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="jje64mbwo"/><stop offset="1" class="bbrrdbcqc"/></radialGradient><radialGradient id="i2aAf5O" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.0323 -10.7984 0 12.854 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="dgu4inb6o"/><stop offset="1" class="ema28n1ks"/></radialGradient><radialGradient id="iihI5cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.48591 17.47465 -7.74862 -.21546 12.875 8.594)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="cqt-zpbtw"/><stop offset="1" class="j74txzb9n"/></radialGradient><radialGradient id="iHhBLZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.7805 -10.7947 0 19.885 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="ai-ceff_y"/><stop offset="1" class="sniln6l-o"/></radialGradient><radialGradient id="i63aZtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.6391 -8.29832 0 19.392 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".958" class="j4n5nmk7v"/><stop offset="1" class="ppy0krbzi"/></radialGradient><radialGradient id="iVh88rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.7256 -10.1586 0 26.838 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="gg84eqfdg"/><stop offset="1" class="hawph0g-w"/></radialGradient><radialGradient id="iVdlRUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.645 -7.80931 0 26.375 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="i9xybo0rq"/><stop offset="1" class="ktl5mwith"/></radialGradient><filter id="iRXefdc" width="27.985" height="23.056" x="1.994" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.376471 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5717"/></filter><filter id="iEQBSrc" width="6.044" height="15.266" x="3.426" y="9.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5717" stdDeviation=".75"/></filter><filter id="iFqnCcc" width="6.044" height="17.467" x="10.238" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5717" stdDeviation=".75"/></filter><filter id="ispMrBc" width="6.044" height="22.312" x="17.892" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5717" stdDeviation=".75"/></filter><filter id="iHeMwDc" width="5.613" height="20.281" x="24.875" y="5.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5717" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-fist-medium-dark" /></template>
<style>
.aa4-qmblq {
  stop-color: var(--svg-color--532a26, #532A26);
}

.ai-ceff_y {
  stop-color: var(--svg-color--783d64, #783D64);
  stop-opacity: 0;
}

.aw8qrjbpp {
  stop-color: var(--svg-color--804d5f, #804D5F);
}

.b49y7dr4w {
  stop-color: var(--svg-color--6b3a3a, #6B3A3A);
}

.bbgdpmb4d {
  stop-color: var(--svg-color--835260, #835260);
}

.bbrrdbcqc {
  stop-color: var(--svg-color--7c4671, #7C4671);
}

.bue1pzc7i {
  stop-color: var(--svg-color--98756e, #98756E);
}

.c-by0kbgf {
  stop-color: var(--svg-color--8d6c66, #8D6C66);
  stop-opacity: 0;
}

.c3lo31rgp {
  stop-color: var(--svg-color--804d5f, #804D5F);
  stop-opacity: 0;
}

.ci-glpb1o {
  stop-color: var(--svg-color--9e7866, #9E7866);
}

.cpznn9bja {
  stop-color: var(--svg-color--865f54, #865F54);
  stop-opacity: 0;
}

.cqglgbu3a {
  stop-color: var(--svg-color--643a37, #643A37);
}

.cqt-zpbtw {
  stop-color: var(--svg-color--764a6c, #764A6C);
  stop-opacity: 0;
}

.d_syq5qya {
  stop-color: var(--svg-color--a78075, #A78075);
}

.db14t0bwj {
  d: path("M1.994 12.711v8.35a3.83 3.83 0 0 0 6.97 2.194a3.831 3.831 0 0 0 6.79 1.003a3.831 3.831 0 0 0 7.267.027a3.83 3.83 0 0 0 6.957-2.21V9.359a4.25 4.25 0 0 0-4.459-4.245l-1.633.08a5.47 5.47 0 0 1-3.089-.776a4.1 4.1 0 0 0-3.883-.186l-1.297.621a6 6 0 0 1-2.59.588h-1.395a4 4 0 0 0-2.42.814L7.563 7.51c-.369.28-.796.566-1.227.734l-1.774.742c-1.703.691-2.568 2.078-2.568 3.726");
}

.dgu4inb6o {
  stop-color: var(--svg-color--7c426f, #7C426F);
  stop-opacity: 0;
}

.ef9rs0bph {
  stop-color: var(--svg-color--8d6c66, #8D6C66);
}

.ema28n1ks {
  stop-color: var(--svg-color--7c426f, #7C426F);
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

.fu44scc_w {
  stop-color: var(--svg-color--532a26, #532A26);
  stop-opacity: 0;
}

.fxa0vko6x {
  stop-color: var(--svg-color--7e5556, #7E5556);
}

.gg84eqfdg {
  stop-color: var(--svg-color--773d65, #773D65);
  stop-opacity: 0;
}

.hawph0g-w {
  stop-color: var(--svg-color--773d65, #773D65);
}

.i9xybo0rq {
  stop-color: var(--svg-color--875580, #875580);
  stop-opacity: 0;
}

.is9-ml1ik {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  rx: 3.83px;
}

.j4n5nmk7v {
  stop-color: var(--svg-color--8e6186, #8E6186);
  stop-opacity: 0;
}

.j74txzb9n {
  stop-color: var(--svg-color--764a6c, #764A6C);
}

.jje64mbwo {
  stop-color: var(--svg-color--7c4671, #7C4671);
  stop-opacity: 0;
}

.ksru84u1i {
  stop-color: var(--svg-color--714d47, #714D47);
  stop-opacity: 0;
}

.ktl5mwith {
  stop-color: var(--svg-color--875580, #875580);
}

.ly3dcpmpn {
  d: path("M4.926 10.968a3.97 3.97 0 0 1 3.044 3.858v6.885a1.522 1.522 0 1 1-3.044 0z");
}

.m1k3k0bqs {
  stop-color: var(--svg-color--714d47, #714D47);
}

.n_jrau6-o {
  d: path("m26.375 7.266l.075.03a4 4 0 0 1 2.538 3.723v12.222a1.307 1.307 0 1 1-2.613 0z");
}

.n3j2o9bka {
  stop-color: var(--svg-color--7d436f, #7D436F);
}

.no4na2b-l {
  stop-color: var(--svg-color--a78075, #A78075);
  stop-opacity: 0;
}

.nv5_uv4vf {
  d: path("m19.392 5.235l.455.172a4 4 0 0 1 2.59 3.743v13.876a1.522 1.522 0 0 1-3.044 0z");
}

.oaopunb0a {
  stop-color: var(--svg-color--a57f74, #A57F74);
  stop-opacity: 0;
}

.os8zuf0sl {
  stop-color: var(--svg-color--6b3a3a, #6B3A3A);
  stop-opacity: 0;
}

.ow42gabgy {
  width: 7.66px;
  height: 18.465px;
  x: 15.562px;
  y: 8.423px;
  rx: 3.83px;
}

.p57s7tbpu {
  stop-color: var(--svg-color--9e7866, #9E7866);
  stop-opacity: 0;
}

.pgj76mb-f {
  stop-color: var(--svg-color--a57f74, #A57F74);
}

.ph7p82b_t {
  stop-color: var(--svg-color--613636, #613636);
}

.ppy0krbzi {
  stop-color: var(--svg-color--8e6186, #8E6186);
}

.pwi46db6j {
  stop-color: var(--svg-color--643a37, #643A37);
  stop-opacity: 0;
}

.q06hynbqf {
  stop-color: var(--svg-color--7d436f, #7D436F);
  stop-opacity: 0;
}

.qf7fwj8si {
  d: path("M12.608 8.423a3.83 3.83 0 0 0-3.83 3.83v9.82a3.83 3.83 0 0 0 6.976 2.185a3.8 3.8 0 0 1-.192-1.2V12.254c0-.642.159-1.248.438-1.78a3.83 3.83 0 0 0-3.392-2.05");
}

.r0q1ucbcl {
  stop-color: var(--svg-color--9f7566, #9F7566);
}

.s28fv4bdt {
  stop-color: var(--svg-color--865f54, #865F54);
}

.sniln6l-o {
  stop-color: var(--svg-color--783d64, #783D64);
}

.tg8dncaxu {
  stop-color: var(--svg-color--754f48, #754F48);
}

.tnclz_bha {
  stop-color: var(--svg-color--835260, #835260);
  stop-opacity: 0;
}

.v-999jmkf {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  fill: var(--svg-color--653845, #653845);
  rx: 3.83px;
}

.vhdi0jbww {
  stop-color: var(--svg-color--98756e, #98756E);
  stop-opacity: 0;
}

.vhei7_ecu {
  stop-color: var(--svg-color--765049, #765049);
}

.vobj_cc7n {
  stop-color: var(--svg-color--7e5556, #7E5556);
  stop-opacity: 0;
}

.wmmlx-bzu {
  d: path("m11.738 8.766l.13.037a4 4 0 0 1 2.914 3.85v9.058a1.522 1.522 0 1 1-3.044 0z");
}

.wx_1lpbxx {
  stop-color: var(--svg-color--7c554d, #7C554D);
  stop-opacity: 0;
}

.xz_i-xa1b {
  stop-color: var(--svg-color--613636, #613636);
  stop-opacity: 0;
}

</style>
