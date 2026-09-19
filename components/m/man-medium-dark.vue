<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOCt5mb)"><circle fill="url(#iAEg9ob)" class="cj7ahub2p"/></g><g filter="url(#i2f5D7b)"><circle fill="url(#i8tgPLd)" class="psfiufb7k"/></g><g filter="url(#i8IAnXc)"><circle fill="url(#i1AeCld)" class="olsf4bx_z"/><circle fill="url(#ik7v5we)" class="olsf4bx_z"/></g><g filter="url(#iCkLnqb)"><circle class="cx50jcc-u"/><circle fill="url(#iOlYQ7K)" class="l7y-dwknf"/><circle fill="url(#i47RSqe)" class="l7y-dwknf"/></g><g filter="url(#iRAnKld)"><path fill="url(#iQXxYhd)" class="at7monu3o"/><path fill="url(#itAc8WL)" class="at7monu3o"/><path fill="url(#i9cj3Wd)" class="at7monu3o"/></g><path fill="url(#iS8H2gd)" class="fmj33gy1k"/><path fill="url(#iQbWmpb)" class="fmj33gy1k"/><path fill="url(#iVwuVJd)" class="fmj33gy1k"/><path fill="url(#itiizwO)" class="fmj33gy1k"/><g filter="url(#i4m54HL)"><path fill="url(#iLFXfMc)" class="etr6pvbbx"/></g><g filter="url(#ibzQMvd)"><path class="i90eok_4v"/><path fill="url(#izuIjIc)" class="v3slk_heg"/><path fill="url(#ioXbObb)" class="v3slk_heg"/><path fill="url(#iiJveVd)" class="v3slk_heg"/><path fill="url(#irl1smb)" class="v3slk_heg"/></g><g filter="url(#ik24Nvd)"><path class="xkwaqpbfb"/></g><g filter="url(#iHJoMxd)"><path class="t44akddzt"/><path fill="url(#icTRWRH)" class="wli80fbal"/><path fill="url(#iqVutTc)" class="wli80fbal"/><path fill="url(#inhYAyd)" class="wli80fbal"/><path fill="url(#i4kQsIe)" class="wli80fbal"/></g><path fill="url(#izOrPCb)" class="wli80fbal"/><path stroke="url(#iKYMQoc)" class="b6l3e16gh"/><g filter="url(#iyZVaUb)"><path class="fdnn3zoeu"/><path fill="url(#iS4pSBc)" class="p08f6nb3i"/></g><g filter="url(#i3Kxl3b)"><path class="aqzugqgth"/><path fill="url(#i9CvgOb)" class="e0u8tvbdi"/></g><path class="orr0vaccf"/><path fill="url(#iIwbPoe)" class="vyw9w5b4x"/><path class="ij_z9_q3v"/><g filter="url(#iodj4Vc)"><path class="be2pnobcs"/><path fill="url(#i1DPErc)" class="jkv6m2m9c"/></g><g filter="url(#i8ocHse)"><path fill="url(#i0jeMov)" class="sywro0-ye"/></g><path class="xgcjlyb0i"/><path fill="url(#imLApCb)" class="w-1m21bpm"/><path class="q4j36-b7k"/><g filter="url(#i18XqEe)"><path fill="url(#iaflJKd)" class="xcsjg_b6r"/></g><g filter="url(#iEpIZQS)"><ellipse transform="rotate(-27.914 11.537 16.44)" class="qqxfifb6m"/><ellipse fill="url(#ibW9YBd)" transform="rotate(-27.914 11.537 16.44)" class="d1sx36jis"/></g><g filter="url(#iZytMre)"><path stroke="url(#iiZ1vAe)" class="muabmkb6n"/></g><g filter="url(#iy0D63Y)"><path stroke="url(#ivVu7oc)" class="xjd87i60r"/></g><g filter="url(#iCcqsNe)"><path stroke="url(#iGhj7Yc)" class="co59-cb9f"/></g><defs><radialGradient id="iAEg9ob" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 4.149 17.89)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="ik7v5we" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.697 17.396)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iOlYQ7K" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.926 19.421)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="i47RSqe" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.25 39.345)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="itAc8WL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.491 15.518)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="i9cj3Wd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 3.1867 0 11.991 15.768)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iVwuVJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.25 -20.7011 0 15.554 14.581)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="expufxtqh"/><stop offset="1" class="cpvcnac5k"/></radialGradient><radialGradient id="izuIjIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4878 -5.51363 2.04463 .55172 24.22 10.233)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="ioXbObb" cx="0" cy="0" r="1" gradientTransform="matrix(7.13272 .6564 -.35295 3.83521 21.157 6.95)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iiJveVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.1314 -4.84965 0 16.116 1.85)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="irl1smb" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.302 1.031)scale(7.1069 11.1342)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="i4kQsIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.727 20.886)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iS4pSBc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 18.65 -5.273)scale(1.14166 3.3775)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i9CvgOb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.85 .427)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iIwbPoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.18 16.618)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1DPErc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.985 3.55)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imLApCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 12.043 16.618)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibW9YBd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.136 2.848)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iOCt5mb" width="6.427" height="6.227" x="4.149" y="14.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19710"/></filter><filter id="i2f5D7b" width="4.711" height="4.711" x="4.907" y="15.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".25"/></filter><filter id="i8IAnXc" width="6.477" height="6.477" x="21.89" y="14.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19710"/></filter><filter id="iCkLnqb" width="4.711" height="4.711" x="22.648" y="15.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".25"/></filter><filter id="iRAnKld" width="19.345" height="22.68" x="6.497" y="7.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19710"/></filter><filter id="i4m54HL" width="11.918" height="9.719" x="14.433" y="5.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation="1"/></filter><filter id="ibzQMvd" width="23.5" height="15.5" x="4.366" y="1.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19710"/></filter><filter id="ik24Nvd" width="4.782" height="6.5" x="13.28" y="16.385" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".375"/></filter><filter id="iHJoMxd" width="4" height="5.5" x="14.116" y="16.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".125"/></filter><filter id="iyZVaUb" width="5.34" height="3.147" x="18.321" y="11.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19710"/></filter><filter id="i3Kxl3b" width="5.341" height="3.147" x="8.721" y="11.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19710"/></filter><filter id="iodj4Vc" width="1.294" height="1.125" x="18.897" y="15.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".05"/></filter><filter id="i8ocHse" width="1.316" height="1.357" x="20.55" y="16.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".1"/></filter><filter id="i18XqEe" width="1.493" height="1.594" x="12.267" y="15.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".1"/></filter><filter id="iEpIZQS" width="1.529" height="1.141" x="10.773" y="15.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".05"/></filter><filter id="iZytMre" width="4.949" height="2.304" x="18.463" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".25"/></filter><filter id="iy0D63Y" width="5.094" height="2.41" x="8.73" y="11.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".25"/></filter><filter id="iCcqsNe" width="1.231" height="3.583" x="6.807" y="8.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19710" stdDeviation=".125"/></filter><linearGradient id="i8tgPLd" x1="7.262" x2="6.068" y1="18.409" y2="18.409" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="i1AeCld" x1="27.029" x2="25.502" y1="15.854" y2="20.584" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iQXxYhd" x1="23.643" x2="9.401" y1="18.616" y2="20.738" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iS8H2gd" x1="6.054" x2="9.563" y1="23.643" y2="23.518" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iQbWmpb" x1="25.188" x2="23.219" y1="22.081" y2="21.893" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="itiizwO" x1="16.17" x2="16.17" y1="28.114" y2="30.071" gradientUnits="userSpaceOnUse"><stop offset=".533" class="m8c2yi15h"/><stop offset="1" class="vbfhreb6b"/></linearGradient><linearGradient id="iLFXfMc" x1="15.125" x2="30.313" y1="13.05" y2="7.612" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="icTRWRH" x1="14.505" x2="16.254" y1="19.845" y2="19.845" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iqVutTc" x1="17.866" x2="15.954" y1="20.447" y2="20.419" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="inhYAyd" x1="16.479" x2="16.479" y1="21.831" y2="20.762" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="izOrPCb" x1="16.351" x2="16.351" y1="21.909" y2="21.597" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iKYMQoc" x1="14.182" x2="14.994" y1="24.843" y2="23.561" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i0jeMov" x1="21.63" x2="21.045" y1="16.718" y2="17.079" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaflJKd" x1="13.43" x2="12.845" y1="16.718" y2="17.079" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iiZ1vAe" x1="21.66" x2="20.876" y1="12.728" y2="11.127" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ivVu7oc" x1="11.767" x2="9.549" y1="12.49" y2="11.56" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iGhj7Yc" x1="7.423" x2="7.423" y1="8.733" y2="12.756" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-medium-dark" /></template>
<style>
.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.aqzugqgth {
  fill: var(--svg-color--352827, #352827);
  d: path("m9.08 12.818l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.062.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 0 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a2.8 2.8 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.at7monu3o {
  d: path("M6.606 16.747q.045.003.091.003s-.1-1.591-.2-2.685c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.19c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034l-.496 7.382c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.b6l3e16gh {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.557 23.07h-.001a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.608c-.938 0-1.82-.221-2.56-.607Z");
}

.be2pnobcs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.061 16.08c.119.159-.13.352-.41.563c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cj7ahub2p {
  cx: 7.262px;
  cy: 17.89px;
  r: 3.113px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co59-cb9f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.663 8.917v1.674c-.014.277-.131.897-.481 1.16");
}

.cpvcnac5k {
  stop-color: var(--svg-color--7d4371, #7D4371);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cx50jcc-u {
  cx: 25.003px;
  cy: 17.89px;
  r: 1.855px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d1sx36jis {
  cx: 11.537px;
  cy: 16.439px;
  rx: 0.726px;
  ry: 0.368px;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0u8tvbdi {
  d: path("m9.08 12.818l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.062.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 0 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a2.8 2.8 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.etr6pvbbx {
  d: path("m23.508 7.4l-5.74 1.914a1.953 1.953 0 0 0 .878 3.788l5.706-.764z");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.expufxtqh {
  stop-color: var(--svg-color--7d4371, #7D4371);
  stop-opacity: 0;
}

.fdnn3zoeu {
  fill: var(--svg-color--352827, #352827);
  d: path("m23.053 12.817l-.003-.002l-.003-.002l-.008-.007l-.023-.018a3 3 0 0 0-.288-.2a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.fmj33gy1k {
  d: path("M6.497 14.065c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.19c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034l-.496 7.382c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.387-.373-6.785-.683-10.166");
}

.ft5dv1b6b {
  fill: none;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.i90eok_4v {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m25.103 5.81l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.807-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.19c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.094l1.8-1.89c1.1-.995 2.701-1.293 4.102-.597c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.492c.4.497.9.795 1.5 1.094");
}

.ij_z9_q3v {
  fill: var(--svg-color--000, #000);
  d: path("M19.23 17.392c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.105.439h-1.687a.86.86 0 0 1-.114-.439");
}

.jkv6m2m9c {
  d: path("M20.061 16.08c.119.159-.13.352-.41.563c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7y-dwknf {
  cx: 25.003px;
  cy: 17.89px;
  r: 1.855px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m8c2yi15h {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.muabmkb6n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.213 12.548c.802-.14 2.366-.1 3.449.742");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olsf4bx_z {
  cx: 25.003px;
  cy: 17.89px;
  r: 3.113px;
}

.orr0vaccf {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.57 15.222c1.217 0 2.246.84 2.525 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.p08f6nb3i {
  d: path("m23.053 12.817l-.003-.002l-.003-.002l-.008-.007l-.023-.018a3 3 0 0 0-.288-.2a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.psfiufb7k {
  cx: 7.262px;
  cy: 17.89px;
  r: 1.855px;
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q4j36-b7k {
  fill: var(--svg-color--000, #000);
  d: path("M12.993 17.392a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.94.94 0 0 0 .114-.439");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qqxfifb6m {
  cx: 11.537px;
  cy: 16.439px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sywro0-ye {
  d: path("M21.666 17.173a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.t44akddzt {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.404 17.358l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.v3slk_heg {
  d: path("m25.103 5.81l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.807-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.19c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.094l1.8-1.89c1.1-.995 2.701-1.293 4.102-.597c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.492c.4.497.9.795 1.5 1.094");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vbfhreb6b {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vyw9w5b4x {
  d: path("M20.184 15.729a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.061-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.w-1m21bpm {
  d: path("M12.04 15.728a1.664 1.664 0 0 0-1.604 2.103h3.215a1.7 1.7 0 0 0 .06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wli80fbal {
  d: path("m15.404 17.358l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.xcsjg_b6r {
  d: path("M13.56 17.197c0-.538-.437-.896-.556-1.005l-.537.52l.33.674z");
}

.xgcjlyb0i {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.654 15.222c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xjd87i60r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.48 13.515c.61-.54 1.942-1.107 3.593-.844");
}

.xkwaqpbfb {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.603 17.662l-1.53 3.17c-.19.651.266 1.303.91 1.303h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

</style>
