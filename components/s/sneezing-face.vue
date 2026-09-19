<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#ipOlTGc)"><path fill="url(#i48x0mi)" clip-rule="evenodd" class="j6b88sbai"/></g><path fill="url(#iAYOAEc)" class="yk76sv2tk"/><g filter="url(#iBDfR9c)" class="ljb4srbfs"><path fill="url(#ihYVRac)" class="mue744bew"/><path fill="url(#ihYVRac)" class="ewlno3sqc"/></g><path fill="url(#ifSYanb)" class="jfk2tlz6z"/><path fill="url(#iOZJFye)" class="jjgocabki"/><g filter="url(#i5lLomc)"><path fill="url(#iZk2peJ)" class="e8j1wibpg"/><path fill="url(#iZk2peJ)" class="xpgr2bbbu"/></g><path fill="url(#i8ICsPd)" class="syggllbnk"/><path fill="url(#i38NwLb)" class="c_8_uccav"/><path fill="url(#id0HIkb)" class="e056lobrv"/><g filter="url(#icIsatt)"><path fill="url(#izy9iVb)" class="fa5h9x75c"/></g><g filter="url(#iQBJ0Cb)"><path class="rzg6hdcga"/></g></g><defs><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="i48x0mi" cx="0" cy="0" r="1" gradientTransform="rotate(130.975 6.985 14.65)scale(10.3892 7.04816)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="h-969lbcv"/><stop offset=".708" class="z-xmlwmhd"/></radialGradient><radialGradient id="iAYOAEc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54683 -6.79689 16.41342 -3.73536 19.39 22.341)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="ccr58nbuz"/><stop offset=".299" class="gvfj_gdms"/><stop offset=".556" class="ovz69fb_x"/></radialGradient><radialGradient id="ihYVRac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62502 7.125 -9.31237 -3.4309 9.781 11.188)" gradientUnits="userSpaceOnUse"><stop class="vn4n3no1s"/><stop offset=".889" class="ixmaddcbc"/></radialGradient><radialGradient id="iZk2peJ" cx="0" cy="0" r="1" gradientTransform="rotate(-135.995 17.089 3.673)scale(13.3597 17.4611)" gradientUnits="userSpaceOnUse"><stop class="kb93-db6z"/><stop offset=".802" class="z-xmlwmhd"/></radialGradient><linearGradient id="ifSYanb" x1="10.578" x2="8" y1="17.482" y2="12.139" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iOZJFye" x1="8.86" x2="11.25" y1="13.889" y2="9.201" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="i8ICsPd" x1="21.406" x2="23.985" y1="17.482" y2="12.139" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="i38NwLb" x1="23.125" x2="20.734" y1="13.889" y2="9.201" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="id0HIkb" x1="15" x2="4.975" y1="20" y2="25.454" gradientUnits="userSpaceOnUse"><stop class="f9t5-qbbb"/><stop offset="1" class="lak8xzben"/></linearGradient><linearGradient id="izy9iVb" x1="5" x2="8" y1="21" y2="23.5" gradientUnits="userSpaceOnUse"><stop class="hcs63vbyr"/><stop offset="1" class="k63-r3bzc"/></linearGradient><filter id="ipOlTGc" width="19.969" height="5.473" x="4.794" y="18.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6807_5247" stdDeviation=".5"/></filter><filter id="iBDfR9c" width="7" height="6.996" x="7.5" y="10.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6807_5247" stdDeviation=".25"/></filter><filter id="i5lLomc" width="7" height="6.996" x="16.906" y="10.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6807_5247" stdDeviation=".25"/></filter><filter id="icIsatt" width="11.031" height="13.992" x="2.234" y="15.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6807_5247" stdDeviation=".5"/></filter><filter id="iQBJ0Cb" width="8.57" height="12.026" x="7.225" y="16.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6807_5247" stdDeviation="1"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sneezing-face" /></template>
<style>
.c_8_uccav {
  d: path("M22.537 10.856a1 1 0 1 1 .895 1.789l-2.207 1.103h-3.24a1 1 0 0 1 .552-.892z");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.e056lobrv {
  d: path("M14.439 16.01c-5.753.685-10.366 5.096-11.406 10.767c-.12.664.1 1.324.52 1.777c.66.605 1.69.595 2.331-.05a1.683 1.683 0 0 1 2.392-.005c.66.665 1.73.665 2.39 0s1.732-.695 2.392-.03c.61.715 1.661.685 2.332.05c.38-.393.61-.927.61-1.51V17.44c.01-.846-.72-1.53-1.561-1.43");
}

.e8j1wibpg {
  d: path("M21.959 17.078a1 1 0 0 0 .895-1.79l-2.207-1.103h-3.24a1 1 0 0 0 .552.893z");
}

.ewlno3sqc {
  d: path("M9.447 11.293a1 1 0 1 0-.894 1.79l2.206 1.102H14a1 1 0 0 0-.553-.892z");
}

.f9t5-qbbb {
  stop-color: var(--svg-color--fff5ff, #FFF5FF);
}

.fa5h9x75c {
  d: path("M4.31 28.81a1.7 1.7 0 0 1-.523-.326a2.1 2.1 0 0 1-.52-1.778c1.686-5.411 4.43-8.41 8.999-9.888z");
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h-969lbcv {
  stop-color: var(--svg-color--c97007, #C97007);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hcs63vbyr {
  stop-color: var(--svg-color--d5bacc, #D5BACC);
}

.ixmaddcbc {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
  stop-opacity: 0;
}

.j6b88sbai {
  fill-rule: evenodd;
  d: path("M12.104 22.07a.5.5 0 0 0-.522-.001l-.527.321l-.718.529l-.146.102a2.5 2.5 0 0 1-2.631.139l-.252-.138l-1.05-.665a1 1 0 0 1 1.07-1.69l.998.632l.196.108a.5.5 0 0 0 .526-.028l.124-.086l.767-.565l.603-.367a2.5 2.5 0 0 1 2.635.02l.042.027l1.13.807l.11.085a.5.5 0 0 0 .572.024l.211-.134l1.095-.782l.043-.027a2.5 2.5 0 0 1 2.635-.02l.602.367l.767.565l.124.086a.5.5 0 0 0 .526.028l.196-.108l.997-.632a1 1 0 1 1 1.07 1.69l-1.05.665l-.25.138a2.5 2.5 0 0 1-2.631-.14l-.147-.101l-.718-.529l-.527-.321a.5.5 0 0 0-.521 0l-1.092.78l-.256.163a2.5 2.5 0 0 1-2.86-.123l-.085-.065z");
}

.jfk2tlz6z {
  d: path("M9.447 16.64a1 1 0 1 1-.894-1.789l2.206-1.103H14a1 1 0 0 1-.553.892z");
}

.jjgocabki {
  d: path("M9.447 10.856a1 1 0 1 0-.894 1.789l2.206 1.103H14a1 1 0 0 0-.553-.892z");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k63-r3bzc {
  stop-color: var(--svg-color--f2d0ff, #F2D0FF);
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kb93-db6z {
  stop-color: var(--svg-color--e9830a, #E9830A);
}

.lak8xzben {
  stop-color: var(--svg-color--f6c2ff, #F6C2FF);
}

.ljb4srbfs {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mue744bew {
  d: path("M9.447 17.078a1 1 0 1 1-.894-1.79l2.206-1.103H14a1 1 0 0 1-.553.893z");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.rzg6hdcga {
  fill: var(--svg-color--d9b2fd, #D9B2FD);
  d: path("m11.923 26.165l-2.075.593a.48.48 0 0 1-.6-.6c.507-1.632 1.763-5.231 3.498-7.152c.498-.551 1.16-.138 1.032.594c-.32 1.827-.9 4.615-1.154 5.816a.99.99 0 0 1-.701.749");
}

.syggllbnk {
  d: path("M22.537 16.64a1 1 0 1 0 .895-1.789l-2.207-1.103h-3.24a1 1 0 0 0 .552.892z");
}

.vn4n3no1s {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xpgr2bbbu {
  d: path("M21.959 11.293a1 1 0 0 1 .895 1.79l-2.207 1.102h-3.24a1 1 0 0 1 .552-.892z");
}

.yk76sv2tk {
  d: path("m20.281 20.841l.593-.805l-.035-.026l-.037-.023zm-.565-.344l-.52.854zm1.443.985l.57-.82zm-.136-.094l-.593.805l.011.008l.011.008zm3.497.251a1 1 0 0 0-1.07-1.69zm-1.56-.196l.482.877l.028-.015l.026-.017zm-.223.123l-.481-.877zm-5.714-.264l.537.844l.023-.014l.022-.016zm1.112-.792l.534.845zm-.018.011l-.534-.846l-.024.016l-.023.016zm-6.398.32l-.52-.854l-.038.023l-.035.026zm.565-.344l.52.854zm-1.443.985l-.57-.82zm.136-.094l.57.821l.012-.008l.01-.008zM8.55 19.95a1 1 0 1 0-1.07 1.69zm.488 1.493l-.535.845l.026.017l.028.015zm.224.123l.481-.877zm5.714-.264l.607-.794l-.013-.01l-.013-.01zm-1.112-.792l-.534.845zm.018.011l.581-.814l-.023-.016l-.025-.016zm2.907.93l-.537-.844zm4.012-1.464l-.566-.344l-1.04 1.708l.565.344zm.928.674l-.136-.094l-1.142 1.642l.136.094zm-.113-.078l-.743-.547l-1.186 1.61l.742.547zm1.832-.633l-1.023.648l1.07 1.69l1.024-.649zm-.97.616l-.223.123l.962 1.753l.224-.122zm-5.992-.107l-.233.148l1.073 1.687l.233-.148zm1.115-.795l-.018.011l1.067 1.692l.018-.012zm-.066.043l-1.094.782l1.163 1.627l1.093-.781zm2.7-.064a2.5 2.5 0 0 0-2.634.021l1.067 1.691a.5.5 0 0 1 .527-.004zm.352 2.66a2.5 2.5 0 0 0 2.63.14l-.962-1.754a.5.5 0 0 1-.526-.028zm-8.349-.608l.565-.344l-1.04-1.708l-.566.344zm-.827.608l.136-.094l-1.142-1.642l-.136.094zm.158-.11l.742-.547l-1.186-1.61l-.743.547zm-4.09-.554l1.024.649l1.07-1.69l-1.023-.648zm1.078.68l.224.123l.962-1.753l-.224-.123zm5.811-.222l.097.074l1.215-1.589l-.097-.074zm-1.038-.742l.018.012l1.067-1.692l-.018-.011zm-.03-.02l1.094.781l1.163-1.627l-1.094-.782zm-.497.016a.5.5 0 0 1 .527.004l1.067-1.691a2.5 2.5 0 0 0-2.634-.02zm-2.534-.69a.5.5 0 0 1-.526.028l-.962 1.753a2.5 2.5 0 0 0 2.63-.139zm5.983-.054a.5.5 0 0 1-.572-.025l-1.215 1.59a2.5 2.5 0 0 0 2.861.122z");
}

.z-xmlwmhd {
  stop-color: var(--svg-color--f08b13, #F08B13);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
