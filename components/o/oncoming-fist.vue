<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(70.668 28.188 17.267)" class="wndv1l6ib"/><rect fill="url(#i5IAmYi)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><rect fill="url(#ihAo6ve)" transform="rotate(70.668 28.188 17.267)" class="is9-ml1ik"/><g filter="url(#iuVvSMb)"><path fill="url(#iFbMf0b)" class="db14t0bwj"/></g><path fill="url(#ihZLQhH)" class="db14t0bwj"/><path fill="url(#i2VyqlD)" class="db14t0bwj"/><path fill="url(#iQFWkWc)" class="gy6s9obqv"/><path fill="url(#i5LVqme)" class="gy6s9obqv"/><path fill="url(#iR6F2ac)" class="gy6s9obqv"/><path fill="url(#i1u7Hxx)" class="qf7fwj8si"/><path fill="url(#iwgm7rc)" class="qf7fwj8si"/><rect fill="url(#iYFBN2d)" class="ow42gabgy"/><rect fill="url(#ia1cyyd)" class="ow42gabgy"/><rect fill="url(#iRJxs8c)" class="ow42gabgy"/><path fill="url(#iReRu8I)" class="erfqgldfp"/><path fill="url(#iKXjKUk)" class="erfqgldfp"/><g filter="url(#iQ92aXb)"><path fill="url(#iH261Ec)" class="iul4mlcuf"/></g><g filter="url(#ifB1u6d)"><path fill="url(#ihg6Mcp)" class="wmmlx-bzu"/></g><g filter="url(#iSWUxuc)"><path fill="url(#i6hV2te)" class="nv5_uv4vf"/></g><g filter="url(#i1E6VCd)"><path fill="url(#iq890sc)" class="n_jrau6-o"/></g><defs><linearGradient id="i5IAmYi" x1="36.113" x2="34.556" y1="24.75" y2="24.795" gradientUnits="userSpaceOnUse"><stop class="j63-8pbxx"/><stop offset="1" class="f9-i1vbrq"/></linearGradient><linearGradient id="iFbMf0b" x1="32.977" x2="15.986" y1="7.313" y2="20.349" gradientUnits="userSpaceOnUse"><stop class="r27zuylkd"/><stop offset="1" class="rom7dhbfv"/></linearGradient><linearGradient id="ihZLQhH" x1="1.994" x2="4.238" y1="16.017" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="gbx792bvh"/><stop offset="1" class="b_7_irzkl"/></linearGradient><linearGradient id="iQFWkWc" x1="9.654" x2="9.654" y1="24.891" y2="12.023" gradientUnits="userSpaceOnUse"><stop class="dum4sac3x"/><stop offset="1" class="bs7fshb0m"/></linearGradient><linearGradient id="i5LVqme" x1="8.964" x2="7.639" y1="17.93" y2="17.93" gradientUnits="userSpaceOnUse"><stop class="a_6-dr6sq"/><stop offset="1" class="iogco7b9v"/></linearGradient><linearGradient id="i1u7Hxx" x1="17.196" x2="17.196" y1="25.904" y2="12.191" gradientUnits="userSpaceOnUse"><stop class="dum4sac3x"/><stop offset="1" class="bs7fshb0m"/></linearGradient><linearGradient id="iYFBN2d" x1="15.238" x2="20.675" y1="21.517" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="dum4sac3x"/><stop offset="1" class="bs7fshb0m"/></linearGradient><linearGradient id="ia1cyyd" x1="19.392" x2="19.392" y1="7.641" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="dwuisxbps"/><stop offset="1" class="o5ttm2_0x"/></linearGradient><linearGradient id="iReRu8I" x1="21.863" x2="25.864" y1="21.329" y2="20.772" gradientUnits="userSpaceOnUse"><stop class="dum4sac3x"/><stop offset="1" class="bs7fshb0m"/></linearGradient><linearGradient id="iH261Ec" x1="6.448" x2="6.448" y1="10.628" y2="26.127" gradientUnits="userSpaceOnUse"><stop class="ta9g-3bva"/><stop offset="1" class="ofgoeqp-x"/></linearGradient><linearGradient id="ihg6Mcp" x1="13.26" x2="13.26" y1="8.766" y2="29.642" gradientUnits="userSpaceOnUse"><stop class="tad_3nbfc"/><stop offset="1" class="vwcj-tbki"/></linearGradient><linearGradient id="i6hV2te" x1="20.914" x2="20.914" y1="5.235" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="h5ux2ub2b"/><stop offset="1" class="qd59vqbam"/></linearGradient><linearGradient id="iq890sc" x1="27.681" x2="27.681" y1="7.266" y2="28.514" gradientUnits="userSpaceOnUse"><stop class="h5ux2ub2b"/><stop offset="1" class="qd59vqbam"/></linearGradient><radialGradient id="ihAo6ve" cx="0" cy="0" r="1" gradientTransform="matrix(1.2086 1.60516 -2.44203 1.83872 33.353 23.454)" gradientUnits="userSpaceOnUse"><stop class="wqxsfxbud"/><stop offset="1" class="qt2rdeaya"/></radialGradient><radialGradient id="i2VyqlD" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41485 3.40558 -4.95105 -3.51073 29.138 5.984)" gradientUnits="userSpaceOnUse"><stop class="krqyjfe1h"/><stop offset="1" class="p-jrq4bqb"/></radialGradient><radialGradient id="iR6F2ac" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3638 -10.4214 0 5.927 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="vfo3w7b7r"/><stop offset="1" class="ozruemedn"/></radialGradient><radialGradient id="iwgm7rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.0323 -10.7984 0 12.854 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="vfo3w7b7r"/><stop offset="1" class="ozruemedn"/></radialGradient><radialGradient id="iRJxs8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.7805 -10.7947 0 19.885 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="vfo3w7b7r"/><stop offset=".953" class="ozruemedn"/></radialGradient><radialGradient id="iKXjKUk" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.7256 -10.1586 0 26.838 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="vfo3w7b7r"/><stop offset=".953" class="ozruemedn"/></radialGradient><filter id="iuVvSMb" width="27.985" height="23.056" x="1.994" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.670588 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5693"/></filter><filter id="iQ92aXb" width="6.044" height="15.605" x="3.426" y="9.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5693" stdDeviation=".75"/></filter><filter id="ifB1u6d" width="6.044" height="17.467" x="10.238" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5693" stdDeviation=".75"/></filter><filter id="iSWUxuc" width="6.044" height="22.312" x="17.892" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5693" stdDeviation=".75"/></filter><filter id="i1E6VCd" width="5.613" height="20.281" x="24.875" y="5.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5693" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-fist" /></template>
<style>
.a_6-dr6sq {
  stop-color: var(--svg-color--f88928, #F88928);
}

.b_7_irzkl {
  stop-color: var(--svg-color--e69e3f, #E69E3F);
  stop-opacity: 0;
}

.bs7fshb0m {
  stop-color: var(--svg-color--f29a36, #F29A36);
  stop-opacity: 0;
}

.db14t0bwj {
  d: path("M1.994 12.711v8.35a3.83 3.83 0 0 0 6.97 2.194a3.831 3.831 0 0 0 6.79 1.003a3.831 3.831 0 0 0 7.267.027a3.83 3.83 0 0 0 6.957-2.21V9.359a4.25 4.25 0 0 0-4.459-4.245l-1.633.08a5.47 5.47 0 0 1-3.089-.776a4.1 4.1 0 0 0-3.883-.186l-1.297.621a6 6 0 0 1-2.59.588h-1.395a4 4 0 0 0-2.42.814L7.563 7.51c-.369.28-.796.566-1.227.734l-1.774.742c-1.703.691-2.568 2.078-2.568 3.726");
}

.dum4sac3x {
  stop-color: var(--svg-color--f29a36, #F29A36);
}

.dwuisxbps {
  stop-color: var(--svg-color--ffd240, #FFD240);
}

.erfqgldfp {
  d: path("M23.021 24.285a3.83 3.83 0 0 0 6.957-2.21v-9.822A3.83 3.83 0 0 0 24.02 9.07c-.975.653-.798 2.01-.798 3.184V23.06c0 .428-.07.84-.2 1.226");
}

.f9-i1vbrq {
  stop-color: var(--svg-color--ea8586, #EA8586);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gbx792bvh {
  stop-color: var(--svg-color--e69e3f, #E69E3F);
}

.gy6s9obqv {
  d: path("M8.778 13.08c0-.466-.15-.931-.507-1.228a3.83 3.83 0 0 0-6.277 2.946v6.264a3.83 3.83 0 0 0 6.97 2.193a3.8 3.8 0 0 1-.186-1.181z");
}

.h5ux2ub2b {
  stop-color: var(--svg-color--ffe64c, #FFE64C);
}

.iogco7b9v {
  stop-color: var(--svg-color--f88928, #F88928);
  stop-opacity: 0;
}

.is9-ml1ik {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  rx: 3.83px;
}

.iul4mlcuf {
  d: path("M4.926 10.628a4 4 0 0 1 3.044 3.884v7.2a1.522 1.522 0 0 1-3.044 0z");
}

.j63-8pbxx {
  stop-color: var(--svg-color--ea8586, #EA8586);
}

.krqyjfe1h {
  stop-color: var(--svg-color--ffeb53, #FFEB53);
}

.n_jrau6-o {
  d: path("m26.375 7.266l.075.03a4 4 0 0 1 2.538 3.723v12.222a1.307 1.307 0 1 1-2.613 0z");
}

.nv5_uv4vf {
  d: path("m19.392 5.235l.455.172a4 4 0 0 1 2.59 3.743v13.876a1.522 1.522 0 0 1-3.044 0z");
}

.o5ttm2_0x {
  stop-color: var(--svg-color--ffd240, #FFD240);
  stop-opacity: 0;
}

.ofgoeqp-x {
  stop-color: var(--svg-color--ffce43, #FFCE43);
  stop-opacity: 0;
}

.ow42gabgy {
  width: 7.66px;
  height: 18.465px;
  x: 15.562px;
  y: 8.423px;
  rx: 3.83px;
}

.ozruemedn {
  stop-color: var(--svg-color--e77d7e, #E77D7E);
}

.p-jrq4bqb {
  stop-color: var(--svg-color--ffeb53, #FFEB53);
  stop-opacity: 0;
}

.qd59vqbam {
  stop-color: var(--svg-color--ffe64c, #FFE64C);
  stop-opacity: 0;
}

.qf7fwj8si {
  d: path("M12.608 8.423a3.83 3.83 0 0 0-3.83 3.83v9.82a3.83 3.83 0 0 0 6.976 2.185a3.8 3.8 0 0 1-.192-1.2V12.254c0-.642.159-1.248.438-1.78a3.83 3.83 0 0 0-3.392-2.05");
}

.qt2rdeaya {
  stop-color: var(--svg-color--f3964b, #F3964B);
  stop-opacity: 0;
}

.r27zuylkd {
  stop-color: var(--svg-color--ffeb54, #FFEB54);
}

.rom7dhbfv {
  stop-color: var(--svg-color--ffba2c, #FFBA2C);
}

.ta9g-3bva {
  stop-color: var(--svg-color--ffce43, #FFCE43);
}

.tad_3nbfc {
  stop-color: var(--svg-color--ffd645, #FFD645);
}

.vfo3w7b7r {
  stop-color: var(--svg-color--e77d7e, #E77D7E);
  stop-opacity: 0;
}

.vwcj-tbki {
  stop-color: var(--svg-color--ffd645, #FFD645);
  stop-opacity: 0;
}

.wmmlx-bzu {
  d: path("m11.738 8.766l.13.037a4 4 0 0 1 2.914 3.85v9.058a1.522 1.522 0 1 1-3.044 0z");
}

.wndv1l6ib {
  width: 7.66px;
  height: 16.279px;
  x: 28.188px;
  y: 17.267px;
  fill: var(--svg-color--dd7f3d, #DD7F3D);
  rx: 3.83px;
}

.wqxsfxbud {
  stop-color: var(--svg-color--f3964b, #F3964B);
}

</style>
