<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ijqmH1d)" class="wt52r_bmz"/><path fill="url(#i9advMF)" class="wt52r_bmz"/><path fill="url(#iAgX7Qb)" class="wt52r_bmz"/><path fill="url(#i3tg16T)" class="wt52r_bmz"/><path fill="url(#ifnrQ1c)" class="wt52r_bmz"/><path fill="url(#iGT5aAe)" class="wt52r_bmz"/><path fill="url(#ibKpMbc)" class="wt52r_bmz"/><path fill="url(#ikAyoob)" class="x6p5sebzf"/><path fill="url(#idv2IJs)" class="x6p5sebzf"/><path fill="url(#iUTetjb)" class="tocspwx1s"/><path fill="url(#ixyR8ec)" class="tocspwx1s"/><path fill="url(#imgtTQb)" class="tocspwx1s"/><path fill="url(#if1GHkb)" class="tocspwx1s"/><g filter="url(#ip5lWvd)"><rect fill="url(#i2hIDhl)" transform="rotate(-17.17 16 7.064)" class="agf94fbmx"/></g><g filter="url(#ioyTDGc)"><rect fill="url(#iZ9N8xd)" transform="rotate(13.82 13.543 6.924)" class="l7d7u3bpk"/></g><g filter="url(#iKSHzkb)"><path class="n10hx0b7o"/><path fill="url(#i64T1Dd)" class="wpn_jx_4s"/><path fill="url(#iIkwBKc)" class="wpn_jx_4s"/><path fill="url(#iXJf7db)" class="wpn_jx_4s"/></g><g filter="url(#iSTZUYd)"><path class="eh8mpaclw"/><path fill="url(#iEHqvpJ)" class="xh5qa-bwo"/><path fill="url(#iIvcNvd)" class="xh5qa-bwo"/></g><path fill="url(#iJ14VFf)" class="xh5qa-bwo"/><g filter="url(#irGkaDc)"><path fill="url(#i9EaIXd)" class="oi5a2ubxf"/></g><g filter="url(#ivU9JHc)"><path fill="url(#i7TcMRA)" class="fp_a3ug4z"/></g><path class="b8j9igbvn"/><path fill="url(#idKZB4c)" class="o8hwk11sf"/><path fill="url(#iqsR8Fe)" class="o8hwk11sf"/><path fill="url(#irwupMe)" class="o8hwk11sf"/><path fill="url(#i7hf20d)" class="o8hwk11sf"/><g filter="url(#ikQGvNd)"><path class="k6hxo8pht"/></g><g filter="url(#iWTi0KZ)"><path class="a6hlfoxbe"/></g><g filter="url(#ivUA53c)"><rect transform="rotate(-14.458 16.81 6.983)" class="ftk7hebix"/></g><g filter="url(#icSuD6d)"><rect fill="url(#iAqbNed)" transform="scale(-1 1)rotate(-14.458 20.045 62.468)" class="i3zku83pp"/></g><defs><linearGradient id="ijqmH1d" x1="15.894" x2="15.894" y1="6.971" y2="22.31" gradientUnits="userSpaceOnUse"><stop offset=".267" class="x8cucmbby"/><stop offset="1" class="ts8t-6p_x"/></linearGradient><linearGradient id="i9advMF" x1="2.277" x2="4.683" y1="22.063" y2="22.438" gradientUnits="userSpaceOnUse"><stop class="r_1-e4_9d"/><stop offset="1" class="xyekjburr"/></linearGradient><linearGradient id="idv2IJs" x1="3.706" x2="5.508" y1="11.882" y2="12.106" gradientUnits="userSpaceOnUse"><stop offset=".251" class="o_lqwv_cr"/><stop offset="1" class="f_vo7zbxi"/></linearGradient><linearGradient id="ixyR8ec" x1="28.077" x2="26.275" y1="11.882" y2="12.106" gradientUnits="userSpaceOnUse"><stop offset=".251" class="o_lqwv_cr"/><stop offset="1" class="f_vo7zbxi"/></linearGradient><linearGradient id="imgtTQb" x1="25.621" x2="27.667" y1="8.621" y2="13.449" gradientUnits="userSpaceOnUse"><stop class="x1ugf8bsk"/><stop offset=".827" class="u40k6fbjn"/></linearGradient><linearGradient id="if1GHkb" x1="27.963" x2="27.349" y1="12.484" y2="12.556" gradientUnits="userSpaceOnUse"><stop class="tn0x7fbsj"/><stop offset="1" class="kcxxjnb0n"/></linearGradient><linearGradient id="i2hIDhl" x1="16.479" x2="16.517" y1="8.78" y2="15.989" gradientUnits="userSpaceOnUse"><stop class="p--e9988d"/><stop offset="0" class="ejbotuz6b"/><stop offset="1" class="gnxe5e-tm"/></linearGradient><linearGradient id="iZ9N8xd" x1="14.022" x2="14.06" y1="8.641" y2="15.849" gradientUnits="userSpaceOnUse"><stop class="h6s-tv9gr"/><stop offset="0" class="ejbotuz6b"/><stop offset="1" class="gnxe5e-tm"/><stop offset="1" class="ud7rikb0j"/></linearGradient><linearGradient id="iIkwBKc" x1="24.062" x2="24.134" y1="25.578" y2="26.083" gradientUnits="userSpaceOnUse"><stop class="s69aonblz"/><stop offset="1" class="jom8cgb_q"/></linearGradient><linearGradient id="iJ14VFf" x1="8.152" x2="8.058" y1="25.719" y2="26.203" gradientUnits="userSpaceOnUse"><stop offset=".259" class="w5fs5xwbq"/><stop offset="1" class="sroc2tsyw"/></linearGradient><linearGradient id="i7TcMRA" x1="8.029" x2="3.876" y1="8.719" y2="15.956" gradientUnits="userSpaceOnUse"><stop offset=".153" class="od6qu9bzp"/><stop offset="1" class="mklb-9bdv"/></linearGradient><linearGradient id="idKZB4c" x1="27.457" x2="21.402" y1="8.813" y2="9.813" gradientUnits="userSpaceOnUse"><stop offset=".198" class="avouqibcv"/><stop offset="1" class="sz83e0njq"/></linearGradient><linearGradient id="iqsR8Fe" x1="16.558" x2="16.558" y1="8.891" y2="8.336" gradientUnits="userSpaceOnUse"><stop offset=".085" class="c93a-q36s"/><stop offset="1" class="yimh8zesr"/></linearGradient><linearGradient id="irwupMe" x1="15.88" x2="15.88" y1="4.719" y2="5.188" gradientUnits="userSpaceOnUse"><stop class="gftrc2_-x"/><stop offset="1" class="utdlu2hgu"/></linearGradient><linearGradient id="i7hf20d" x1="3.933" x2="8.496" y1="8.031" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="h1hd_r2dd"/><stop offset="1" class="vto9idfjm"/></linearGradient><linearGradient id="iAqbNed" x1=".517" x2=".635" y1="0" y2="8.337" gradientUnits="userSpaceOnUse"><stop class="pmg10qb6b"/><stop offset="1" class="essrf_btt"/></linearGradient><radialGradient id="iAgX7Qb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -5.5625 4.56017 2.10075 16.808 20.125)" gradientUnits="userSpaceOnUse"><stop class="h-jpkd7xu"/><stop offset="1" class="kp5g0sbrs"/></radialGradient><radialGradient id="i3tg16T" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -15.25 6.73302 .66227 17.496 28.438)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="ge4r7aclr"/><stop offset="1" class="raip0giyt"/></radialGradient><radialGradient id="ifnrQ1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.125 2.3517 0 15.894 19.688)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="yl0aymb9x"/><stop offset="1" class="y1yh92bai"/></radialGradient><radialGradient id="iGT5aAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -9.2325 3.2322 .5689 11.87 27.438)" gradientUnits="userSpaceOnUse"><stop class="vx8pws82f"/><stop offset="1" class="bbiz4l6mj"/></radialGradient><radialGradient id="ibKpMbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 -9.375 4.51388 -.69212 29.746 24.938)" gradientUnits="userSpaceOnUse"><stop class="nucoaacqp"/><stop offset="1" class="zylvi8kka"/></radialGradient><radialGradient id="ikAyoob" cx="0" cy="0" r="1" gradientTransform="rotate(135 .537 7.127)scale(2.8942 1.77185)" gradientUnits="userSpaceOnUse"><stop class="ny39_1bln"/><stop offset="1" class="hk_8uvb2x"/></radialGradient><radialGradient id="iUTetjb" cx="0" cy="0" r="1" gradientTransform="rotate(45 -1.314 37.07)scale(2.8942 1.77185)" gradientUnits="userSpaceOnUse"><stop class="ny39_1bln"/><stop offset="1" class="hk_8uvb2x"/></radialGradient><radialGradient id="i64T1Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.338 4.05915 -1.86508 -.1553 29.746 24.878)" gradientUnits="userSpaceOnUse"><stop class="irmlwfbci"/><stop offset="1" class="m14fg2a1l"/></radialGradient><radialGradient id="iXJf7db" cx="0" cy="0" r="1" gradientTransform="matrix(-6.2126 5.50398 -7.68594 -8.67547 27.169 24.878)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="timlb4b1i"/><stop offset="1" class="tw_n8tazt"/></radialGradient><radialGradient id="iEHqvpJ" cx="0" cy="0" r="1" gradientTransform="matrix(-8.99386 1.87826 -2.1556 -10.32192 11.492 25.794)" gradientUnits="userSpaceOnUse"><stop offset=".746" class="ecwcbs_qb"/><stop offset="1" class="pg9hcibuj"/></radialGradient><radialGradient id="iIvcNvd" cx="0" cy="0" r="1" gradientTransform="rotate(141.263 1.472 16.084)scale(4.21382 4.31537)" gradientUnits="userSpaceOnUse"><stop class="cveoxe77r"/><stop offset="1" class="qsuejirgi"/></radialGradient><radialGradient id="i9EaIXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 -1.25 5.19017 8.56378 24.527 12.25)" gradientUnits="userSpaceOnUse"><stop class="jkj6tdb7g"/><stop offset="1" class="of7ro9b7w"/></radialGradient><filter id="ip5lWvd" width="4.364" height="9.573" x="15.629" y="6.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16988" stdDeviation=".25"/></filter><filter id="ioyTDGc" width="3.519" height="9.296" x="11.219" y="6.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16988" stdDeviation=".15"/></filter><filter id="iKSHzkb" width="10.976" height="4.775" x="18.77" y="24.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.486275 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16988"/></filter><filter id="iSTZUYd" width="11.076" height="4.775" x="1.948" y="24.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.478431 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16988"/></filter><filter id="irGkaDc" width="4.865" height="6.311" x="23.519" y="8.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.65098 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16988"/></filter><filter id="ivU9JHc" width="4.965" height="6.211" x="3.388" y="8.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.576471 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16988"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.878431 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_16988" result="effect2_innerShadow_18_16988"/></filter><filter id="ikQGvNd" width="1.713" height="2.393" x="16.519" y="6.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16988" stdDeviation=".125"/></filter><filter id="iWTi0KZ" width="2.028" height="2.406" x="12.874" y="6.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16988" stdDeviation=".125"/></filter><filter id="ivUA53c" width="3.304" height="8.975" x="16.923" y="6.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.596078 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16988"/></filter><filter id="icSuD6d" width="3.304" height="8.975" x="11.845" y="6.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.564706 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16988"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shorts" /></template>
<style>
.a6hlfoxbe {
  fill: var(--svg-color--3e8e84, #3E8E84);
  d: path("M14.136 6.922c-.276.071-.414.305-.523.625l-.489 1.265h1.068l.46-1.504c-.071-.277-.24-.457-.516-.386");
}

.agf94fbmx {
  width: 1.034px;
  height: 8.925px;
  x: 16px;
  y: 7.064px;
  rx: 0.517px;
}

.avouqibcv {
  stop-color: var(--svg-color--6affa5, #6AFFA5);
}

.b8j9igbvn {
  fill: var(--svg-color--4be596, #4BE596);
  d: path("M4.67 6.198a1.75 1.75 0 0 1 1.73-1.48h18.988c.87 0 1.607.64 1.732 1.5l.334 2.309a.25.25 0 0 1-.247.286H4.554a.25.25 0 0 1-.247-.29z");
}

.bbiz4l6mj {
  stop-color: var(--svg-color--4afd94, #4AFD94);
  stop-opacity: 0;
}

.c93a-q36s {
  stop-color: var(--svg-color--47a591, #47A591);
}

.cveoxe77r {
  stop-color: var(--svg-color--32d079, #32D079);
}

.ecwcbs_qb {
  stop-color: var(--svg-color--29a25e, #29A25E);
  stop-opacity: 0;
}

.eh8mpaclw {
  fill: var(--svg-color--3eb085, #3EB085);
  d: path("M2.04 24.979a.1.1 0 0 1 .115-.085L12.84 26.64a.1.1 0 0 1 .083.117l-.12.648a2.53 2.53 0 0 1-2.879 2.032l-5.619-.876a2.786 2.786 0 0 1-2.328-3.15z");
}

.ejbotuz6b {
  stop-color: var(--svg-color--8c9a49, #8C9A49);
}

.essrf_btt {
  stop-color: var(--svg-color--e5c5ff, #E5C5FF);
}

.f_vo7zbxi {
  stop-color: var(--svg-color--9ec953, #9EC953);
  stop-opacity: 0;
}

.fp_a3ug4z {
  d: path("M7.16 11.969c.775-1.114 1.057-2.594 1.093-3.25h-1c0 .46-.198 1.662-.992 2.781c-.992 1.398-2.25 1.797-2.586 2.36c-.268.45-.19.9-.117 1.07c.008-.078.102-.22.453-.399l.016-.008c.738-.376 2.1-1.072 3.133-2.554");
}

.ft5dv1b6b {
  fill: none;
}

.ftk7hebix {
  width: 1.034px;
  height: 8.925px;
  x: 16.81px;
  y: 6.983px;
  fill: var(--svg-color--fff5ff, #FFF5FF);
  rx: 0.517px;
}

.ge4r7aclr {
  stop-color: var(--svg-color--36ac71, #36AC71);
}

.gftrc2_-x {
  stop-color: var(--svg-color--4cef90, #4CEF90);
}

.gnxe5e-tm {
  stop-color: var(--svg-color--789b71, #789B71);
}

.h-jpkd7xu {
  stop-color: var(--svg-color--7bca87, #7BCA87);
}

.h1hd_r2dd {
  stop-color: var(--svg-color--39bb77, #39BB77);
}

.h6s-tv9gr {
  stop-color: var(--svg-color--77923b, #77923B);
}

.hk_8uvb2x {
  stop-color: var(--svg-color--b0d350, #B0D350);
}

.i3zku83pp {
  width: 1.034px;
  height: 8.925px;
  rx: 0.517px;
}

.irmlwfbci {
  stop-color: var(--svg-color--4bdf7d, #4BDF7D);
}

.jkj6tdb7g {
  stop-color: var(--svg-color--4bca8b, #4BCA8B);
}

.jom8cgb_q {
  stop-color: var(--svg-color--51d680, #51D680);
  stop-opacity: 0;
}

.k6hxo8pht {
  fill: var(--svg-color--3e8e84, #3E8E84);
  d: path("M17.157 6.936a.517.517 0 0 0-.372.63l.13 1.246h1.067l-.196-1.504a.517.517 0 0 0-.63-.372");
}

.kcxxjnb0n {
  stop-color: var(--svg-color--adfe6e, #ADFE6E);
  stop-opacity: 0;
}

.kp5g0sbrs {
  stop-color: var(--svg-color--7bca87, #7BCA87);
  stop-opacity: 0;
}

.l7d7u3bpk {
  width: 1.034px;
  height: 8.925px;
  x: 13.543px;
  y: 6.924px;
  rx: 0.517px;
}

.m14fg2a1l {
  stop-color: var(--svg-color--37be7d, #37BE7D);
  stop-opacity: 0;
}

.mklb-9bdv {
  stop-color: var(--svg-color--309761, #309761);
}

.n10hx0b7o {
  fill: var(--svg-color--3daa85, #3DAA85);
  d: path("M29.655 24.979a.1.1 0 0 0-.115-.085L18.854 26.64a.1.1 0 0 0-.082.117l.12.648a2.53 2.53 0 0 0 2.878 2.032l5.619-.876a2.786 2.786 0 0 0 2.328-3.15z");
}

.nucoaacqp {
  stop-color: var(--svg-color--62ff95, #62FF95);
}

.ny39_1bln {
  stop-color: var(--svg-color--9fd057, #9FD057);
}

.o_lqwv_cr {
  stop-color: var(--svg-color--86ad4e, #86AD4E);
}

.o8hwk11sf {
  d: path("M4.67 6.198a1.75 1.75 0 0 1 1.73-1.48h18.988c.87 0 1.607.64 1.732 1.5l.334 2.309a.25.25 0 0 1-.247.286H4.554a.25.25 0 0 1-.247-.29z");
}

.od6qu9bzp {
  stop-color: var(--svg-color--39ce83, #39CE83);
}

.of7ro9b7w {
  stop-color: var(--svg-color--67f59f, #67F59F);
}

.oi5a2ubxf {
  d: path("M24.613 11.969c-.775-1.114-1.057-2.594-1.094-3.25h1c0 .46.199 1.662.993 2.781c.992 1.398 2.25 1.797 2.585 2.36c.27.45.19.9.118 1.07c-.008-.078-.102-.22-.453-.399l-.016-.008c-.738-.376-2.101-1.072-3.133-2.554");
}

.p--e9988d {
  stop-color: var(--svg-color--839255, #839255);
}

.pg9hcibuj {
  stop-color: var(--svg-color--29a25e, #29A25E);
}

.pmg10qb6b {
  stop-color: var(--svg-color--fffaff, #FFFAFF);
}

.qsuejirgi {
  stop-color: var(--svg-color--32d079, #32D079);
  stop-opacity: 0;
}

.r_1-e4_9d {
  stop-color: var(--svg-color--4aae62, #4AAE62);
}

.raip0giyt {
  stop-color: var(--svg-color--5dd380, #5DD380);
  stop-opacity: 0;
}

.s69aonblz {
  stop-color: var(--svg-color--51d680, #51D680);
}

.sroc2tsyw {
  stop-color: var(--svg-color--43cd7d, #43CD7D);
  stop-opacity: 0;
}

.sz83e0njq {
  stop-color: var(--svg-color--6affa5, #6AFFA5);
  stop-opacity: 0;
}

.timlb4b1i {
  stop-color: var(--svg-color--3d8c6e, #3D8C6E);
  stop-opacity: 0;
}

.tn0x7fbsj {
  stop-color: var(--svg-color--adfe6e, #ADFE6E);
}

.tocspwx1s {
  d: path("m27.106 7.349l.97 6.736c-3.585-1.816-4.256-4.782-4.103-6.168z");
}

.ts8t-6p_x {
  stop-color: var(--svg-color--47e494, #47E494);
}

.tw_n8tazt {
  stop-color: var(--svg-color--3d8c6e, #3D8C6E);
}

.u40k6fbjn {
  stop-color: var(--svg-color--b8ff7c, #B8FF7C);
}

.ud7rikb0j {
  stop-color: var(--svg-color--638c55, #638C55);
}

.utdlu2hgu {
  stop-color: var(--svg-color--4cef90, #4CEF90);
  stop-opacity: 0;
}

.vto9idfjm {
  stop-color: var(--svg-color--39bb77, #39BB77);
  stop-opacity: 0;
}

.vx8pws82f {
  stop-color: var(--svg-color--4afd94, #4AFD94);
}

.w5fs5xwbq {
  stop-color: var(--svg-color--43cd7d, #43CD7D);
}

.wpn_jx_4s {
  d: path("M29.655 24.979a.1.1 0 0 0-.115-.085L18.854 26.64a.1.1 0 0 0-.082.117l.12.648a2.53 2.53 0 0 0 2.878 2.032l5.619-.876a2.786 2.786 0 0 0 2.328-3.15z");
}

.wt52r_bmz {
  d: path("M4.73 6.972L2.07 25.434a2.75 2.75 0 0 0 2.3 3.11l5.546.864a2.5 2.5 0 0 0 2.842-2.006l1.307-7.065a1.5 1.5 0 0 1 1.475-1.228h.708a1.5 1.5 0 0 1 1.475 1.227l1.308 7.066a2.5 2.5 0 0 0 2.841 2.006l5.547-.864a2.75 2.75 0 0 0 2.298-3.11L27.058 6.971z");
}

.x1ugf8bsk {
  stop-color: var(--svg-color--d7ff77, #D7FF77);
}

.x6p5sebzf {
  d: path("m4.676 7.349l-.97 6.736c3.586-1.816 4.257-4.782 4.104-6.168z");
}

.x8cucmbby {
  stop-color: var(--svg-color--c0ef5f, #C0EF5F);
}

.xh5qa-bwo {
  d: path("M2.04 24.979a.1.1 0 0 1 .115-.085L12.84 26.64a.1.1 0 0 1 .083.117l-.12.648a2.53 2.53 0 0 1-2.879 2.032l-5.619-.876a2.786 2.786 0 0 1-2.328-3.15z");
}

.xyekjburr {
  stop-color: var(--svg-color--4ad277, #4AD277);
  stop-opacity: 0;
}

.y1yh92bai {
  stop-color: var(--svg-color--7fce8c, #7FCE8C);
  stop-opacity: 0;
}

.yimh8zesr {
  stop-color: var(--svg-color--41cd85, #41CD85);
  stop-opacity: 0;
}

.yl0aymb9x {
  stop-color: var(--svg-color--6c9492, #6C9492);
}

.zylvi8kka {
  stop-color: var(--svg-color--4de795, #4DE795);
  stop-opacity: 0;
}

</style>
