<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHFHutr)"><circle fill="url(#iG5uDDd)" class="y6h4mvbgz"/></g><g filter="url(#ikXFZyY)"><circle fill="url(#i1lobGd)" class="jfk3ysbzo"/></g><g filter="url(#iZMhz8b)"><circle fill="url(#iH03dKb)" class="xamti8bbo"/><circle fill="url(#iwZsr4S)" class="xamti8bbo"/></g><g filter="url(#i8cVF0c)"><circle class="e9g0cq8lr"/><circle fill="url(#iRuAuIe)" class="rwz2nk4bz"/><circle fill="url(#iVkoELm)" class="rwz2nk4bz"/></g><g filter="url(#iOyviEe)"><path fill="url(#i4GQ8pe)" class="ced-wvd9h"/><path fill="url(#i3D2jMd)" class="ced-wvd9h"/><path fill="url(#ixbPWrd)" class="ced-wvd9h"/><path fill="url(#ivCZ0be)" class="ced-wvd9h"/><path fill="url(#itsErUu)" class="ced-wvd9h"/></g><g filter="url(#iZLorWd)"><path class="tc-pazb4x"/><path fill="url(#iRgNUZd)" class="hn7v3_r_d"/><path fill="url(#iqmOlkc)" class="hn7v3_r_d"/><path fill="url(#iUoXlyb)" class="hn7v3_r_d"/><path fill="url(#i9XAFzb)" class="hn7v3_r_d"/><path fill="url(#isw4cNe)" class="hn7v3_r_d"/></g><path fill="url(#iWolKFk)" class="hn7v3_r_d"/><path fill="url(#iHZs2Lc)" class="hn7v3_r_d"/><g filter="url(#i3yU9Od)"><path class="nss7y93xb"/></g><g filter="url(#i0as3ub)"><path class="n6rmfdbym"/><path fill="url(#ikKxSLd)" class="svl3smbra"/><path fill="url(#i3nrmzb)" class="svl3smbra"/><path fill="url(#iP0Kfed)" class="svl3smbra"/></g><path fill="url(#iszkkle)" class="svl3smbra"/><path stroke="url(#iyACPYd)" class="ygm6t7b6u"/><g filter="url(#iT0d4me)"><path class="v__0a5bgs"/></g><g filter="url(#ickNq3c)"><path class="g1badvthd"/></g><path class="s2axe1clu"/><path fill="url(#iHCkH0b)" class="amhd2acsm"/><path class="mmg9bcbxv"/><g filter="url(#ip8aRIe)"><path class="x11ft_07j"/><path fill="url(#idAmIWb)" class="glk_20k3g"/></g><g filter="url(#ivadf4b)"><path fill="url(#iVWNYHB)" class="n6naizbxd"/></g><path class="dn-3kccjq"/><path fill="url(#ieVl6dc)" class="aatijorde"/><path class="bq197y77p"/><g filter="url(#i3lqjPa)"><path fill="url(#iGu0AZc)" class="wjr8unmmj"/></g><g filter="url(#i1TX1cv)"><ellipse transform="rotate(-27.914 11.537 16.608)" class="o6qdzjmyx"/><ellipse fill="url(#ipW6Iee)" transform="rotate(-27.914 11.537 16.608)" class="r1m62ccor"/></g><g filter="url(#ikyIN1Y)"><path stroke="url(#iE35JUb)" class="zy4y66vli"/></g><g filter="url(#ilstXVd)"><path stroke="url(#iXfrx3d)" class="gl7lir6wx"/></g><defs><radialGradient id="iG5uDDd" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 4.149 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iwZsr4S" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.697 17.565)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iRuAuIe" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.926 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iVkoELm" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.455 39.43)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="i3D2jMd" cx="0" cy="0" r="1" gradientTransform="rotate(97.214 2.06 15.41)scale(15.9482 21.6489)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="daw21qbgk"/><stop offset="1" class="k64o5hods"/></radialGradient><radialGradient id="ivCZ0be" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.491 15.688)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="itsErUu" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.991 15.625)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iRgNUZd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.4087 8.25997 -14.04691 -10.89865 23.002 3.675)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iUoXlyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.12461 -3.47136 1.70486 -.0612 8.298 11.615)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i9XAFzb" cx="0" cy="0" r="1" gradientTransform="matrix(1.60216 -3.6672 2.99087 1.30668 24 14.818)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="isw4cNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.85139 2.29723 -2.0283 1.63465 14.67 2.019)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iWolKFk" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 7.436 11.962)scale(1.4992 2.4647)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iHZs2Lc" cx="0" cy="0" r="1" gradientTransform="matrix(1.35294 1.67337 -3.7494 3.03145 8.013 5.242)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iHCkH0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.18 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="idAmIWb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.026 3.634)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieVl6dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 12.043 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ipW6Iee" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.219 2.932)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iHFHutr" width="6.427" height="6.227" x="4.149" y="14.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19745"/></filter><filter id="ikXFZyY" width="4.711" height="4.711" x="4.907" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".25"/></filter><filter id="iZMhz8b" width="6.477" height="6.477" x="21.89" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19745"/></filter><filter id="i8cVF0c" width="4.711" height="4.711" x="22.648" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".25"/></filter><filter id="iOyviEe" width="19.345" height="22.68" x="6.497" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19745"/></filter><filter id="iZLorWd" width="23.5" height="15.5" x="4.366" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19745"/></filter><filter id="i3yU9Od" width="4.782" height="6.5" x="13.28" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".375"/></filter><filter id="i0as3ub" width="4" height="5.5" x="14.116" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".125"/></filter><filter id="iT0d4me" width="5.34" height="3.147" x="18.321" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19745"/></filter><filter id="ickNq3c" width="5.341" height="3.147" x="8.721" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19745"/></filter><filter id="ip8aRIe" width="1.294" height="1.125" x="18.897" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".05"/></filter><filter id="ivadf4b" width="1.316" height="1.357" x="20.55" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".1"/></filter><filter id="i3lqjPa" width="1.493" height="1.594" x="12.267" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".1"/></filter><filter id="i1TX1cv" width="1.529" height="1.141" x="10.773" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".05"/></filter><filter id="ikyIN1Y" width="4.949" height="2.304" x="18.463" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".25"/></filter><filter id="ilstXVd" width="5.094" height="2.41" x="8.73" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19745" stdDeviation=".25"/></filter><linearGradient id="i1lobGd" x1="7.262" x2="6.068" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iH03dKb" x1="27.029" x2="25.502" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i4GQ8pe" x1="23.643" x2="9.401" y1="18.785" y2="20.907" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ixbPWrd" x1="6.054" x2="10.366" y1="23.813" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iqmOlkc" x1="7.051" x2="12.463" y1="17.56" y2="7.947" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ikKxSLd" x1="14.505" x2="16.254" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="i3nrmzb" x1="17.866" x2="15.954" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iP0Kfed" x1="16.479" x2="16.479" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iszkkle" x1="16.351" x2="16.351" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iyACPYd" x1="14.182" x2="14.994" y1="25.012" y2="23.73" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iVWNYHB" x1="21.63" x2="21.045" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGu0AZc" x1="13.43" x2="12.845" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iE35JUb" x1="21.66" x2="20.876" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iXfrx3d" x1="11.767" x2="9.549" y1="12.659" y2="11.729" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-medium-light" /></template>
<style>
.aatijorde {
  d: path("M12.04 15.897A1.664 1.664 0 0 0 10.436 18h3.215a1.7 1.7 0 0 0 .06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.amhd2acsm {
  d: path("M20.184 15.897A1.664 1.664 0 0 1 21.787 18h-3.214a1.7 1.7 0 0 1-.061-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bq197y77p {
  fill: var(--svg-color--000, #000);
  d: path("M12.993 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.ced-wvd9h {
  d: path("M6.606 16.916q.045.003.091.003s-.1-1.591-.2-2.685c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L25.14 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.daw21qbgk {
  stop-color: var(--svg-color--b57195, #B57195);
  stop-opacity: 0;
}

.dn-3kccjq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.654 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e9g0cq8lr {
  cx: 25.003px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1badvthd {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m9.08 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05a4 4 0 0 1 .222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gl7lir6wx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.48 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.glk_20k3g {
  d: path("M20.061 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.hn7v3_r_d {
  d: path("m25.103 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89C11.599 2 13.2 1.703 14.6 2.399c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jfk3ysbzo {
  cx: 7.262px;
  cy: 18.059px;
  r: 1.855px;
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k64o5hods {
  stop-color: var(--svg-color--b57195, #B57195);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mmg9bcbxv {
  fill: var(--svg-color--000, #000);
  d: path("M19.23 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.105.439h-1.687a.86.86 0 0 1-.114-.439");
}

.n6naizbxd {
  d: path("M21.666 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.n6rmfdbym {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.404 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.nss7y93xb {
  fill: var(--svg-color--c68378, #C68378);
  d: path("M15.603 17.83L14.073 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.o6qdzjmyx {
  cx: 11.537px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r1m62ccor {
  cx: 11.537px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.rwz2nk4bz {
  cx: 25.003px;
  cy: 18.059px;
  r: 1.855px;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s2axe1clu {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.57 15.39c1.217 0 2.246.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.svl3smbra {
  d: path("m15.404 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.tc-pazb4x {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m25.103 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89C11.599 2 13.2 1.703 14.6 2.399c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v__0a5bgs {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m23.053 12.986l-.003-.002l-.003-.002l-.008-.007l-.023-.018a3 3 0 0 0-.288-.2a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a3 3 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wjr8unmmj {
  d: path("M13.56 17.366c0-.538-.437-.896-.556-1.005l-.537.52l.33.674z");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x11ft_07j {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.061 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.xamti8bbo {
  cx: 25.003px;
  cy: 18.059px;
  r: 3.113px;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y6h4mvbgz {
  cx: 7.262px;
  cy: 18.059px;
  r: 3.113px;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ygm6t7b6u {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.557 23.239h-.001a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zy4y66vli {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.213 12.717c.802-.14 2.366-.1 3.449.742");
}

</style>
