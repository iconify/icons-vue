<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g filter="url(#icR3S7c)"><path fill="url(#iClvUxb)" class="ua26z45ag"/><path fill="url(#iCJKPpe)" class="ua26z45ag"/><path fill="url(#idlU71a)" class="ua26z45ag"/><path fill="url(#iqtZdDc)" class="ua26z45ag"/><path fill="url(#innAEEe)" class="ua26z45ag"/><path fill="url(#iEs5Hhd)" class="rdjeyccdk"/><path fill="url(#iPy2lqd)" class="ua26z45ag"/></g><g filter="url(#i9Jkape)"><rect fill="url(#ih18gHd)" class="wbxd66bhc"/><rect stroke="url(#iKMblFc)" class="yl9ilcbyd"/></g><rect fill="url(#ipxUHCd)" class="x50pembsf"/><rect fill="url(#ixyQYse)" class="x50pembsf"/><rect fill="url(#iF69rnd)" class="x50pembsf"/><rect fill="url(#iTmWJpb)" class="a46ho-z1h"/><g filter="url(#iODRikb)"><circle class="leo7-6bnu"/></g><g filter="url(#iG2ZKDL)"><circle class="a3m9mtlvz"/></g><g filter="url(#iMMgB4d)"><path fill="url(#iXwrfpe)" class="v48um_b4j"/></g><path fill="url(#iFoFuod)" class="d_-84abgu"/><path fill="url(#i02onDc)" class="d_-84abgu"/><path fill="url(#isdf2OG)" class="d_-84abgu"/><path fill="url(#i0kX3Nc)" class="d_-84abgu"/><path fill="url(#i3Uh6Ce)" class="d_-84abgu"/><path fill="url(#iqaJgAc)" class="d_-84abgu"/><path fill="url(#iWI9FZb)" class="d_-84abgu"/><g filter="url(#i0kipDz)"><path fill="url(#iOyYaGc)" class="l2nx8nbmr"/></g><path fill="url(#iSkYmZc)" class="s8fvee_bj"/><path fill="url(#icIB0ab)" class="s8fvee_bj"/><path fill="url(#icife2c)" class="s8fvee_bj"/><path fill="url(#iLQh6WO)" class="s8fvee_bj"/><path fill="url(#i1JUJ7f)" class="s8fvee_bj"/><path fill="url(#inN8XTc)" class="s8fvee_bj"/><path fill="url(#id7C53d)" class="s8fvee_bj"/><path fill="url(#iE0fvrD)" class="lhy1g2mlx"/><path fill="url(#iiIqTqm)" class="gz8vo1b6j"/><g filter="url(#iD6uike)"><rect class="yckxvybbr"/></g><g filter="url(#i0GVbJb)"><rect class="b4j87nb8s"/></g><rect fill="url(#iN5incb)" class="f2huxnbrn"/><rect fill="url(#iZZEyfb)" class="f2huxnbrn"/><rect fill="url(#ixkdnDd)" class="f2huxnbrn"/><rect fill="url(#idUv7Od)" class="n0hx4nbbr"/><rect fill="url(#iZZvWrz)" class="n0hx4nbbr"/><rect fill="url(#if6bosd)" class="n0hx4nbbr"/><g filter="url(#ioX2yVc)"><path stroke="url(#i4N5n6d)" class="g41l7tz1r"/></g><g filter="url(#iWe6cxH)"><path stroke="url(#iJqmAXc)" class="mc4p80biw"/></g><g filter="url(#iH8DE2c)"><path stroke="url(#i92Y8Sc)" class="c3h3qddlv"/></g><g filter="url(#iAZBKKe)"><path stroke="url(#igI30pd)" class="bgzy7rbhj"/></g><g filter="url(#iHdyyPd)"><path stroke="url(#iRrxlgd)" class="p-h5s5brh"/></g></g><defs><linearGradient id="ih18gHd" x1="15.999" x2="12.856" y1="23.42" y2="27.208" gradientUnits="userSpaceOnUse"><stop class="idvnfh51b"/><stop offset="1" class="i73qprb4j"/></linearGradient><linearGradient id="ipxUHCd" x1="15.05" x2="19.714" y1="26.291" y2="19.264" gradientUnits="userSpaceOnUse"><stop class="typz9pbxj"/><stop offset="1" class="cmgba8agn"/></linearGradient><linearGradient id="ixyQYse" x1="16.688" x2="16.688" y1="25.998" y2="22.445" gradientUnits="userSpaceOnUse"><stop class="iqyre-byx"/><stop offset="1" class="msvq59q-i"/></linearGradient><linearGradient id="iF69rnd" x1="16.688" x2="16.688" y1="17.407" y2="19.753" gradientUnits="userSpaceOnUse"><stop class="f8t67ubzw"/><stop offset="1" class="fgp642bun"/></linearGradient><linearGradient id="iXwrfpe" x1="25.859" x2="24.272" y1="9.536" y2="14.892" gradientUnits="userSpaceOnUse"><stop class="arb_upbxs"/><stop offset="1" class="sp-75hswm"/></linearGradient><linearGradient id="iFoFuod" x1="26.511" x2="24.751" y1="8.851" y2="14.789" gradientUnits="userSpaceOnUse"><stop class="u-1z0bc2x"/><stop offset="1" class="dcxtb6bsq"/></linearGradient><linearGradient id="i02onDc" x1="27.782" x2="26.511" y1="14.101" y2="12.898" gradientUnits="userSpaceOnUse"><stop class="brr59tv3o"/><stop offset="1" class="s56mtcc3s"/></linearGradient><linearGradient id="isdf2OG" x1="22.959" x2="24.939" y1="12.476" y2="12.476" gradientUnits="userSpaceOnUse"><stop class="brr59tv3o"/><stop offset="1" class="s56mtcc3s"/></linearGradient><linearGradient id="i0kX3Nc" x1="21.001" x2="27.814" y1="15.843" y2="12.476" gradientUnits="userSpaceOnUse"><stop class="brr59tv3o"/><stop offset="1" class="s56mtcc3s"/></linearGradient><linearGradient id="iWI9FZb" x1="29.314" x2="25.845" y1="4.414" y2="8.132" gradientUnits="userSpaceOnUse"><stop offset=".282" class="lj2y9qyjo"/><stop offset="1" class="omles_kzw"/></linearGradient><linearGradient id="iOyYaGc" x1="5.72" x2="9.301" y1="13.789" y2="16.417" gradientUnits="userSpaceOnUse"><stop class="hac_8ebud"/><stop offset="1" class="sp-75hswm"/></linearGradient><linearGradient id="iSkYmZc" x1="6.189" x2="4.145" y1="8.65" y2="14.951" gradientUnits="userSpaceOnUse"><stop class="u-1z0bc2x"/><stop offset="1" class="dcxtb6bsq"/></linearGradient><linearGradient id="icIB0ab" x1="7.316" x2="4.507" y1="16.617" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="brr59tv3o"/><stop offset="1" class="s56mtcc3s"/></linearGradient><linearGradient id="icife2c" x1="4.18" x2="7.376" y1="15.591" y2="12.817" gradientUnits="userSpaceOnUse"><stop class="qx0q0ibah"/><stop offset="1" class="ypk5rrhnn"/></linearGradient><linearGradient id="iLQh6WO" x1="3.456" x2="10.079" y1="6.545" y2="12.69" gradientUnits="userSpaceOnUse"><stop class="lj2y9qyjo"/><stop offset="1" class="omles_kzw"/></linearGradient><linearGradient id="inN8XTc" x1="1.876" x2="5.814" y1="6.437" y2="10.375" gradientUnits="userSpaceOnUse"><stop offset=".238" class="f-5f9xxcs"/><stop offset="1" class="u89k2g-sf"/></linearGradient><linearGradient id="iE0fvrD" x1="18.516" x2="18.516" y1="21.318" y2="22.678" gradientUnits="userSpaceOnUse"><stop class="ldep_ni8f"/><stop offset="1" class="c3ex79bkf"/></linearGradient><linearGradient id="iiIqTqm" x1="14.859" x2="14.859" y1="21.318" y2="22.678" gradientUnits="userSpaceOnUse"><stop class="ldep_ni8f"/><stop offset="1" class="c3ex79bkf"/></linearGradient><linearGradient id="iN5incb" x1="21.447" x2="20.527" y1="16.439" y2="16.439" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="iZZEyfb" x1="21.923" x2="21.923" y1="17.97" y2="17.062" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ixkdnDd" x1="19.874" x2="20.552" y1="16.592" y2="16.592" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="idUv7Od" x1="12.947" x2="12.027" y1="16.439" y2="16.439" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="iZZvWrz" x1="13.423" x2="13.423" y1="17.97" y2="17.062" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="if6bosd" x1="11.374" x2="12.052" y1="16.592" y2="16.592" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="i4N5n6d" x1="29.095" x2="25.282" y1="11.57" y2="15.351" gradientUnits="userSpaceOnUse"><stop class="vhq8occ2q"/><stop offset="1" class="gq4fbabya"/></linearGradient><linearGradient id="iJqmAXc" x1="7.782" x2="7.782" y1="10.358" y2="22.239" gradientUnits="userSpaceOnUse"><stop class="z13wi8c-d"/><stop offset="1" class="r1nmoycej"/></linearGradient><linearGradient id="i92Y8Sc" x1="17.554" x2="22.997" y1="18.351" y2="22.242" gradientUnits="userSpaceOnUse"><stop class="iitn73bvn"/><stop offset=".448" class="r1gk77bva"/><stop offset="1" class="iitn73bvn"/></linearGradient><linearGradient id="igI30pd" x1="16.733" x2="19.144" y1="21.564" y2="23.938" gradientUnits="userSpaceOnUse"><stop class="iitn73bvn"/><stop offset=".448" class="r1gk77bva"/><stop offset="1" class="iitn73bvn"/></linearGradient><linearGradient id="iRrxlgd" x1="13.039" x2="15.45" y1="21.564" y2="23.938" gradientUnits="userSpaceOnUse"><stop class="iitn73bvn"/><stop offset=".078" class="f6x822dyq"/><stop offset=".448" class="r1gk77bva"/><stop offset="1" class="iitn73bvn"/></linearGradient><radialGradient id="iClvUxb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.00116 23.4375 -30.12477 -7.71343 22.689 7.726)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="al9ukubhg"/><stop offset=".543" class="wwsqyibor"/><stop offset=".891" class="yw054yb8u"/></radialGradient><radialGradient id="iCJKPpe" cx="0" cy="0" r="1" gradientTransform="scale(17.3923 16.375)rotate(90 .038 .922)" gradientUnits="userSpaceOnUse"><stop offset=".884" class="t87xhhblh"/><stop offset="1" class="a4hmrqbwo"/></radialGradient><radialGradient id="idlU71a" cx="0" cy="0" r="1" gradientTransform="rotate(-137.793 14.134 -.056)scale(4.53529 2.73031)" gradientUnits="userSpaceOnUse"><stop class="gjskt6rxa"/><stop offset=".286" class="arb_upbxs"/><stop offset="1" class="g9372ycdl"/></radialGradient><radialGradient id="iqtZdDc" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 3.875 -6.70294 9.8382 .876 14.601)" gradientUnits="userSpaceOnUse"><stop class="qjndclbcv"/><stop offset="1" class="fdzzkr94y"/></radialGradient><radialGradient id="innAEEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.89497 6.79187 0 16.688 19.33)" gradientUnits="userSpaceOnUse"><stop class="m6uyf7c4l"/><stop offset="1" class="mru534bov"/></radialGradient><radialGradient id="iEs5Hhd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.6875 .25001 -.59651 -11.1842 27.376 19.413)" gradientUnits="userSpaceOnUse"><stop class="n8fbblb3t"/><stop offset="1" class="hljfr-qqw"/></radialGradient><radialGradient id="iPy2lqd" cx="0" cy="0" r="1" gradientTransform="rotate(124.608 11.47 14.217)scale(6.37863 5.88374)" gradientUnits="userSpaceOnUse"><stop class="n8fbblb3t"/><stop offset="1" class="hljfr-qqw"/></radialGradient><radialGradient id="iKMblFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5917 4.38412 -3.88417 -1.4102 19.713 19.837)" gradientUnits="userSpaceOnUse"><stop class="omar4t_8a"/><stop offset="1" class="r6cal3b4d"/></radialGradient><radialGradient id="iTmWJpb" cx="0" cy="0" r="1" gradientTransform="rotate(137.281 6.82 13.967)scale(3.68944 5.09474)" gradientUnits="userSpaceOnUse"><stop class="qf2crsb3h"/><stop offset="1" class="q623wgb9i"/></radialGradient><radialGradient id="i3Uh6Ce" cx="0" cy="0" r="1" gradientTransform="rotate(52.284 7.107 24.561)scale(5.92565 4.96071)" gradientUnits="userSpaceOnUse"><stop class="lj2y9qyjo"/><stop offset="1" class="omles_kzw"/></radialGradient><radialGradient id="iqaJgAc" cx="0" cy="0" r="1" gradientTransform="rotate(-149.503 20.004 3.057)scale(16.6104 12.5171)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="omles_kzw"/><stop offset="1" class="lj2y9qyjo"/></radialGradient><radialGradient id="i1JUJ7f" cx="0" cy="0" r="1" gradientTransform="matrix(-.18752 5.12613 -3.26208 -.11933 7.377 5.562)" gradientUnits="userSpaceOnUse"><stop class="fpytrg8nn"/><stop offset="1" class="x-4usgbhn"/></radialGradient><radialGradient id="id7C53d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.71506 -1.67605 1.71063 -8.89486 10.603 12.365)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="u89k2g-sf"/><stop offset="1" class="ogo8pshab"/></radialGradient><filter id="icR3S7c" width="27.248" height="25.398" x="3.689" y="5.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy=".4"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.12 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2988"/></filter><filter id="i9Jkape" width="14.611" height="11.516" x="8.693" y="17.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation="1"/></filter><filter id="iODRikb" width="3.169" height="3.169" x="13.474" y="20.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".25"/></filter><filter id="iG2ZKDL" width="3.169" height="3.169" x="17.07" y="20.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".25"/></filter><filter id="iMMgB4d" width="9.409" height="12.202" x="21.155" y="5.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".75"/></filter><filter id="i0kipDz" width="6.578" height="7.266" x="3.626" y="10.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".5"/></filter><filter id="iD6uike" width="2.5" height="3.5" x="19.36" y="14.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".25"/></filter><filter id="i0GVbJb" width="2.5" height="3.5" x="10.861" y="14.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".25"/></filter><filter id="ioX2yVc" width="6.813" height="7.188" x="24.001" y="9.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".5"/></filter><filter id="iWe6cxH" width="2.3" height="9.779" x="7.764" y="6.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".5"/></filter><filter id="iH8DE2c" width="3.413" height="3.781" x="17.869" y="18.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".15"/></filter><filter id="iAZBKKe" width="2.288" height="2.021" x="16.756" y="21.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".15"/></filter><filter id="iHdyyPd" width="2.288" height="2.021" x="13.062" y="21.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2988" stdDeviation=".15"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pig-face" /></template>
<style>
.a3m9mtlvz {
  cx: 18.654px;
  cy: 21.608px;
  r: 1.084px;
  fill: var(--svg-color--ff93d0, #FF93D0);
}

.a46ho-z1h {
  width: 9.234px;
  height: 6.625px;
  x: 12.07px;
  y: 18.539px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 3.313px;
}

.a4hmrqbwo {
  stop-color: var(--svg-color--ff6cd7, #FF6CD7);
}

.al9ukubhg {
  stop-color: var(--svg-color--ffc0ca, #FFC0CA);
}

.arb_upbxs {
  stop-color: var(--svg-color--f78296, #F78296);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b4j87nb8s {
  width: 1.5px;
  height: 2.5px;
  x: 11.361px;
  y: 15.454px;
  fill: var(--svg-color--ff648b, #FF648B);
  rx: 0.75px;
}

.bgzy7rbhj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.132 21.924c.045.452.416 1.339 1.537 1.267");
}

.brr59tv3o {
  stop-color: var(--svg-color--ffa0d5, #FFA0D5);
}

.c_lfom8in {
  stop-color: var(--svg-color--574d50, #574D50);
  stop-opacity: 0;
}

.c3ex79bkf {
  stop-color: var(--svg-color--ab087f, #AB087F);
}

.c3h3qddlv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M18.244 19.21c1.22 0 2.663.797 2.663 3.032");
}

.cmgba8agn {
  stop-color: var(--svg-color--ffafe5, #FFAFE5);
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.d_-84abgu {
  d: path("m26.389 6.229l3.09 3.09c.78.78.78 2.06 0 2.84l-3.09 3.09c-1.27 1.27-3.43.37-3.43-1.42v-6.17c0-1.79 2.17-2.69 3.43-1.43");
}

.dcxtb6bsq {
  stop-color: var(--svg-color--ffb5ea, #FFB5EA);
}

.f-5f9xxcs {
  stop-color: var(--svg-color--bd747c, #BD747C);
}

.f2huxnbrn {
  width: 1.5px;
  height: 2.5px;
  x: 20.189px;
  y: 15.189px;
  rx: 0.75px;
}

.f6x822dyq {
  stop-color: var(--svg-color--ffd8f1, #FFD8F1);
  stop-opacity: 0.174;
}

.f8t67ubzw {
  stop-color: var(--svg-color--ffabc8, #FFABC8);
}

.fdzzkr94y {
  stop-color: var(--svg-color--c86c80, #C86C80);
  stop-opacity: 0;
}

.fgp642bun {
  stop-color: var(--svg-color--ffabc8, #FFABC8);
  stop-opacity: 0;
}

.fpytrg8nn {
  stop-color: var(--svg-color--ffa4b7, #FFA4B7);
}

.ft5dv1b6b {
  fill: none;
}

.g41l7tz1r {
  stroke-linecap: round;
  d: path("M29.314 10.664L25.5 14.85");
}

.g9372ycdl {
  stop-color: var(--svg-color--f78296, #F78296);
  stop-opacity: 0;
}

.gjskt6rxa {
  stop-color: var(--svg-color--e2697d, #E2697D);
}

.gq4fbabya {
  stop-color: var(--svg-color--ffd8ee, #FFD8EE);
  stop-opacity: 0;
}

.gz8vo1b6j {
  d: path("M14.86 22.843a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.hac_8ebud {
  stop-color: var(--svg-color--bc4f87, #BC4F87);
}

.hljfr-qqw {
  stop-color: var(--svg-color--ffb5c8, #FFB5C8);
  stop-opacity: 0;
}

.i73qprb4j {
  stop-color: var(--svg-color--fc4992, #FC4992);
  stop-opacity: 0;
}

.idvnfh51b {
  stop-color: var(--svg-color--eb3f85, #EB3F85);
}

.iitn73bvn {
  stop-color: var(--svg-color--ffd6f0, #FFD6F0);
  stop-opacity: 0;
}

.iqyre-byx {
  stop-color: var(--svg-color--ff8df3, #FF8DF3);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.kfeabacio {
  stop-color: var(--svg-color--574d50, #574D50);
}

.l2nx8nbmr {
  d: path("M4.626 14.017c.288-1.725 1.542-2.427 2.156-2.578l2.422 4.422l-2.14.843z");
}

.ldep_ni8f {
  stop-color: var(--svg-color--d6085d, #D6085D);
}

.leo7-6bnu {
  cx: 15.059px;
  cy: 21.608px;
  r: 1.084px;
  fill: var(--svg-color--ff93d0, #FF93D0);
}

.lhy1g2mlx {
  d: path("M18.516 22.843a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.lj2y9qyjo {
  stop-color: var(--svg-color--ec9099, #EC9099);
}

.m6uyf7c4l {
  stop-color: var(--svg-color--ff857d, #FF857D);
}

.mc4p80biw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M8.914 7.372v7.48");
}

.mru534bov {
  stop-color: var(--svg-color--ff857d, #FF857D);
  stop-opacity: 0;
}

.msvq59q-i {
  stop-color: var(--svg-color--ff8df3, #FF8DF3);
  stop-opacity: 0;
}

.n0hx4nbbr {
  width: 1.5px;
  height: 2.5px;
  x: 11.689px;
  y: 15.189px;
  rx: 0.75px;
}

.n8fbblb3t {
  stop-color: var(--svg-color--ffb5c8, #FFB5C8);
}

.ogo8pshab {
  stop-color: var(--svg-color--cc8c93, #CC8C93);
}

.omar4t_8a {
  stop-color: var(--svg-color--ffd0ef, #FFD0EF);
}

.omles_kzw {
  stop-color: var(--svg-color--ec9099, #EC9099);
  stop-opacity: 0;
}

.p-h5s5brh {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.437 21.924c.046.452.417 1.339 1.538 1.267");
}

.q623wgb9i {
  stop-color: var(--svg-color--ffc7ea, #FFC7EA);
  stop-opacity: 0;
}

.qf2crsb3h {
  stop-color: var(--svg-color--ffc7ea, #FFC7EA);
}

.qjndclbcv {
  stop-color: var(--svg-color--c86c80, #C86C80);
}

.qx0q0ibah {
  stop-color: var(--svg-color--e88bc9, #E88BC9);
}

.r1gk77bva {
  stop-color: var(--svg-color--ffe1f4, #FFE1F4);
}

.r1nmoycej {
  stop-color: var(--svg-color--ffe5f4, #FFE5F4);
  stop-opacity: 0;
}

.r6cal3b4d {
  stop-color: var(--svg-color--ffcef0, #FFCEF0);
  stop-opacity: 0;
}

.rdjeyccdk {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M16.688 30.186c8.667 0 12.998-5.596 12.998-12.498c0-6.903-4.33-12.5-12.998-12.5s-13 5.597-13 12.5s4.332 12.498 13 12.498");
}

.s56mtcc3s {
  stop-color: var(--svg-color--ffaddb, #FFADDB);
  stop-opacity: 0;
}

.s8fvee_bj {
  d: path("M6.31 5.822L3.264 9.16c-.769.84-.769 2.219 0 3.059l3.044 3.328c1.252 1.368 3.38.399 3.38-1.53V7.363c0-1.928-2.128-2.898-3.38-1.54");
}

.sp-75hswm {
  stop-color: var(--svg-color--e3519c, #E3519C);
}

.t87xhhblh {
  stop-color: var(--svg-color--ff6cd7, #FF6CD7);
  stop-opacity: 0;
}

.typz9pbxj {
  stop-color: var(--svg-color--ff9de5, #FF9DE5);
}

.u-1z0bc2x {
  stop-color: var(--svg-color--ffc5de, #FFC5DE);
}

.u89k2g-sf {
  stop-color: var(--svg-color--cc8c93, #CC8C93);
  stop-opacity: 0;
}

.ua26z45ag {
  d: path("M16.688 30.186c8.667 0 12.998-5.596 12.998-12.498c0-6.903-4.33-12.5-12.998-12.5s-13 5.597-13 12.5s4.332 12.498 13 12.498");
}

.v48um_b4j {
  d: path("m25.749 7.171l2.787 2.787a1.82 1.82 0 0 1 0 2.562l-2.787 2.787c-1.146 1.145-3.094.334-3.094-1.28V8.46c0-1.615 1.957-2.426 3.094-1.29");
}

.vhq8occ2q {
  stop-color: var(--svg-color--ffd8ee, #FFD8EE);
}

.wbxd66bhc {
  width: 10.611px;
  height: 7.516px;
  x: 10.693px;
  y: 19.21px;
  rx: 3.758px;
}

.wwsqyibor {
  stop-color: var(--svg-color--ff8ca8, #FF8CA8);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x-4usgbhn {
  stop-color: var(--svg-color--ffa4b7, #FFA4B7);
  stop-opacity: 0;
}

.x50pembsf {
  width: 9.234px;
  height: 6.625px;
  x: 12.07px;
  y: 18.539px;
  rx: 3.313px;
}

.yckxvybbr {
  width: 1.5px;
  height: 2.5px;
  x: 19.86px;
  y: 15.454px;
  fill: var(--svg-color--ff648b, #FF648B);
  rx: 0.75px;
}

.yl9ilcbyd {
  width: 10.111px;
  height: 7.016px;
  x: 10.943px;
  y: 19.46px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 3.508px;
}

.ypk5rrhnn {
  stop-color: var(--svg-color--e88bc9, #E88BC9);
  stop-opacity: 0;
}

.yw054yb8u {
  stop-color: var(--svg-color--fa5292, #FA5292);
}

.z13wi8c-d {
  stop-color: var(--svg-color--ffe6f4, #FFE6F4);
}

</style>
