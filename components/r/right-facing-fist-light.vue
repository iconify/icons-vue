<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#if6cfde)" transform="matrix(-1 0 0 1 24.164 15.716)" class="njm0dpb1e"/><g filter="url(#iEa5TUb)"><path fill="url(#iQLzNkb)" class="a7bucp0yb"/></g><g filter="url(#iOxdmXc)"><path fill="url(#ieeLtBd)" clip-rule="evenodd" class="bn_icbbch"/><path fill="url(#iJELS6b)" clip-rule="evenodd" class="bn_icbbch"/></g><path fill="url(#idGXfqb)" clip-rule="evenodd" class="bn_icbbch"/><path fill="url(#iUQYJ0b)" clip-rule="evenodd" class="bn_icbbch"/><path fill="url(#iPeTjuc)" clip-rule="evenodd" class="bn_icbbch"/><path fill="url(#iwTkQAc)" clip-rule="evenodd" class="bn_icbbch"/><path fill="url(#iplA4PE)" clip-rule="evenodd" class="bn_icbbch"/><path fill="url(#iDbMuXd)" clip-rule="evenodd" class="bn_icbbch"/><path fill="url(#iaAcD9b)" class="rfrehizge"/><path fill="url(#iIzvy5b)" class="rfrehizge"/><path fill="url(#iaAcD9b)" class="mn1-o161p"/><path fill="url(#iIzvy5b)" class="mn1-o161p"/><g filter="url(#iKL8vhb)"><path stroke="url(#iPveYCb)" class="mz969qbqt"/></g><g filter="url(#iT4uewe)"><path stroke="url(#iPrU5xc)" class="f-lhxgbqy"/></g><g filter="url(#i95KDBW)"><path fill="url(#i5mGmlK)" class="bh3tlmnji"/></g><g filter="url(#iXMb5fe)"><path stroke="url(#ii01Oad)" class="f1sqvludj"/></g><g filter="url(#ikfVYPb)"><path stroke="url(#ijVneFb)" class="ivu34ybyx"/></g><g filter="url(#irWspfd)"><path fill="url(#iWwC1hc)" class="w1myr7b3z"/></g><defs><radialGradient id="if6cfde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.45455 -2.5004 1.96327 -2.71245 5.915 4.096)" gradientUnits="userSpaceOnUse"><stop class="kc38vug1n"/><stop offset="1" class="guwhpsbgh"/></radialGradient><radialGradient id="iQLzNkb" cx="0" cy="0" r="1" gradientTransform="matrix(3.34023 1.05914 -1.73617 5.4754 19.024 20.474)" gradientUnits="userSpaceOnUse"><stop class="hicgpsbtp"/><stop offset="1" class="sdx5y1bvz"/></radialGradient><radialGradient id="ieeLtBd" cx="0" cy="0" r="1" gradientTransform="matrix(-20.67863 7.07665 -10.92678 -31.92907 25.455 13.316)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="icd8fhbfu"/><stop offset="1" class="ol6lln-9x"/></radialGradient><radialGradient id="iJELS6b" cx="0" cy="0" r="1" gradientTransform="matrix(3.38096 -.36661 .1081 .99695 19.243 17.218)" gradientUnits="userSpaceOnUse"><stop class="o9xixqbgr"/><stop offset="1" class="gcxcq1b1c"/></radialGradient><radialGradient id="iUQYJ0b" cx="0" cy="0" r="1" gradientTransform="matrix(5.65223 -10.42138 12.95581 7.02682 9.365 32.573)" gradientUnits="userSpaceOnUse"><stop class="tqd4_yb8j"/><stop offset="1" class="jp-nkzmpd"/></radialGradient><radialGradient id="iPeTjuc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.30621 -8.37322 5.14514 -1.41711 3.6 18.55)" gradientUnits="userSpaceOnUse"><stop class="kpay2mb3i"/><stop offset="1" class="c0n1b0gku"/></radialGradient><radialGradient id="iplA4PE" cx="0" cy="0" r="1" gradientTransform="matrix(1.26733 -1.80396 3.40014 2.38868 3.867 20.812)" gradientUnits="userSpaceOnUse"><stop class="ynyzls6wn"/><stop offset="1" class="z9ynm4bmz"/></radialGradient><radialGradient id="iDbMuXd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53833 -.45955 .38325 -2.95086 22.33 28.572)" gradientUnits="userSpaceOnUse"><stop class="x4r87d7_k"/><stop offset="1" class="s11vy8e-x"/></radialGradient><radialGradient id="iaAcD9b" cx="0" cy="0" r="1" gradientTransform="matrix(2.62072 -.57328 1.10205 5.03792 18.99 22.88)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="p0y1tmwma"/><stop offset="1" class="y9gyhubrd"/></radialGradient><linearGradient id="idGXfqb" x1="16" x2="16" y1="6.87" y2="10.771" gradientUnits="userSpaceOnUse"><stop class="agclh9bxw"/><stop offset="1" class="h3_mb0r9k"/></linearGradient><linearGradient id="iwTkQAc" x1="1.342" x2="5.98" y1="16.845" y2="17.347" gradientUnits="userSpaceOnUse"><stop class="rmfe762wy"/><stop offset="1" class="ed7pcqjnp"/></linearGradient><linearGradient id="iIzvy5b" x1="22.769" x2="22.672" y1="21.863" y2="26.743" gradientUnits="userSpaceOnUse"><stop class="ildi3ybup"/><stop offset="1" class="jo09f2gpx"/></linearGradient><linearGradient id="iPveYCb" x1="18.728" x2="19.442" y1="25.542" y2="15.287" gradientUnits="userSpaceOnUse"><stop class="wysldqoja"/><stop offset="1" class="h578k2bla"/></linearGradient><linearGradient id="iPrU5xc" x1="13.461" x2="16.812" y1="19.541" y2="17.358" gradientUnits="userSpaceOnUse"><stop class="ck9tz8b2c"/><stop offset="1" class="m2gcslbcq"/></linearGradient><linearGradient id="i5mGmlK" x1="23.163" x2="32.367" y1="16.48" y2="19.341" gradientUnits="userSpaceOnUse"><stop class="i_kb8swtu"/><stop offset="1" class="fwu-16bhg"/></linearGradient><linearGradient id="ii01Oad" x1="23.885" x2="30.102" y1="22.184" y2="13.514" gradientUnits="userSpaceOnUse"><stop offset=".448" class="da09a-vmu"/><stop offset="1" class="ciy5vot7u"/></linearGradient><linearGradient id="ijVneFb" x1="22.794" x2="31.484" y1="8.911" y2="7.807" gradientUnits="userSpaceOnUse"><stop offset=".448" class="zfgsai7gf"/><stop offset="1" class="rb9ypvr6g"/></linearGradient><linearGradient id="iWwC1hc" x1="19.206" x2="19.206" y1="17.773" y2="12.075" gradientUnits="userSpaceOnUse"><stop class="ro_2kpb-n"/><stop offset="1" class="i7fmxurrt"/></linearGradient><filter id="iEa5TUb" width="8.486" height="7.397" x="16.653" y="16.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.333333 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3367"/></filter><filter id="iOxdmXc" width="28.891" height="22.295" x="2.055" y="7.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.25"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.517647 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3367"/></filter><filter id="iKL8vhb" width="13.911" height="17.782" x="10.22" y="11.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3367" stdDeviation="1.25"/></filter><filter id="iT4uewe" width="6.695" height="8.342" x="11.87" y="13.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3367" stdDeviation=".75"/></filter><filter id="i95KDBW" width="9.014" height="12.34" x="21.585" y="10.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3367" stdDeviation="1"/></filter><filter id="iXMb5fe" width="9.877" height="12.488" x="20.427" y="11.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3367" stdDeviation=".75"/></filter><filter id="ikfVYPb" width="13.921" height="9.001" x="16.383" y="9.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3367" stdDeviation=".75"/></filter><filter id="irWspfd" width="13.429" height="8.17" x="15.175" y="10.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3367" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:right-facing-fist-light" /></template>
<style>
.a7bucp0yb {
  d: path("M22.308 18.65a4.8 4.8 0 0 0-.066-1.824h2.797v7.296h-6.703c-1.078 0-1.898-1.609-1.633-2.843c.266-1.235 1.432-2.277 2.711-2.203c.963.055 1.893.016 2.524-.073a.43.43 0 0 0 .37-.354");
}

.agclh9bxw {
  stop-color: var(--svg-color--f9cbad, #F9CBAD);
}

.bh3tlmnji {
  d: path("m26.002 12.31l-2.417 3.932c1.3 1.373.685 3.563.302 4.408H28.6v-8.34z");
}

.bn_icbbch {
  fill-rule: evenodd;
  d: path("M24.445 7.888a5.5 5.5 0 0 1 5.5 5.5v5.625h-.004v.399c.01.724-.205 2.58-1.043 3.804c-1.046 1.531-2.859 2.75-4.64 2.75h-2.104c.075.281.102.573.134.921l.001.017c0 1.023-.437 2.562-2.64 3c-.985.148-2-.274-2.829-.93a91 91 0 0 1-1.961-1.64l-.832-.705c-.357-.309-.862-.745-1.472-.788c-.835-.058-2.42-.379-4.352-2.219c-.78-.742-1.4-1.748-1.755-2.322a10 10 0 0 0-.221-.35q-.08-.115-.138-.211c-.235-.375-.328-.523-1.331-.523l.007-.008h-.71a2 2 0 0 1-2-2v-8.32a2 2 0 0 1 2-2zm-7.302 12.3c-.273-.474-.686-1.271-.87-1.917c-.273-.961.24-1.07.485-1.117c.37-.07.942-.062 1.536-.053c.201.003.405.006.604.006q.357 0 .758.005c1.227.012 2.667.026 3.399-.193c.133.066.398.318.398.805v.1c.002.583.004 1.208-.476 1.533c-.178.12-.531.147-.965.18c-.487.036-1.075.08-1.631.273h-.002l-.062.023c-.245.09-.482.21-.701.374a3.33 3.33 0 0 0-1.228 1.742c-.702-.82-1.131-1.54-1.228-1.752z");
}

.c0n1b0gku {
  stop-color: var(--svg-color--e3ac99, #E3AC99);
  stop-opacity: 0;
}

.ciy5vot7u {
  stop-color: var(--svg-color--ffddc2, #FFDDC2);
  stop-opacity: 0;
}

.ck9tz8b2c {
  stop-color: var(--svg-color--ffe7cc, #FFE7CC);
}

.da09a-vmu {
  stop-color: var(--svg-color--ffddc2, #FFDDC2);
}

.ed7pcqjnp {
  stop-color: var(--svg-color--edb49c, #EDB49C);
  stop-opacity: 0;
}

.f-lhxgbqy {
  stroke-linecap: round;
  d: path("M16.565 15.213c-.492-.07-1.647.085-2.322 1.267c-.676 1.182-.282 2.534 0 3.061");
}

.f1sqvludj {
  stroke-linecap: round;
  d: path("M22.427 21.878h2.877a3 3 0 0 0 3-3v-5.489");
}

.ft5dv1b6b {
  fill: none;
}

.fwu-16bhg {
  stop-color: var(--svg-color--e5a393, #E5A393);
  stop-opacity: 0;
}

.gcxcq1b1c {
  stop-color: var(--svg-color--af6b6c, #AF6B6C);
  stop-opacity: 0;
}

.guwhpsbgh {
  stop-color: var(--svg-color--9a5544, #9A5544);
}

.h3_mb0r9k {
  stop-color: var(--svg-color--f9cbad, #F9CBAD);
  stop-opacity: 0;
}

.h578k2bla {
  stop-color: var(--svg-color--ffe7cb, #FFE7CB);
  stop-opacity: 0;
}

.hicgpsbtp {
  stop-color: var(--svg-color--bd7b68, #BD7B68);
}

.i_kb8swtu {
  stop-color: var(--svg-color--e5a393, #E5A393);
}

.i7fmxurrt {
  stop-color: var(--svg-color--ecad9c, #ECAD9C);
  stop-opacity: 0;
}

.icd8fhbfu {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
}

.ildi3ybup {
  stop-color: var(--svg-color--c48795, #C48795);
  stop-opacity: 0;
}

.ivu34ybyx {
  stroke-linecap: round;
  d: path("M18.383 11.377h6.921a3 3 0 0 1 3 3v2");
}

.jo09f2gpx {
  stop-color: var(--svg-color--c48795, #C48795);
}

.jp-nkzmpd {
  stop-color: var(--svg-color--ba7c92, #BA7C92);
  stop-opacity: 0;
}

.kc38vug1n {
  stop-color: var(--svg-color--ae6d62, #AE6D62);
}

.kpay2mb3i {
  stop-color: var(--svg-color--e3ac99, #E3AC99);
}

.m2gcslbcq {
  stop-color: var(--svg-color--ffe7cc, #FFE7CC);
  stop-opacity: 0;
}

.mn1-o161p {
  d: path("m22.939 16.95l-.036.01l.011-.01z");
}

.mz969qbqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.72 15.263c-.05 1.77 2.53 8.037 6.91 10.781");
}

.njm0dpb1e {
  d: path("M0 0h9.563v7.109H0z");
}

.o9xixqbgr {
  stop-color: var(--svg-color--af6b6c, #AF6B6C);
}

.ol6lln-9x {
  stop-color: var(--svg-color--f0bca3, #F0BCA3);
}

.p0y1tmwma {
  stop-color: var(--svg-color--d68b70, #D68B70);
}

.rb9ypvr6g {
  stop-color: var(--svg-color--ffe6ca, #FFE6CA);
  stop-opacity: 0;
}

.rfrehizge {
  d: path("M29.945 16.95v2.063h-.004v.399c.01.724-.205 2.58-1.043 3.804c-.818 1.198-2.105 2.204-3.479 2.586c-.372.1-.75.155-1.126.155h-2.141c-.082-.293-.328-.887-.968-1.465c-.116-.11-.341-.3-.62-.531c-.692-.578-1.642-1.268-2.181-2.006c.141-.47.509-1.232 1.233-1.748a2.8 2.8 0 0 1 .763-.397h.002c.556-.193 1.144-.237 1.631-.274c.434-.032.787-.059.965-.18c.48-.324.478-.95.476-1.532v-.1c0-.43-.206-.676-.346-.773z");
}

.rmfe762wy {
  stop-color: var(--svg-color--edb49c, #EDB49C);
}

.ro_2kpb-n {
  stop-color: var(--svg-color--ecad9c, #ECAD9C);
}

.s11vy8e-x {
  stop-color: var(--svg-color--f5c0b5, #F5C0B5);
  stop-opacity: 0;
}

.sdx5y1bvz {
  stop-color: var(--svg-color--a55c48, #A55C48);
}

.tqd4_yb8j {
  stop-color: var(--svg-color--ba7c92, #BA7C92);
}

.w1myr7b3z {
  d: path("M17.175 12.31h9.429l-1.565 4.17h-7.864z");
}

.wysldqoja {
  stop-color: var(--svg-color--ffe7cb, #FFE7CB);
}

.x4r87d7_k {
  stop-color: var(--svg-color--f5c0b5, #F5C0B5);
}

.y9gyhubrd {
  stop-color: var(--svg-color--d68b70, #D68B70);
  stop-opacity: 0;
}

.ynyzls6wn {
  stop-color: var(--svg-color--c3898d, #C3898D);
}

.z9ynm4bmz {
  stop-color: var(--svg-color--c3898d, #C3898D);
  stop-opacity: 0;
}

.zfgsai7gf {
  stop-color: var(--svg-color--ffe6ca, #FFE6CA);
}

</style>
