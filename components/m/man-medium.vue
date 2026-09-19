<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ic8aSBd)"><circle fill="url(#i0GoQ9U)" class="y6h4mvbgz"/></g><circle fill="url(#iQRYcAd)" class="y6h4mvbgz"/><g filter="url(#inhlLCe)"><circle fill="url(#i5ESuld)" class="jfk3ysbzo"/></g><g filter="url(#iFEjE2b)"><circle fill="url(#iNs8PFB)" class="xamti8bbo"/><circle fill="url(#iSK7Scb)" class="xamti8bbo"/></g><g filter="url(#ifI6Fyc)"><circle class="omh0tg8bg"/><circle fill="url(#iIumvJc)" class="rwz2nk4bz"/><circle fill="url(#ia8dkFb)" class="rwz2nk4bz"/></g><g filter="url(#iDMJuze)"><path fill="url(#ilmA2Sb)" class="ced-wvd9h"/><path fill="url(#iexMwmc)" class="ced-wvd9h"/><path fill="url(#ik6a7lb)" class="ced-wvd9h"/></g><path fill="url(#iwWv83b)" class="vp6-di28c"/><path fill="url(#i8PNhLe)" class="vp6-di28c"/><path fill="url(#iW2S7Jc)" class="vp6-di28c"/><path fill="url(#iIExRqd)" class="vp6-di28c"/><g filter="url(#iqiYnQl)"><path fill="url(#i4pSPPc)" class="lz87wtago"/></g><g filter="url(#iVTZ4Le)"><path class="jk-pmsb4i"/><path fill="url(#ihWzvhr)" class="hn7v3_r_d"/><path fill="url(#idGHywC)" class="hn7v3_r_d"/><path fill="url(#ibaVn1c)" class="hn7v3_r_d"/><path fill="url(#irT1Wre)" class="hn7v3_r_d"/></g><g filter="url(#ifY56nc)"><path class="jonf9gbqj"/></g><g filter="url(#iZC5rjc)"><path class="z1jqayb1f"/><path fill="url(#iPtWKCe)" class="svl3smbra"/><path fill="url(#isd3KGd)" class="svl3smbra"/><path fill="url(#ib6hp0d)" class="svl3smbra"/><path fill="url(#i6LAEjb)" class="svl3smbra"/></g><path fill="url(#iht8Wzc)" class="svl3smbra"/><path stroke="url(#iqmTNMe)" class="ygm6t7b6u"/><g filter="url(#iXeTZhc)"><path class="o_wukibzu"/><path fill="url(#iV85Mre)" class="oc6pt9z2c"/></g><g filter="url(#im247Cd)"><path class="dn9j17pcp"/><path fill="url(#iJV4T7c)" class="elgkbzbsm"/></g><path class="s2axe1clu"/><path fill="url(#i3cbgGc)" class="amhd2acsm"/><path class="mmg9bcbxv"/><g filter="url(#iw6sWSb)"><path class="x11ft_07j"/><path fill="url(#idAmIWb)" class="glk_20k3g"/></g><g filter="url(#iSwhBAd)"><path fill="url(#iVWNYHB)" class="n6naizbxd"/></g><path class="dn-3kccjq"/><path fill="url(#icKlKBb)" class="aatijorde"/><path class="bq197y77p"/><g filter="url(#iSotaVd)"><path fill="url(#iGu0AZc)" class="wjr8unmmj"/></g><g filter="url(#iTEykre)"><ellipse transform="rotate(-27.914 11.537 16.608)" class="o6qdzjmyx"/><ellipse fill="url(#ipW6Iee)" transform="rotate(-27.914 11.537 16.608)" class="r1m62ccor"/></g><g filter="url(#ipFdNze)"><path stroke="url(#iOjm6ne)" class="zy4y66vli"/></g><g filter="url(#i5T4M3c)"><path stroke="url(#ihdrOod)" class="gl7lir6wx"/></g><g filter="url(#iyKFd7d)"><path stroke="url(#ipEdboj)" class="p2eecfbhj"/></g><defs><radialGradient id="i0GoQ9U" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 4.149 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iQRYcAd" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.144 8.695)scale(3.08956)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iSK7Scb" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.697 17.565)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iIumvJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.926 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="ia8dkFb" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.455 39.43)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iexMwmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.491 15.688)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ik6a7lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 3.1867 0 11.991 15.938)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iW2S7Jc" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.25 -20.7011 0 15.554 14.75)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="kwao9fbqu"/><stop offset="1" class="wv6j595ib"/></radialGradient><radialGradient id="ihWzvhr" cx="0" cy="0" r="1" gradientTransform="matrix(1.4878 -5.51363 2.04463 .55172 24.22 10.401)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="idGHywC" cx="0" cy="0" r="1" gradientTransform="matrix(7.13272 .65639 -.35293 3.83521 21.156 7.12)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="ibaVn1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.1314 -4.84965 0 16.116 2.019)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="irT1Wre" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.56 1.116)scale(7.1069 11.1342)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="i6LAEjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.727 21.055)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iV85Mre" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 18.75 -5.188)scale(1.14166 3.3775)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iJV4T7c" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.95 .512)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i3cbgGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.18 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="idAmIWb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.026 3.634)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icKlKBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 12.043 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ipW6Iee" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.219 2.932)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ic8aSBd" width="6.427" height="6.227" x="4.149" y="14.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19737"/></filter><filter id="inhlLCe" width="4.711" height="4.711" x="4.907" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".25"/></filter><filter id="iFEjE2b" width="6.477" height="6.477" x="21.89" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19737"/></filter><filter id="ifI6Fyc" width="4.711" height="4.711" x="22.648" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".25"/></filter><filter id="iDMJuze" width="19.345" height="22.68" x="6.497" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19737"/></filter><filter id="iqiYnQl" width="11.918" height="9.719" x="14.433" y="5.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation="1"/></filter><filter id="iVTZ4Le" width="23.5" height="15.5" x="4.366" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19737"/></filter><filter id="ifY56nc" width="4.782" height="6.5" x="13.28" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".375"/></filter><filter id="iZC5rjc" width="4" height="5.5" x="14.116" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".125"/></filter><filter id="iXeTZhc" width="5.34" height="3.147" x="18.321" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19737"/></filter><filter id="im247Cd" width="5.341" height="3.147" x="8.721" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19737"/></filter><filter id="iw6sWSb" width="1.294" height="1.125" x="18.897" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".05"/></filter><filter id="iSwhBAd" width="1.316" height="1.357" x="20.55" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".1"/></filter><filter id="iSotaVd" width="1.493" height="1.594" x="12.267" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".1"/></filter><filter id="iTEykre" width="1.529" height="1.141" x="10.773" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".05"/></filter><filter id="ipFdNze" width="4.949" height="2.304" x="18.463" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".25"/></filter><filter id="i5T4M3c" width="5.094" height="2.41" x="8.73" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".25"/></filter><filter id="iyKFd7d" width="1.231" height="3.583" x="6.807" y="8.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19737" stdDeviation=".125"/></filter><linearGradient id="i5ESuld" x1="7.262" x2="6.068" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iNs8PFB" x1="27.029" x2="25.502" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="ilmA2Sb" x1="23.643" x2="9.401" y1="18.785" y2="20.907" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iwWv83b" x1="6.054" x2="9.563" y1="23.813" y2="23.688" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="i8PNhLe" x1="25.293" x2="23.219" y1="22.243" y2="22.063" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iIExRqd" x1="16.17" x2="16.17" y1="28.283" y2="30.24" gradientUnits="userSpaceOnUse"><stop offset=".533" class="n3-c-obfq"/><stop offset="1" class="o40bvx3go"/></linearGradient><linearGradient id="i4pSPPc" x1="15.125" x2="30.313" y1="13.219" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iPtWKCe" x1="14.505" x2="16.254" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="isd3KGd" x1="17.866" x2="15.954" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="ib6hp0d" x1="16.479" x2="16.479" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iht8Wzc" x1="16.351" x2="16.351" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iqmTNMe" x1="14.182" x2="14.994" y1="25.012" y2="23.73" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iVWNYHB" x1="21.63" x2="21.045" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGu0AZc" x1="13.43" x2="12.845" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOjm6ne" x1="21.66" x2="20.876" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ihdrOod" x1="11.767" x2="9.549" y1="12.659" y2="11.729" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ipEdboj" x1="7.423" x2="7.423" y1="8.902" y2="12.925" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.aatijorde {
  d: path("M12.04 15.897A1.664 1.664 0 0 0 10.436 18h3.215a1.7 1.7 0 0 0 .06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.amhd2acsm {
  d: path("M20.184 15.897A1.664 1.664 0 0 1 21.787 18h-3.214a1.7 1.7 0 0 1-.061-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bq197y77p {
  fill: var(--svg-color--000, #000);
  d: path("M12.993 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.ced-wvd9h {
  d: path("M6.606 16.916q.045.003.091.003s-.1-1.591-.2-2.685c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L25.14 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dn-3kccjq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.654 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.dn9j17pcp {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m9.08 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05a4 4 0 0 1 .222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.elgkbzbsm {
  d: path("m9.08 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05a4 4 0 0 1 .222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.gl7lir6wx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.48 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.glk_20k3g {
  d: path("M20.061 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hn7v3_r_d {
  d: path("m25.103 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89C11.599 2 13.2 1.703 14.6 2.399c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jfk3ysbzo {
  cx: 7.262px;
  cy: 18.059px;
  r: 1.855px;
}

.jk-pmsb4i {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m25.103 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89C11.599 2 13.2 1.703 14.6 2.399c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.jonf9gbqj {
  fill: var(--svg-color--87565c, #87565C);
  d: path("M15.603 17.83L14.073 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kwao9fbqu {
  stop-color: var(--svg-color--975681, #975681);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lz87wtago {
  d: path("m23.508 7.57l-5.74 1.913a1.953 1.953 0 0 0 .878 3.788l5.706-.764z");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmg9bcbxv {
  fill: var(--svg-color--000, #000);
  d: path("M19.23 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.105.439h-1.687a.86.86 0 0 1-.114-.439");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n3-c-obfq {
  stop-color: var(--svg-color--a66d9f, #A66D9F);
  stop-opacity: 0;
}

.n6naizbxd {
  d: path("M21.666 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o_wukibzu {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m23.053 12.986l-.003-.002l-.003-.002l-.008-.007l-.023-.018a3 3 0 0 0-.288-.2a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a3 3 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.o40bvx3go {
  stop-color: var(--svg-color--a66d9f, #A66D9F);
}

.o6qdzjmyx {
  cx: 11.537px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.oc6pt9z2c {
  d: path("m23.053 12.986l-.003-.002l-.003-.002l-.008-.007l-.023-.018a3 3 0 0 0-.288-.2a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a3 3 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.omh0tg8bg {
  cx: 25.003px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.p2eecfbhj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.663 9.086v1.674c-.014.277-.131.897-.481 1.16");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
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

.s2axe1clu {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.57 15.39c1.217 0 2.246.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.svl3smbra {
  d: path("m15.404 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vp6-di28c {
  d: path("M6.497 14.234c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L25.14 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.387-.373-6.785-.683-10.166");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wjr8unmmj {
  d: path("M13.56 17.366c0-.538-.437-.896-.556-1.005l-.537.52l.33.674z");
}

.wv6j595ib {
  stop-color: var(--svg-color--975681, #975681);
}

.x11ft_07j {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.061 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xamti8bbo {
  cx: 25.003px;
  cy: 18.059px;
  r: 3.113px;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y6h4mvbgz {
  cx: 7.262px;
  cy: 18.059px;
  r: 3.113px;
}

.ygm6t7b6u {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.557 23.239h-.001a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z1jqayb1f {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.404 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zy4y66vli {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.213 12.717c.802-.14 2.366-.1 3.449.742");
}

</style>
