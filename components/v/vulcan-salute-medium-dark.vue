<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSXxcbc)"><path class="dkc15pbra"/><path fill="url(#i865rvT)" class="w6diq8b2m"/><path fill="url(#it55Ydd)" class="w6diq8b2m"/><path fill="url(#iHzGYCc)" class="w6diq8b2m"/></g><path fill="url(#icp2qdb)" class="u357n587q"/><path fill="url(#iNhkT2d)" class="u357n587q"/><g filter="url(#ivqbPXc)"><rect transform="rotate(-22.578 4.94 9)" class="q928nqo-o"/></g><path fill="url(#iLwCece)" class="ycudmab1m"/><path fill="url(#iwgvfOc)" class="ycudmab1m"/><path fill="url(#ieWYdLd)" class="ycudmab1m"/><path fill="url(#ijGhhge)" class="ycudmab1m"/><path fill="url(#iDubY5c)" class="ycudmab1m"/><g filter="url(#it4r8qc)"><rect transform="rotate(-19.107 9.287 5.753)" class="ei7x5eyav"/></g><path fill="url(#i1ja2ed)" class="bpb_98wvn"/><path fill="url(#iNwuX6v)" class="bpb_98wvn"/><path fill="url(#iOOHfKr)" class="bpb_98wvn"/><path fill="url(#irun17b)" class="bpb_98wvn"/><g filter="url(#ictSfPe)"><rect fill="url(#i6XtKAc)" transform="rotate(16.763 19.015 3.744)" class="ispvntb8a"/></g><path fill="url(#iohi2nd)" class="js5oatb-a"/><path fill="url(#iZyaCDR)" class="js5oatb-a"/><path fill="url(#izhlkob)" class="js5oatb-a"/><g filter="url(#iUySj3b)"><rect fill="url(#i0Idtrk)" transform="rotate(20.79 23.501 5.9)" class="v4_8p0nkk"/></g><g filter="url(#iB5KgDc)"><path stroke="url(#ivoZjvb)" class="pg0frac3p"/></g><g filter="url(#iqDvThe)"><path stroke="url(#i0xJWGc)" class="xtw-h0d1h"/></g><path fill="url(#ik3thZd)" class="apu3jebpp"/><g filter="url(#iWq9vVb)"><path stroke="url(#iM9Sbqc)" class="zrqlevncg"/></g><g filter="url(#imTt37k)"><path stroke="url(#ikaEAvb)" class="f78duk3si"/></g><g filter="url(#iu9XBkc)"><path stroke="url(#ijtvrNd)" class="i0g09bc1d"/></g><path fill="url(#iLRGIsb)" class="kfoowdb5f"/><path fill="url(#i23T8sc)" class="kfoowdb5f"/><path fill="url(#iBkSZQb)" class="kfoowdb5f"/><path fill="url(#iAtWULb)" class="kfoowdb5f"/><path fill="url(#iVVqWxb)" class="kfoowdb5f"/><path fill="url(#it14qrb)" class="kfoowdb5f"/><path fill="url(#i1W8R0C)" class="kfoowdb5f"/><defs><linearGradient id="icp2qdb" x1="9.166" x2="7.619" y1="11.893" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="fw95tfb4h"/><stop offset="1" class="iim9j-bub"/></linearGradient><linearGradient id="iNhkT2d" x1="9.892" x2="8.544" y1="14.509" y2="13.23" gradientUnits="userSpaceOnUse"><stop class="llqhz2bdk"/><stop offset="1" class="v050y05zk"/></linearGradient><linearGradient id="iLwCece" x1="8.064" x2="10.544" y1="11.739" y2="10.823" gradientUnits="userSpaceOnUse"><stop class="mxlmqjc-y"/><stop offset="1" class="gqx7dw7ac"/></linearGradient><linearGradient id="ijGhhge" x1="13.712" x2="11.431" y1="9.063" y2="10.063" gradientUnits="userSpaceOnUse"><stop class="wfmiukx7j"/><stop offset="1" class="fkw3d7vbz"/></linearGradient><linearGradient id="iDubY5c" x1="12.274" x2="11.931" y1="14.688" y2="13.594" gradientUnits="userSpaceOnUse"><stop class="llqhz2bdk"/><stop offset="1" class="v050y05zk"/></linearGradient><linearGradient id="i1ja2ed" x1="14.068" x2="16.62" y1="8.389" y2="9.169" gradientUnits="userSpaceOnUse"><stop class="v_kr7hb2y"/><stop offset="1" class="af9cz1bkz"/></linearGradient><linearGradient id="iNwuX6v" x1="19.999" x2="18.723" y1="10.579" y2="10.211" gradientUnits="userSpaceOnUse"><stop class="ph6nsob2q"/><stop offset="1" class="xfo40bb-l"/></linearGradient><linearGradient id="iOOHfKr" x1="19.332" x2="18.717" y1="10.556" y2="10.353" gradientUnits="userSpaceOnUse"><stop class="d1mllbjrx"/><stop offset="1" class="gakdjgb1i"/></linearGradient><linearGradient id="irun17b" x1="17.431" x2="15.63" y1="15.177" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="vj3udsj1t"/><stop offset="1" class="b2v583ptj"/></linearGradient><linearGradient id="i6XtKAc" x1="20.429" x2="20.36" y1="4.932" y2="15.559" gradientUnits="userSpaceOnUse"><stop class="a3_z2xhkr"/><stop offset="1" class="elec60bww"/></linearGradient><linearGradient id="iohi2nd" x1="18.612" x2="21.713" y1="10.639" y2="11.633" gradientUnits="userSpaceOnUse"><stop class="l9g6fvb1k"/><stop offset="1" class="yq0u2qb8m"/></linearGradient><linearGradient id="iZyaCDR" x1="19.69" x2="20.631" y1="16.039" y2="14.146" gradientUnits="userSpaceOnUse"><stop class="q-gccboqy"/><stop offset="1" class="qhzqt8b5s"/></linearGradient><linearGradient id="i0Idtrk" x1="24.958" x2="24.339" y1="5.487" y2="19.956" gradientUnits="userSpaceOnUse"><stop class="evbmxbc-k"/><stop offset="1" class="khiyoub3u"/></linearGradient><linearGradient id="ivoZjvb" x1="17.827" x2="16.575" y1="15.133" y2="16.218" gradientUnits="userSpaceOnUse"><stop class="ztm0e_b3u"/><stop offset="1" class="vwhkdlrgq"/></linearGradient><linearGradient id="i0xJWGc" x1="22.094" x2="21.172" y1="18.079" y2="18.159" gradientUnits="userSpaceOnUse"><stop class="ztm0e_b3u"/><stop offset="1" class="vwhkdlrgq"/></linearGradient><linearGradient id="iM9Sbqc" x1="27.214" x2="23.115" y1="14.916" y2="20.062" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ikaEAvb" x1="10.007" x2="8.388" y1="17.615" y2="18.138" gradientUnits="userSpaceOnUse"><stop class="ztm0e_b3u"/><stop offset="1" class="vwhkdlrgq"/></linearGradient><linearGradient id="ijtvrNd" x1="13" x2="11.754" y1="15.086" y2="15.036" gradientUnits="userSpaceOnUse"><stop class="ztm0e_b3u"/><stop offset="1" class="vwhkdlrgq"/></linearGradient><radialGradient id="i865rvT" cx="0" cy="0" r="1" gradientTransform="matrix(5.57964 -3.27694 6.45506 10.99104 7.087 26.957)" gradientUnits="userSpaceOnUse"><stop class="lzav1ju_h"/><stop offset="1" class="ai69lckgn"/></radialGradient><radialGradient id="it55Ydd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50706 8.21304 -8.36063 -3.57008 22.5 25.357)" gradientUnits="userSpaceOnUse"><stop class="jvs4veb5e"/><stop offset="1" class="q4ic-9bzb"/></radialGradient><radialGradient id="iHzGYCc" cx="0" cy="0" r="1" gradientTransform="rotate(122.492 6.683 17.828)scale(9.17623 4.3211)" gradientUnits="userSpaceOnUse"><stop class="augeicbpr"/><stop offset="1" class="qtnyoe6zz"/></radialGradient><radialGradient id="iwgvfOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.88994 .30388 -1.63403 -4.7854 13.478 9.714)" gradientUnits="userSpaceOnUse"><stop class="r9tmkbbhr"/><stop offset="1" class="l7c2v_sbh"/></radialGradient><radialGradient id="ieWYdLd" cx="0" cy="0" r="1" gradientTransform="matrix(.41951 -.13185 1.49361 4.7524 8.706 12.348)" gradientUnits="userSpaceOnUse"><stop class="rc9csgezl"/><stop offset="1" class="qv1e3eb2q"/></radialGradient><radialGradient id="izhlkob" cx="0" cy="0" r="1" gradientTransform="rotate(-160.567 12.547 6.208)scale(.74532 1.9169)" gradientUnits="userSpaceOnUse"><stop class="g5v9d8oze"/><stop offset="1" class="waw90piqz"/></radialGradient><radialGradient id="ik3thZd" cx="0" cy="0" r="1" gradientTransform="matrix(1.29719 1.10259 -3.33471 3.92326 24.013 13.79)" gradientUnits="userSpaceOnUse"><stop class="cix1u3i-b"/><stop offset="1" class="bj_c80e5c"/></radialGradient><radialGradient id="iLRGIsb" cx="0" cy="0" r="1" gradientTransform="matrix(.96216 19.58178 -15.02288 .73816 14.494 10.536)" gradientUnits="userSpaceOnUse"><stop offset=".899" class="xwm4e9a0z"/><stop offset="1" class="ykdiu0b8r"/></radialGradient><radialGradient id="i23T8sc" cx="0" cy="0" r="1" gradientTransform="matrix(-.02402 2.56503 -.76778 -.0072 13.792 10.382)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="t25e2n4al"/><stop offset="1" class="nw0-oqbas"/></radialGradient><radialGradient id="iBkSZQb" cx="0" cy="0" r="1" gradientTransform="rotate(136.84 11.734 12.58)scale(3.56633 2.41749)" gradientUnits="userSpaceOnUse"><stop class="m9s3l41cu"/><stop offset="1" class="mrd148bvv"/></radialGradient><radialGradient id="iAtWULb" cx="0" cy="0" r="1" gradientTransform="rotate(124.344 10.931 9.57)scale(2.30423 2.42474)" gradientUnits="userSpaceOnUse"><stop class="m9s3l41cu"/><stop offset="1" class="mrd148bvv"/></radialGradient><radialGradient id="iVVqWxb" cx="0" cy="0" r="1" gradientTransform="rotate(137.036 9.512 6.026)scale(2.66463 2.35358)" gradientUnits="userSpaceOnUse"><stop class="m9s3l41cu"/><stop offset="1" class="mrd148bvv"/></radialGradient><radialGradient id="it14qrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90997 2.55112 -1.66421 -.59361 10.873 5.597)" gradientUnits="userSpaceOnUse"><stop class="m9s3l41cu"/><stop offset="1" class="mrd148bvv"/></radialGradient><radialGradient id="i1W8R0C" cx="0" cy="0" r="1" gradientTransform="rotate(113.794 -.205 6.658)scale(1.18141 1.33457)" gradientUnits="userSpaceOnUse"><stop class="m9s3l41cu"/><stop offset="1" class="mrd148bvv"/></radialGradient><filter id="iSXxcbc" width="27.027" height="28.645" x="2.958" y="1.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.298039 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1630"/></filter><filter id="ivqbPXc" width="6.832" height="10.115" x="3.67" y="7.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".75"/></filter><filter id="it4r8qc" width="6.862" height="11.328" x="7.99" y="3.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".75"/></filter><filter id="ictSfPe" width="7.078" height="13.072" x="14.684" y="2.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".75"/></filter><filter id="iUySj3b" width="7.735" height="12.875" x="18.521" y="4.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".75"/></filter><filter id="iB5KgDc" width="4.556" height="2.719" x="14.008" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".3"/></filter><filter id="iqDvThe" width="2.968" height="5.692" x="19.958" y="12.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".3"/></filter><filter id="iWq9vVb" width="8.372" height="8.6" x="20.842" y="12.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".75"/></filter><filter id="imTt37k" width="4.049" height="3.811" x="6.726" y="14.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".3"/></filter><filter id="iu9XBkc" width="3.874" height="3.076" x="10.581" y="12.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1630" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:vulcan-salute-medium-dark" /></template>
<style>
.a3_z2xhkr {
  stop-color: var(--svg-color--a17e73, #A17E73);
}

.af9cz1bkz {
  stop-color: var(--svg-color--624039, #624039);
  stop-opacity: 0;
}

.ai69lckgn {
  stop-color: var(--svg-color--74494d, #74494D);
  stop-opacity: 0;
}

.apu3jebpp {
  d: path("m22.258 15.929l-.008.011c-.348 1.417-.32 4.26 1.725 6.455c.62-1.007 1.632-2.361 2.242-3.152l2.283-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.283 2.457z");
}

.augeicbpr {
  stop-color: var(--svg-color--86575f, #86575F);
}

.b2v583ptj {
  stop-color: var(--svg-color--8c605f, #8C605F);
  stop-opacity: 0;
}

.bj_c80e5c {
  stop-color: var(--svg-color--705148, #705148);
  stop-opacity: 0;
}

.bpb_98wvn {
  d: path("M13.8 11.81c.083 2.688 2.763 3.825 3.94 3.481l2.865-8.797l.342-1.081a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.298 3.9a290 290 0 0 0-2.415 7.812a.15.15 0 0 1-.083.096");
}

.cix1u3i-b {
  stop-color: var(--svg-color--705148, #705148);
}

.d1mllbjrx {
  stop-color: var(--svg-color--58322c, #58322C);
}

.dkc15pbra {
  fill: var(--svg-color--8c605e, #8C605E);
  d: path("M20.947 5.413a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.298 3.9a290 290 0 0 0-2.415 7.812c-.041.142-.241.147-.287.006c-.6-1.825-1.558-4.734-1.856-5.613c-.446-1.312-1.887-1.94-3.165-1.485a2.43 2.43 0 0 0-1.473 3.103l.368 1.034A2.45 2.45 0 0 0 3.101 10.9l.679 1.904c.235.696.904 2.518 1.148 4.869l.065.645c.244 2.454.519 5.22 1.953 7.523a8.33 8.33 0 0 0 7.28 4.276a8.3 8.3 0 0 0 3.476-.757c1.361-.584 2.62-1.481 3.6-2.802c1.16-1.472 1.546-2.166 2.139-3.23c.102-.184.21-.378.33-.59c.576-1.02 1.763-2.611 2.445-3.496l2.284-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.283 2.457l3.146-8.221a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.ei7x5eyav {
  width: 1.494px;
  height: 8.726px;
  x: 9.287px;
  y: 5.753px;
  fill: var(--svg-color--9b7970, #9B7970);
  rx: 0.747px;
}

.elec60bww {
  stop-color: var(--svg-color--895e5e, #895E5E);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.evbmxbc-k {
  stop-color: var(--svg-color--9f7470, #9F7470);
}

.f78duk3si {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M7.626 17.142c.332-.159 1.522-1.111 2.249-2.01");
}

.fkw3d7vbz {
  stop-color: var(--svg-color--7b594d, #7B594D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fw95tfb4h {
  stop-color: var(--svg-color--613a32, #613A32);
}

.g5v9d8oze {
  stop-color: var(--svg-color--7b5a4f, #7B5A4F);
}

.gakdjgb1i {
  stop-color: var(--svg-color--58322c, #58322C);
  stop-opacity: 0;
}

.gqx7dw7ac {
  stop-color: var(--svg-color--5b2f28, #5B2F28);
  stop-opacity: 0;
}

.i0g09bc1d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M11.481 14.183c.363-.056 1.514-.346 2.074-1.276");
}

.iim9j-bub {
  stop-color: var(--svg-color--613a32, #613A32);
  stop-opacity: 0;
}

.ispvntb8a {
  width: 1.494px;
  height: 10.452px;
  x: 19.015px;
  y: 3.744px;
  rx: 0.747px;
}

.js5oatb-a {
  d: path("m20.515 6.777l-2.85 8.68c.46.614 1.787 1.854 3.799 1.94c0-.037.3-.584.787-1.45l3.146-8.22a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.jvs4veb5e {
  stop-color: var(--svg-color--916161, #916161);
}

.kfoowdb5f {
  d: path("M20.93 5.413a2.45 2.45 0 0 0-1.592-3.071A2.436 2.436 0 0 0 16.27 3.9a290 290 0 0 0-2.42 7.813c-.041.142-.241.147-.287.006c-.601-1.824-1.562-4.734-1.86-5.614c-.447-1.312-1.892-1.94-3.172-1.485a2.43 2.43 0 0 0-1.476 3.103l.37 1.034a2.46 2.46 0 0 0-2.892-.986A2.447 2.447 0 0 0 3.045 10.9l.68 1.904c.237.696.907 2.518 1.15 4.869q.034.318.066.645c.245 2.454.52 5.22 1.957 7.523a8.35 8.35 0 0 0 7.296 4.276a8.3 8.3 0 0 0 3.484-.757c1.363-.584 2.626-1.481 3.607-2.802c1.162-1.472 1.55-2.166 2.143-3.23l.331-.59c.578-1.02 1.767-2.611 2.451-3.496l2.289-2.58c.954-1.03 1.044-2.549-.105-3.61c-1.031-.952-2.74-.806-3.87.438l-2.288 2.457l3.153-8.221a2.456 2.456 0 0 0-1.465-3.181c-1.266-.458-2.672.182-3.129 1.446q-.199.55-.426 1.187z");
}

.khiyoub3u {
  stop-color: var(--svg-color--8d625e, #8D625E);
  stop-opacity: 0;
}

.l7c2v_sbh {
  stop-color: var(--svg-color--775e56, #775E56);
  stop-opacity: 0;
}

.l9g6fvb1k {
  stop-color: var(--svg-color--593029, #593029);
}

.llqhz2bdk {
  stop-color: var(--svg-color--8c605e, #8C605E);
}

.lzav1ju_h {
  stop-color: var(--svg-color--74494d, #74494D);
}

.m9s3l41cu {
  stop-color: var(--svg-color--a58074, #A58074);
}

.mrd148bvv {
  stop-color: var(--svg-color--a58074, #A58074);
  stop-opacity: 0;
}

.mxlmqjc-y {
  stop-color: var(--svg-color--5b2f28, #5B2F28);
}

.nw0-oqbas {
  stop-color: var(--svg-color--624038, #624038);
  stop-opacity: 0;
}

.pg0frac3p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M14.908 13.998c.406.297 1.524.897 2.757.918");
}

.ph6nsob2q {
  stop-color: var(--svg-color--4d241e, #4D241E);
}

.q-gccboqy {
  stop-color: var(--svg-color--8d605f, #8D605F);
}

.q4ic-9bzb {
  stop-color: var(--svg-color--916161, #916161);
  stop-opacity: 0;
}

.q928nqo-o {
  width: 1.494px;
  height: 7.581px;
  x: 4.941px;
  y: 9px;
  fill: var(--svg-color--9b7970, #9B7970);
  rx: 0.747px;
}

.qhzqt8b5s {
  stop-color: var(--svg-color--8d605f, #8D605F);
  stop-opacity: 0;
}

.qtnyoe6zz {
  stop-color: var(--svg-color--86575f, #86575F);
  stop-opacity: 0;
}

.qv1e3eb2q {
  stop-color: var(--svg-color--51241e, #51241E);
  stop-opacity: 0;
}

.r9tmkbbhr {
  stop-color: var(--svg-color--775e56, #775E56);
}

.rc9csgezl {
  stop-color: var(--svg-color--51241e, #51241E);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.t25e2n4al {
  stop-color: var(--svg-color--624038, #624038);
}

.u357n587q {
  d: path("M4.665 15.951a4.99 4.99 0 0 0 5.086-1.405L7.452 8.73a2.45 2.45 0 0 0-4.351 2.17l.679 1.904l.057.168c.196.571.557 1.623.828 2.978");
}

.v_kr7hb2y {
  stop-color: var(--svg-color--624039, #624039);
}

.v050y05zk {
  stop-color: var(--svg-color--8c605e, #8C605E);
  stop-opacity: 0;
}

.v4_8p0nkk {
  width: 1.589px;
  height: 10.452px;
  x: 23.501px;
  y: 5.899px;
  rx: 0.794px;
}

.vj3udsj1t {
  stop-color: var(--svg-color--8c605f, #8C605F);
}

.vwhkdlrgq {
  stop-color: var(--svg-color--917069, #917069);
  stop-opacity: 0;
}

.w6diq8b2m {
  d: path("M20.947 5.413a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.298 3.9a290 290 0 0 0-2.415 7.812c-.041.142-.241.147-.287.006c-.6-1.825-1.558-4.734-1.856-5.613c-.446-1.312-1.887-1.94-3.165-1.485a2.43 2.43 0 0 0-1.473 3.103l.368 1.034A2.45 2.45 0 0 0 3.101 10.9l.679 1.904c.235.696.904 2.518 1.148 4.869l.065.645c.244 2.454.519 5.22 1.953 7.523a8.33 8.33 0 0 0 7.28 4.276a8.3 8.3 0 0 0 3.476-.757c1.361-.584 2.62-1.481 3.6-2.802c1.16-1.472 1.546-2.166 2.139-3.23c.102-.184.21-.378.33-.59c.576-1.02 1.763-2.611 2.445-3.496l2.284-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.283 2.457l3.146-8.221a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.waw90piqz {
  stop-color: var(--svg-color--7b5a4f, #7B5A4F);
  stop-opacity: 0;
}

.wfmiukx7j {
  stop-color: var(--svg-color--7b594d, #7B594D);
}

.xfo40bb-l {
  stop-color: var(--svg-color--4d241e, #4D241E);
  stop-opacity: 0;
}

.xtw-h0d1h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m20.858 17.164l1.167-3.892");
}

.xwm4e9a0z {
  stop-color: var(--svg-color--7b4066, #7B4066);
  stop-opacity: 0;
}

.ycudmab1m {
  d: path("M13.596 11.72a.15.15 0 0 0 .037.06l.495 1.981c-1.612 1.435-3.434 1.475-4.143 1.387l-.237-.598l.003-.004L7.452 8.73l.019.028l-.369-1.034a2.43 2.43 0 0 1 1.473-3.103c1.278-.456 2.72.173 3.165 1.485c.298.88 1.256 3.788 1.856 5.613");
}

.ykdiu0b8r {
  stop-color: var(--svg-color--7b4066, #7B4066);
}

.yq0u2qb8m {
  stop-color: var(--svg-color--593029, #593029);
  stop-opacity: 0;
}

.zrqlevncg {
  stroke-linecap: round;
  d: path("m22.842 19.288l4.372-4.6");
}

.ztm0e_b3u {
  stop-color: var(--svg-color--917069, #917069);
}

</style>
