<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iObdTKe)" transform="matrix(-1 0 0 1 24.164 15.828)" class="njm0dpb1e"/><g filter="url(#i21R1Uc)"><path fill="url(#ivrDJVM)" class="qbizkwjvk"/></g><g filter="url(#imAfbge)"><path fill="url(#ilDyIHb)" clip-rule="evenodd" class="vy1qibb_n"/><path fill="url(#irIt9Pc)" clip-rule="evenodd" class="vy1qibb_n"/></g><path fill="url(#iFB0oDd)" clip-rule="evenodd" class="vy1qibb_n"/><path fill="url(#iXOq9kd)" clip-rule="evenodd" class="vy1qibb_n"/><path fill="url(#ih8OVIb)" clip-rule="evenodd" class="vy1qibb_n"/><path fill="url(#ibkhBFc)" clip-rule="evenodd" class="vy1qibb_n"/><path fill="url(#ibDLpBe)" clip-rule="evenodd" class="vy1qibb_n"/><path fill="url(#iiC4lSc)" clip-rule="evenodd" class="vy1qibb_n"/><path fill="url(#iXHuxRc)" class="dcnoy6bws"/><path fill="url(#irkZwPe)" class="dcnoy6bws"/><path fill="url(#iXHuxRc)" class="hq7nc_b5g"/><path fill="url(#irkZwPe)" class="hq7nc_b5g"/><g filter="url(#iDUTKne)"><path stroke="url(#idF5OTY)" class="sj7l7qbir"/></g><g filter="url(#iFw8aKd)"><path stroke="url(#iYTG9Kc)" class="wt1n0w0oz"/></g><g filter="url(#iRa9VMe)"><path fill="url(#iRwt3Be)" class="rdssrqtof"/></g><g filter="url(#ioRPt9c)"><path stroke="url(#ih6P4de)" class="k93nogb0w"/></g><g filter="url(#iqag0eb)"><path stroke="url(#iCnBVKd)" class="h4eheebwx"/></g><g filter="url(#iR4edEc)"><path fill="url(#iPGoPjS)" class="j0-vhfbmm"/></g><defs><radialGradient id="iObdTKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.45455 -2.5004 1.96327 -2.71245 5.915 4.096)" gradientUnits="userSpaceOnUse"><stop class="a2pgeft6p"/><stop offset="1" class="vypwhzxgc"/></radialGradient><radialGradient id="ivrDJVM" cx="0" cy="0" r="1" gradientTransform="matrix(3.34023 1.05914 -1.73617 5.4754 19.024 20.586)" gradientUnits="userSpaceOnUse"><stop class="hxlvlcc3n"/><stop offset="1" class="uzc7eacbr"/></radialGradient><radialGradient id="ilDyIHb" cx="0" cy="0" r="1" gradientTransform="matrix(-20.67863 7.07665 -10.92678 -31.92907 25.455 13.428)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="i43_zwi8b"/><stop offset="1" class="z_66y-lxi"/></radialGradient><radialGradient id="irIt9Pc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38096 -.36661 .1081 .99695 19.243 17.33)" gradientUnits="userSpaceOnUse"><stop class="b0q_b8bmb"/><stop offset="1" class="q7vpy_xpc"/></radialGradient><radialGradient id="iXOq9kd" cx="0" cy="0" r="1" gradientTransform="matrix(2.5387 -3.9178 6.64011 4.30275 12.876 28.24)" gradientUnits="userSpaceOnUse"><stop class="y8akcsb0f"/><stop offset="1" class="rng777bgu"/></radialGradient><radialGradient id="ih8OVIb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.30621 -8.37322 5.14514 -1.41711 3.6 18.661)" gradientUnits="userSpaceOnUse"><stop class="t971gxbqb"/><stop offset="1" class="qsn7wcc-e"/></radialGradient><radialGradient id="ibDLpBe" cx="0" cy="0" r="1" gradientTransform="matrix(1.26733 -1.80396 3.40014 2.38868 3.868 20.924)" gradientUnits="userSpaceOnUse"><stop class="t-4c4gw1u"/><stop offset="1" class="oh8m9579w"/></radialGradient><radialGradient id="iiC4lSc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53833 -.45955 .38325 -2.95086 22.33 28.684)" gradientUnits="userSpaceOnUse"><stop class="sx3_e8bck"/><stop offset="1" class="e1douwbnp"/></radialGradient><radialGradient id="iXHuxRc" cx="0" cy="0" r="1" gradientTransform="matrix(2.62072 -.57328 1.10205 5.03792 18.99 22.991)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="i03nfjb7q"/><stop offset="1" class="j9-g-eb3b"/></radialGradient><linearGradient id="iFB0oDd" x1="16" x2="16" y1="6.981" y2="10.882" gradientUnits="userSpaceOnUse"><stop class="ywvkd1b-t"/><stop offset="1" class="xe8qb69km"/></linearGradient><linearGradient id="ibkhBFc" x1="1.342" x2="5.98" y1="16.957" y2="17.459" gradientUnits="userSpaceOnUse"><stop class="va9rj2pho"/><stop offset="1" class="het_sccnu"/></linearGradient><linearGradient id="irkZwPe" x1="22.769" x2="22.769" y1="21.975" y2="29.051" gradientUnits="userSpaceOnUse"><stop class="f0cr8vb0n"/><stop offset="1" class="kpn6myhmn"/><stop offset="1" class="ivk32qtai"/></linearGradient><linearGradient id="idF5OTY" x1="18.728" x2="19.442" y1="25.654" y2="15.399" gradientUnits="userSpaceOnUse"><stop class="zxf8fbvkt"/><stop offset="1" class="onztulzij"/></linearGradient><linearGradient id="iYTG9Kc" x1="13.461" x2="16.812" y1="19.653" y2="17.47" gradientUnits="userSpaceOnUse"><stop class="g31rn7qdq"/><stop offset="1" class="mi_x_zbkv"/></linearGradient><linearGradient id="iRwt3Be" x1="23.163" x2="32.367" y1="16.592" y2="19.453" gradientUnits="userSpaceOnUse"><stop class="xtxri4b2x"/><stop offset="1" class="om1v59_lm"/></linearGradient><linearGradient id="ih6P4de" x1="23.885" x2="30.102" y1="22.296" y2="13.626" gradientUnits="userSpaceOnUse"><stop offset=".448" class="n4l67hb-g"/><stop offset="1" class="v6enekpta"/></linearGradient><linearGradient id="iCnBVKd" x1="22.794" x2="31.484" y1="9.023" y2="7.919" gradientUnits="userSpaceOnUse"><stop offset=".448" class="n4l67hb-g"/><stop offset="1" class="v6enekpta"/></linearGradient><linearGradient id="iPGoPjS" x1="19.206" x2="19.206" y1="17.885" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="f4e9ljjvu"/><stop offset="1" class="q9lb1q8tn"/></linearGradient><filter id="i21R1Uc" width="8.486" height="7.397" x="16.653" y="16.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.262745 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3355"/></filter><filter id="imAfbge" width="28.891" height="22.295" x="2.055" y="7.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.25"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.45098 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3355"/></filter><filter id="iDUTKne" width="13.911" height="17.782" x="10.22" y="11.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3355" stdDeviation="1.25"/></filter><filter id="iFw8aKd" width="6.695" height="8.342" x="11.87" y="13.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3355" stdDeviation=".75"/></filter><filter id="iRa9VMe" width="9.014" height="12.34" x="21.585" y="10.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3355" stdDeviation="1"/></filter><filter id="ioRPt9c" width="9.877" height="12.488" x="20.427" y="11.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3355" stdDeviation=".75"/></filter><filter id="iqag0eb" width="13.921" height="9.001" x="16.383" y="9.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3355" stdDeviation=".75"/></filter><filter id="iR4edEc" width="13.429" height="8.17" x="15.175" y="10.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3355" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:right-facing-fist-medium-light" /></template>
<style>
.a2pgeft6p {
  stop-color: var(--svg-color--945c50, #945C50);
}

.b0q_b8bmb {
  stop-color: var(--svg-color--a5625a, #A5625A);
}

.dcnoy6bws {
  d: path("M29.945 17.063v2.062h-.004v.398c.01.724-.205 2.58-1.043 3.805c-.818 1.198-2.105 2.204-3.479 2.586c-.372.1-.75.155-1.126.155h-2.141c-.082-.293-.328-.887-.968-1.465a14 14 0 0 0-.62-.531c-.692-.578-1.642-1.268-2.181-2.007c.141-.47.509-1.23 1.233-1.747a2.8 2.8 0 0 1 .763-.397h.002c.556-.193 1.144-.237 1.631-.274c.434-.032.787-.059.965-.18c.48-.324.478-.95.476-1.532v-.1c0-.43-.206-.676-.346-.773z");
}

.e1douwbnp {
  stop-color: var(--svg-color--f3bda0, #F3BDA0);
  stop-opacity: 0;
}

.f0cr8vb0n {
  stop-color: var(--svg-color--b4718f, #B4718F);
  stop-opacity: 0;
}

.f4e9ljjvu {
  stop-color: var(--svg-color--d08f7b, #D08F7B);
}

.ft5dv1b6b {
  fill: none;
}

.g31rn7qdq {
  stop-color: var(--svg-color--ffceab, #FFCEAB);
}

.h4eheebwx {
  stroke-linecap: round;
  d: path("M18.383 11.488h6.921a3 3 0 0 1 3 3v2.001");
}

.het_sccnu {
  stop-color: var(--svg-color--daa68a, #DAA68A);
  stop-opacity: 0;
}

.hq7nc_b5g {
  d: path("m22.939 17.063l-.036.008l.011-.009z");
}

.hxlvlcc3n {
  stop-color: var(--svg-color--a77056, #A77056);
}

.i03nfjb7q {
  stop-color: var(--svg-color--b67153, #B67153);
}

.i43_zwi8b {
  stop-color: var(--svg-color--fbc7a2, #FBC7A2);
}

.ivk32qtai {
  stop-color: var(--svg-color--b4718f, #B4718F);
}

.j0-vhfbmm {
  d: path("M17.175 12.422h9.429l-1.565 4.17h-7.864z");
}

.j9-g-eb3b {
  stop-color: var(--svg-color--b67153, #B67153);
  stop-opacity: 0;
}

.k93nogb0w {
  stroke-linecap: round;
  d: path("M22.427 21.99h2.877a3 3 0 0 0 3-3V13.5");
}

.kpn6myhmn {
  stop-color: var(--svg-color--995b87, #995B87);
}

.mi_x_zbkv {
  stop-color: var(--svg-color--ffceab, #FFCEAB);
  stop-opacity: 0;
}

.n4l67hb-g {
  stop-color: var(--svg-color--ffcdab, #FFCDAB);
}

.njm0dpb1e {
  d: path("M0 0h9.563v7.109H0z");
}

.oh8m9579w {
  stop-color: var(--svg-color--b77889, #B77889);
  stop-opacity: 0;
}

.om1v59_lm {
  stop-color: var(--svg-color--cb8977, #CB8977);
  stop-opacity: 0;
}

.onztulzij {
  stop-color: var(--svg-color--ffdcbf, #FFDCBF);
  stop-opacity: 0;
}

.q7vpy_xpc {
  stop-color: var(--svg-color--a5625a, #A5625A);
  stop-opacity: 0;
}

.q9lb1q8tn {
  stop-color: var(--svg-color--d08f7b, #D08F7B);
  stop-opacity: 0;
}

.qbizkwjvk {
  d: path("M22.308 18.761a4.8 4.8 0 0 0-.066-1.823h2.797v7.296h-6.703c-1.078 0-1.898-1.609-1.633-2.843c.266-1.235 1.432-2.277 2.711-2.203c.963.055 1.893.016 2.524-.074a.43.43 0 0 0 .37-.353");
}

.qsn7wcc-e {
  stop-color: var(--svg-color--d69e89, #D69E89);
  stop-opacity: 0;
}

.rdssrqtof {
  d: path("m26.002 12.422l-2.417 3.932c1.3 1.373.685 3.563.302 4.408H28.6v-8.34z");
}

.rng777bgu {
  stop-color: var(--svg-color--b77285, #B77285);
  stop-opacity: 0;
}

.sj7l7qbir {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.72 15.375c-.05 1.77 2.53 8.037 6.91 10.781");
}

.sx3_e8bck {
  stop-color: var(--svg-color--f3bda0, #F3BDA0);
}

.t-4c4gw1u {
  stop-color: var(--svg-color--b77889, #B77889);
}

.t971gxbqb {
  stop-color: var(--svg-color--d69e89, #D69E89);
}

.uzc7eacbr {
  stop-color: var(--svg-color--824732, #824732);
}

.v6enekpta {
  stop-color: var(--svg-color--ffcdab, #FFCDAB);
  stop-opacity: 0;
}

.va9rj2pho {
  stop-color: var(--svg-color--daa68a, #DAA68A);
}

.vy1qibb_n {
  fill-rule: evenodd;
  d: path("M24.445 8a5.5 5.5 0 0 1 5.5 5.5v5.625h-.004v.398c.01.724-.205 2.58-1.043 3.805c-1.046 1.531-2.859 2.75-4.64 2.75h-2.104c.075.28.102.573.134.921l.001.017c0 1.023-.437 2.562-2.64 3c-.985.148-2-.274-2.829-.93a95 95 0 0 1-1.961-1.64c-.27-.229-.515-.437-.703-.594l-.129-.11c-.357-.31-.862-.747-1.472-.789c-.835-.058-2.42-.38-4.352-2.219c-.78-.742-1.4-1.748-1.755-2.322a9 9 0 0 0-.221-.35a5 5 0 0 1-.138-.212c-.235-.374-.328-.522-1.331-.522l.007-.008h-.71a2 2 0 0 1-2-2V10a2 2 0 0 1 2-2zm-7.302 12.3c-.273-.474-.686-1.272-.87-1.917c-.273-.961.24-1.071.485-1.117c.37-.07.942-.062 1.536-.053c.201.003.405.006.604.006q.357 0 .758.005c1.227.012 2.667.026 3.399-.193c.133.065.398.317.398.805v.1c.002.582.004 1.208-.476 1.533c-.178.12-.531.147-.965.18c-.487.036-1.075.08-1.631.273h-.002l-.062.023c-.245.09-.482.21-.701.373a3.33 3.33 0 0 0-1.228 1.743c-.702-.82-1.131-1.54-1.228-1.752z");
}

.vypwhzxgc {
  stop-color: var(--svg-color--794130, #794130);
}

.wt1n0w0oz {
  stroke-linecap: round;
  d: path("M16.565 15.325c-.492-.07-1.647.085-2.322 1.267c-.676 1.182-.282 2.533 0 3.061");
}

.xe8qb69km {
  stop-color: var(--svg-color--f3c198, #F3C198);
  stop-opacity: 0;
}

.xtxri4b2x {
  stop-color: var(--svg-color--cb8977, #CB8977);
}

.y8akcsb0f {
  stop-color: var(--svg-color--b77285, #B77285);
}

.ywvkd1b-t {
  stop-color: var(--svg-color--f3c198, #F3C198);
}

.z_66y-lxi {
  stop-color: var(--svg-color--e4ad8c, #E4AD8C);
}

.zxf8fbvkt {
  stop-color: var(--svg-color--ffdcbf, #FFDCBF);
}

</style>
