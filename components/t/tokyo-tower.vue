<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqk471c)"><path fill="url(#ilrayFb)" clip-rule="evenodd" class="wxwu9h54q"/></g><path fill="url(#i6aMsFz)" clip-rule="evenodd" class="wxwu9h54q"/><path fill="url(#i4yh3Tb)" clip-rule="evenodd" class="wxwu9h54q"/><path fill="url(#ibmSGte)" clip-rule="evenodd" class="wxwu9h54q"/><path fill="url(#ioVdo1H)" clip-rule="evenodd" class="wxwu9h54q"/><g filter="url(#iLFX2he)"><path stroke="url(#iHUbaxd)" class="izty-ubab"/></g><path fill="url(#iausqQe)" class="msdg_4owv"/><path fill="url(#iOmkVTX)" class="msdg_4owv"/><path fill="url(#iKFmf8b)" class="fvxgqubcj"/><path fill="url(#iKpe3Nw)" class="fvxgqubcj"/><path fill="url(#i3Bo56c)" class="fvxgqubcj"/><g filter="url(#ii3CRGb)"><path fill="url(#ilBZyzd)" class="vyva1zbae"/></g><path fill="url(#ipEmHje)" class="vyva1zbae"/><path fill="url(#iwHMhed)" class="vyva1zbae"/><path fill="url(#ihmPLlT)" class="e8ja9fc1b"/><path fill="url(#io92tQd)" class="e8ja9fc1b"/><path fill="url(#iAbPEEy)" class="u5f70ybwl"/><path fill="url(#i9jHNrp)" class="u5f70ybwl"/><g filter="url(#iV9qyxb)"><path stroke="url(#i5AsAGb)" class="dh3u_m8vd"/></g><g filter="url(#irRrS8b)"><path stroke="url(#iZl316d)" class="jtcopg55i"/></g><g filter="url(#iatgNGr)"><path stroke="url(#itYA7PU)" class="q1ik71-2u"/></g><g filter="url(#iCFyX4e)"><path stroke="url(#iI0wVzK)" class="rb9-esbyd"/></g><g filter="url(#iU2jcTb)"><path stroke="url(#izRfeve)" class="c-8ajpbhj"/></g><g filter="url(#iCTFZMc)"><path stroke="url(#iP4Bead)" class="a06_7h7vy"/></g><defs><linearGradient id="ilrayFb" x1="19.437" x2="11.249" y1="21.189" y2="20.961" gradientUnits="userSpaceOnUse"><stop class="ev6o4w7yu"/><stop offset="1" class="v_iq25res"/></linearGradient><linearGradient id="i6aMsFz" x1="22.212" x2="17.875" y1="20.627" y2="22" gradientUnits="userSpaceOnUse"><stop class="bcesubcjx"/><stop offset="1" class="ax9w_jm9z"/></linearGradient><linearGradient id="iHUbaxd" x1="16.501" x2="24.886" y1="4.992" y2="28.728" gradientUnits="userSpaceOnUse"><stop class="kozmnlv6j"/><stop offset="1" class="gh0kcfzpo"/></linearGradient><linearGradient id="iausqQe" x1="7.782" x2="12.985" y1="29.497" y2="29.493" gradientUnits="userSpaceOnUse"><stop class="kx_nnrbvj"/><stop offset="1" class="llamx0epw"/></linearGradient><linearGradient id="iOmkVTX" x1="9.485" x2="9.485" y1="30.156" y2="29.766" gradientUnits="userSpaceOnUse"><stop class="xi20cxlmq"/><stop offset="1" class="pbysotbds"/></linearGradient><linearGradient id="iKFmf8b" x1="19.402" x2="25.295" y1="29.632" y2="29.492" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="i5-01cczj"/></linearGradient><linearGradient id="iKpe3Nw" x1="21.375" x2="25.985" y1="29.497" y2="29.494" gradientUnits="userSpaceOnUse"><stop class="v1dgibbyf"/><stop offset="1" class="gu26ljbif"/></linearGradient><linearGradient id="i3Bo56c" x1="22.485" x2="22.485" y1="30.156" y2="29.766" gradientUnits="userSpaceOnUse"><stop class="vm_wn9kuo"/><stop offset="1" class="gcy1debcf"/></linearGradient><linearGradient id="ilBZyzd" x1="19.794" x2="12.085" y1="15.354" y2="15.566" gradientUnits="userSpaceOnUse"><stop class="jqm39kb6w"/><stop offset="1" class="yn-0mvbxq"/></linearGradient><linearGradient id="ipEmHje" x1="15.937" x2="15.937" y1="16.683" y2="16.309" gradientUnits="userSpaceOnUse"><stop class="brv7iym9y"/><stop offset="1" class="ttnbao_wm"/></linearGradient><linearGradient id="iwHMhed" x1="15.937" x2="15.937" y1="13.313" y2="14.063" gradientUnits="userSpaceOnUse"><stop class="gibcc3bqu"/><stop offset="1" class="p987ijutw"/></linearGradient><linearGradient id="ihmPLlT" x1="16.171" x2="13.749" y1="9.391" y2="8.879" gradientUnits="userSpaceOnUse"><stop offset=".407" class="vgkl71b3v"/><stop offset=".843" class="eygb4jb-b"/></linearGradient><linearGradient id="io92tQd" x1="18.062" x2="17.093" y1="9.797" y2="9.984" gradientUnits="userSpaceOnUse"><stop offset=".179" class="mmi_gfead"/><stop offset="1" class="zzpvmbbrw"/></linearGradient><linearGradient id="iAbPEEy" x1="16" x2="14.685" y1="5.203" y2="5.182" gradientUnits="userSpaceOnUse"><stop offset=".233" class="vgkl71b3v"/><stop offset=".762" class="eygb4jb-b"/></linearGradient><linearGradient id="i9jHNrp" x1="17.195" x2="16.618" y1="5.797" y2="5.862" gradientUnits="userSpaceOnUse"><stop offset=".179" class="mmi_gfead"/><stop offset="1" class="zzpvmbbrw"/></linearGradient><linearGradient id="i5AsAGb" x1="13.463" x2="20.795" y1="18.318" y2="22.774" gradientUnits="userSpaceOnUse"><stop class="fgaabmpif"/><stop offset="1" class="i0z_sybku"/></linearGradient><linearGradient id="iZl316d" x1="18.932" x2="11.6" y1="18.318" y2="22.774" gradientUnits="userSpaceOnUse"><stop class="i0z_sybku"/><stop offset="1" class="ueuaj0gqf"/></linearGradient><linearGradient id="itYA7PU" x1="18.567" x2="16.715" y1="17.265" y2="14.736" gradientUnits="userSpaceOnUse"><stop class="i0z_sybku"/><stop offset="1" class="ueuaj0gqf"/></linearGradient><linearGradient id="iI0wVzK" x1="20.957" x2="10.02" y1="22.693" y2="22.693" gradientUnits="userSpaceOnUse"><stop class="i0z_sybku"/><stop offset="1" class="ueuaj0gqf"/></linearGradient><linearGradient id="izRfeve" x1="16.307" x2="17.574" y1="17.387" y2="17.668" gradientUnits="userSpaceOnUse"><stop class="i0z_sybku"/><stop offset="1" class="ueuaj0gqf"/></linearGradient><linearGradient id="iP4Bead" x1="12.892" x2="18.756" y1="25.094" y2="29.041" gradientUnits="userSpaceOnUse"><stop class="i6heq9bzz"/><stop offset="1" class="jvhau5btw"/></linearGradient><filter id="iqk471c" width="17.932" height="27.25" x="7.019" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.278431 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6964"/></filter><filter id="iLFX2he" width="8.956" height="24.55" x="15.851" y="4.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6964" stdDeviation=".25"/></filter><filter id="ii3CRGb" width="8.214" height="3.02" x="11.829" y="13.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.513726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6964"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.85098 0 0 0 0 0.909804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6964" result="effect2_innerShadow_18_6964"/></filter><filter id="iV9qyxb" width="8.953" height="6.239" x="12.349" y="17.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6964" stdDeviation=".25"/></filter><filter id="irRrS8b" width="8.953" height="6.239" x="11.093" y="17.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6964" stdDeviation=".25"/></filter><filter id="iatgNGr" width="6.806" height="1.5" x="12.511" y="16.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6964" stdDeviation=".25"/></filter><filter id="iCFyX4e" width="11.91" height="1.5" x="9.797" y="23.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6964" stdDeviation=".25"/></filter><filter id="iU2jcTb" width="1.5" height="8.021" x="15.508" y="16.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6964" stdDeviation=".25"/></filter><filter id="iCTFZMc" width="9.703" height="4.942" x="11.741" y="24.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6964" stdDeviation=".25"/></filter><radialGradient id="i4yh3Tb" cx="0" cy="0" r="1" gradientTransform="matrix(.56708 -2.9164 .4212 .0819 14.921 13.174)" gradientUnits="userSpaceOnUse"><stop class="j20fl5bja"/><stop offset="1" class="x3v72rbdz"/></radialGradient><radialGradient id="ibmSGte" cx="0" cy="0" r="1" gradientTransform="matrix(-.42531 -2.8354 .4095 -.06142 16.947 13.113)" gradientUnits="userSpaceOnUse"><stop class="j20fl5bja"/><stop offset="1" class="x3v72rbdz"/></radialGradient><radialGradient id="ioVdo1H" cx="0" cy="0" r="1" gradientTransform="matrix(1.27593 0 0 4.0146 14.881 2.906)" gradientUnits="userSpaceOnUse"><stop class="s1nbd6dgc"/><stop offset="1" class="xuam90qng"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tokyo-tower" /></template>
<style>
.a06_7h7vy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.491 26.559c.358-.488 1.523-1.465 3.32-1.465c2.246 0 3.955.977 4.882 3.442");
}

.ax9w_jm9z {
  stop-color: var(--svg-color--ff8f43, #FF8F43);
  stop-opacity: 0;
}

.bcesubcjx {
  stop-color: var(--svg-color--ff8f43, #FF8F43);
}

.brv7iym9y {
  stop-color: var(--svg-color--947e9e, #947E9E);
}

.c-8ajpbhj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.258 17.387v6.521");
}

.dh3u_m8vd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m13.099 18.318l7.453 4.74");
}

.e8ja9fc1b {
  d: path("M14.085 10.063h3.84c-.17-.71-.32-1.38-.44-2h-2.93c-.13.64-.29 1.31-.47 2");
}

.ev6o4w7yu {
  stop-color: var(--svg-color--f86625, #F86625);
}

.eygb4jb-b {
  stop-color: var(--svg-color--a7908e, #A7908E);
}

.fgaabmpif {
  stop-color: var(--svg-color--f25f3d, #F25F3D);
}

.ft5dv1b6b {
  fill: none;
}

.fvxgqubcj {
  d: path("M25.476 29.063h-5.982a.506.506 0 0 0-.509.5c0 .274.23.5.51.5h5.98c.28 0 .51-.226.51-.5c0-.275-.23-.5-.51-.5");
}

.gcy1debcf {
  stop-color: var(--svg-color--e35030, #E35030);
  stop-opacity: 0;
}

.gh0kcfzpo {
  stop-color: var(--svg-color--ff8f46, #FF8F46);
}

.ghzd3_bys {
  stop-color: var(--svg-color--ee3124, #EE3124);
}

.gibcc3bqu {
  stop-color: var(--svg-color--c1b6b8, #C1B6B8);
}

.gu26ljbif {
  stop-color: var(--svg-color--f8732d, #F8732D);
}

.i0z_sybku {
  stop-color: var(--svg-color--ff864b, #FF864B);
}

.i5-01cczj {
  stop-color: var(--svg-color--ff8213, #FF8213);
}

.i6heq9bzz {
  stop-color: var(--svg-color--eb4d30, #EB4D30);
}

.izty-ubab {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.501 5.478c.81 4.415 3.476 15.246 7.656 23.25");
}

.j20fl5bja {
  stop-color: var(--svg-color--e03f09, #E03F09);
}

.jqm39kb6w {
  stop-color: var(--svg-color--cfc1d6, #CFC1D6);
}

.jtcopg55i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.296 18.318l-7.453 4.74");
}

.jvhau5btw {
  stop-color: var(--svg-color--ff803c, #FF803C);
}

.kozmnlv6j {
  stop-color: var(--svg-color--ffa464, #FFA464);
}

.kx_nnrbvj {
  stop-color: var(--svg-color--df143b, #DF143B);
}

.llamx0epw {
  stop-color: var(--svg-color--e15c4a, #E15C4A);
}

.mmi_gfead {
  stop-color: var(--svg-color--ede9f0, #EDE9F0);
}

.msdg_4owv {
  d: path("M12.476 29.063H6.494a.506.506 0 0 0-.509.5c0 .274.23.5.51.5h5.98c.28 0 .51-.226.51-.5c0-.275-.23-.5-.51-.5");
}

.p987ijutw {
  stop-color: var(--svg-color--c1b6b8, #C1B6B8);
  stop-opacity: 0;
}

.pbysotbds {
  stop-color: var(--svg-color--c62d45, #C62D45);
  stop-opacity: 0;
}

.q1ik71-2u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M13.26 17.265h5.307");
}

.rb9-esbyd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.547 24.11h10.41");
}

.s1nbd6dgc {
  stop-color: var(--svg-color--f15134, #F15134);
}

.ttnbao_wm {
  stop-color: var(--svg-color--947e9e, #947E9E);
  stop-opacity: 0;
}

.u5f70ybwl {
  d: path("M17.115 6.063c-.07-.54-.13-1-.13-1.5v-.5h-2v.55c0 .46-.04.95-.1 1.45z");
}

.ueuaj0gqf {
  stop-color: var(--svg-color--ee4a32, #EE4A32);
}

.v_iq25res {
  stop-color: var(--svg-color--ec383e, #EC383E);
}

.v1dgibbyf {
  stop-color: var(--svg-color--ed6033, #ED6033);
}

.vgkl71b3v {
  stop-color: var(--svg-color--c3b7c8, #C3B7C8);
}

.vm_wn9kuo {
  stop-color: var(--svg-color--e35030, #E35030);
}

.vyva1zbae {
  d: path("m19.332 13.586l-6.78-.044c-.263 0-.473.193-.473.434v2.586h7.715V14.02c.01-.241-.2-.434-.462-.434");
}

.wxwu9h54q {
  fill-rule: evenodd;
  d: path("M11.426 18.59q.243-.76.488-1.513l.198-.607c1.488-4.574 2.873-8.832 2.873-11.907l-.005-1.507a1 1 0 0 1 1-.993h.01c.55.01.99.456 1 .993l-.005 1.507c0 1.956 1.09 6.74 2.81 12l.17.513q.001.003.004.002q.003 0 .004.002q.255.764.524 1.535q0 .003-.002.004l-.001.004a92 92 0 0 0 1.817 4.764q.267.644.542 1.274a57 57 0 0 0 2.092 4.328a.05.05 0 0 1-.044.073h-4.942a.05.05 0 0 1-.05-.04a4.004 4.004 0 0 0-3.919-3.147a4.004 4.004 0 0 0-3.92 3.147a.05.05 0 0 1-.049.04H7.07a.05.05 0 0 1-.044-.073a59 59 0 0 0 2.686-5.655l.002-.002a58 58 0 0 0 1.713-4.742m5.359-2.027a.05.05 0 0 1-.05-.05v-4.61c0-.06.084-.07.1-.014a94 94 0 0 0 1.354 4.608a.05.05 0 0 1-.048.066zm-1.6 0a.05.05 0 0 0 .05-.05v-4.655c0-.058-.083-.07-.099-.014a142 142 0 0 1-1.47 4.653a.05.05 0 0 0 .048.066zm-2.61 6.907c-.044.026-.025.093.026.093h2.584a.05.05 0 0 0 .05-.05V21.93a.05.05 0 0 0-.076-.043zm1.796-3.075a.05.05 0 0 1 0 .085l-2.428 1.487a.05.05 0 0 1-.074-.06q.451-1.221.844-2.456a.05.05 0 0 1 .073-.027zm3.21.01a.05.05 0 0 0 0 .085l2.45 1.5a.05.05 0 0 0 .072-.06a98 98 0 0 1-.905-2.446a.05.05 0 0 0-.073-.026zm.56-2.343c.05 0 .07.067.027.093l-1.357.83a.05.05 0 0 1-.076-.042v-.83a.05.05 0 0 1 .05-.05zm-2.956 0a.05.05 0 0 1 .05.05v.852a.05.05 0 0 1-.076.043l-1.39-.852c-.043-.026-.024-.093.026-.093zm4.18 5.5c.051 0 .07-.066.027-.092l-2.58-1.58a.05.05 0 0 0-.077.042v1.58c0 .028.022.05.05.05zm-.574 1.597c-.045-.026-.026-.096.025-.096h2.533a.05.05 0 0 1 .046.03q.536 1.24 1.097 2.408a.05.05 0 0 1-.045.072H21.01a.05.05 0 0 1-.045-.029a5.5 5.5 0 0 0-2.173-2.385m-8.205-.066a.05.05 0 0 1 .046-.03h2.506c.052 0 .07.07.026.096a5.5 5.5 0 0 0-2.168 2.385a.05.05 0 0 1-.045.029H9.514a.05.05 0 0 1-.045-.072q.585-1.195 1.117-2.408");
}

.x3v72rbdz {
  stop-color: var(--svg-color--e03f09, #E03F09);
  stop-opacity: 0;
}

.xi20cxlmq {
  stop-color: var(--svg-color--c62d45, #C62D45);
}

.xuam90qng {
  stop-color: var(--svg-color--f15134, #F15134);
  stop-opacity: 0;
}

.yn-0mvbxq {
  stop-color: var(--svg-color--9f93a3, #9F93A3);
}

.zzpvmbbrw {
  stop-color: var(--svg-color--ede9f0, #EDE9F0);
  stop-opacity: 0;
}

</style>
