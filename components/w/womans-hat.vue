<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#if8jeXc)"><path fill="url(#iQgrJze)" class="q_hopibzu"/><path fill="url(#iYR2BMs)" class="q_hopibzu"/></g><g filter="url(#iekO9cb)"><path stroke="url(#iibbavc)" class="yrs51ybov"/></g><g filter="url(#imu4WOe)"><path fill="url(#ixPQkJb)" class="arm9ow8wn"/><path fill="url(#ii9LKGc)" class="arm9ow8wn"/></g><g filter="url(#ieBkyGe)"><path class="qc-xy-9rm"/></g><g filter="url(#ioRW8mb)"><path fill="url(#i2Wmmue)" class="yy5kdgb4j"/><path fill="url(#iIEsSjd)" class="yy5kdgb4j"/></g><g filter="url(#ihUp4pc)"><path fill="url(#iQuv3Gd)" class="aukd7cbgo"/><path fill="url(#i8LPYje)" class="aukd7cbgo"/></g><path fill="url(#idLYx3G)" class="s4m2gryvp"/><g filter="url(#iJUbVld)"><path fill="url(#iiSnazU)" class="pebx9_b5x"/><path fill="url(#ielUHbe)" class="pebx9_b5x"/></g><path fill="url(#iUuvmik)" class="p8iocomfz"/><path fill="url(#i5qB6ue)" class="p8iocomfz"/><path fill="url(#i2oUzKe)" clip-rule="evenodd" class="iintq0d0c"/><path fill="url(#ikORgdb)" class="pc-9n12zk"/><path fill="url(#ibo2zxe)" class="pc-9n12zk"/><path fill="url(#i8DoPJb)" class="qj4-z0gzg"/><path fill="url(#i2UBNvb)" clip-rule="evenodd" class="jn7__3bwi"/><g filter="url(#iKkXace)"><rect fill="url(#ic3PbWd)" class="ax9cydber"/></g><g filter="url(#iugv3qa)"><ellipse class="xe4rm3b-a"/></g><g filter="url(#iQxj6Vd)"><path fill="url(#iCkFb0I)" class="tywfg8bsa"/></g><g filter="url(#igIlvSc)"><path stroke="url(#iJH49Ee)" class="unree3bju"/></g><g filter="url(#izbPzid)"><path stroke="url(#icvMFDc)" class="mf_ksyttz"/></g><defs><linearGradient id="iQgrJze" x1="2.057" x2="29.776" y1="23" y2="23" gradientUnits="userSpaceOnUse"><stop class="l97yfykvf"/><stop offset=".594" class="m1e1tu26e"/><stop offset=".802" class="jf0lffnsc"/></linearGradient><linearGradient id="ixPQkJb" x1="21.463" x2="8.026" y1="15.063" y2="15.063" gradientUnits="userSpaceOnUse"><stop class="umzakg-9y"/><stop offset="1" class="qkb5pbbwn"/></linearGradient><linearGradient id="ii9LKGc" x1="18.213" x2="18.713" y1="26.625" y2="18.563" gradientUnits="userSpaceOnUse"><stop class="xl8k8-txd"/><stop offset="1" class="v_sn9vhxe"/></linearGradient><linearGradient id="i2Wmmue" x1="21.156" x2="19.39" y1="24.482" y2="29.659" gradientUnits="userSpaceOnUse"><stop offset=".265" class="l97i_p84x"/><stop offset="1" class="jxwl9v2gf"/></linearGradient><linearGradient id="iQuv3Gd" x1="23.963" x2="24.038" y1="23.563" y2="29.659" gradientUnits="userSpaceOnUse"><stop offset=".265" class="l97i_p84x"/><stop offset="1" class="jxwl9v2gf"/></linearGradient><linearGradient id="idLYx3G" x1="15.145" x2="22.238" y1="22.305" y2="22.305" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iiSnazU" x1="20.463" x2="14.95" y1="21.242" y2="21.242" gradientUnits="userSpaceOnUse"><stop class="p3yt7cc0v"/><stop offset=".453" class="wpsvwx1kk"/><stop offset=".918" class="l8_po90im"/></linearGradient><linearGradient id="ielUHbe" x1="20.735" x2="19.651" y1="23.781" y2="23.781" gradientUnits="userSpaceOnUse"><stop offset=".279" class="cpxa22b6k"/><stop offset="1" class="unrik3biz"/></linearGradient><linearGradient id="i5qB6ue" x1="20.02" x2="19.173" y1="24.797" y2="23.587" gradientUnits="userSpaceOnUse"><stop offset=".153" class="q7eek4buc"/><stop offset="1" class="eibjaokbp"/></linearGradient><linearGradient id="i2oUzKe" x1="15.658" x2="20.486" y1="23.641" y2="23.607" gradientUnits="userSpaceOnUse"><stop class="epn402gwt"/><stop offset="1" class="dpl2k3m2v"/></linearGradient><linearGradient id="ikORgdb" x1="23.963" x2="28.244" y1="22.031" y2="22.031" gradientUnits="userSpaceOnUse"><stop class="r8mn7o_ri"/><stop offset="1" class="qlvd7jezf"/></linearGradient><linearGradient id="ibo2zxe" x1="28.963" x2="27.526" y1="23.969" y2="23.969" gradientUnits="userSpaceOnUse"><stop class="njvj6r3gg"/><stop offset="1" class="zns-bvbiy"/></linearGradient><linearGradient id="i2UBNvb" x1="28.619" x2="23.791" y1="23.641" y2="23.607" gradientUnits="userSpaceOnUse"><stop class="m-pzp6bpx"/><stop offset="1" class="fm-pyvb6f"/></linearGradient><linearGradient id="ic3PbWd" x1="21.901" x2="21.901" y1="19.239" y2="24.687" gradientUnits="userSpaceOnUse"><stop class="hkee3c7nc"/><stop offset="1" class="r65qq8rpw"/></linearGradient><linearGradient id="iCkFb0I" x1="23.526" x2="15.374" y1="14.125" y2="14.125" gradientUnits="userSpaceOnUse"><stop class="ka0qpbbiz"/><stop offset="1" class="x75hib93w"/></linearGradient><filter id="if8jeXc" width="27.719" height="13.531" x="2.057" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.486275 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17427"/></filter><filter id="iekO9cb" width="6.025" height="9.785" x="23.74" y="18.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17427" stdDeviation=".125"/></filter><filter id="imu4WOe" width="17.281" height="13.453" x="8.026" y="9.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.568627 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17427"/></filter><filter id="ieBkyGe" width="15.781" height="5.131" x="8.026" y="17.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.235294 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17427"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.152941 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17427" result="effect2_innerShadow_18_17427"/></filter><filter id="ioRW8mb" width="5.066" height="6.643" x="17.258" y="23.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.152941 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17427"/></filter><filter id="ihUp4pc" width="5.066" height="6.643" x="21.906" y="23.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.152941 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17427"/></filter><filter id="iJUbVld" width="5.077" height="5.458" x="15.658" y="18.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.176471 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17427"/></filter><filter id="iKkXace" width="3.333" height="5.985" x="20.448" y="19.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.054902 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17427"/></filter><filter id="iugv3qa" width="1.85" height="1.558" x="22.037" y="23.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17427" stdDeviation=".25"/></filter><filter id="iQxj6Vd" width="10.164" height="6.031" x="14.124" y="9.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17427" stdDeviation=".625"/></filter><filter id="igIlvSc" width="1.613" height="3.509" x="20.118" y="25.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17427" stdDeviation=".075"/></filter><filter id="izbPzid" width="1.284" height="2.626" x="25.376" y="25.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17427" stdDeviation=".075"/></filter><radialGradient id="iYR2BMs" cx="0" cy="0" r="1" gradientTransform="rotate(-100.181 23.841 4.73)scale(7.77874 3.32765)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="gnm39mblh"/><stop offset="1" class="z_566_b6l"/></radialGradient><radialGradient id="iibbavc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25 5.3125 -3.1432 -3.10622 30.15 21.75)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="xxfcvcb_d"/><stop offset="1" class="y5xweczmu"/></radialGradient><radialGradient id="iIEsSjd" cx="0" cy="0" r="1" gradientTransform="rotate(116.946 3.22 18.756)scale(3.25635 4.01953)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="bbaomj29x"/><stop offset="1" class="sb537vbhr"/></radialGradient><radialGradient id="i8LPYje" cx="0" cy="0" r="1" gradientTransform="rotate(102.529 3.05 21.834)scale(4.03355 4.97889)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="bbaomj29x"/><stop offset="1" class="sb537vbhr"/></radialGradient><radialGradient id="iUuvmik" cx="0" cy="0" r="1" gradientTransform="rotate(-67.342 27.583 -.251)scale(3.00973 7.89031)" gradientUnits="userSpaceOnUse"><stop class="p2dtx8b-f"/><stop offset=".459" class="u-e3p3bbw"/></radialGradient><radialGradient id="i8DoPJb" cx="0" cy="0" r="1" gradientTransform="matrix(.8714 -2.43426 6.38166 2.28446 25.294 25.3)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="w93ughx6u"/><stop offset=".817" class="pc-thj0xz"/></radialGradient><radialGradient id="iJH49Ee" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 -.3125 .43103 -1.0776 21.244 27)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="nnycftuor"/><stop offset="1" class="dzqyntbfd"/></radialGradient><radialGradient id="icvMFDc" cx="0" cy="0" r="1" gradientTransform="rotate(-112.433 22.1 4.802)scale(.92128 1.11798)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="nnycftuor"/><stop offset="1" class="dzqyntbfd"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:womans-hat" /></template>
<style>
.arm9ow8wn {
  d: path("M8.026 14.766a4.75 4.75 0 0 1 4.75-4.75h6.28a4.75 4.75 0 0 1 4.75 4.75v6.203a2 2 0 0 1-2 2h-11.78a2 2 0 0 1-2-2z");
}

.aukd7cbgo {
  d: path("m24.906 23.203l-3 1.092l1.937 5.321c.108.3.528.31.651.016l.303-.72a.6.6 0 0 1 .82-.306l.748.37a.35.35 0 0 0 .484-.433z");
}

.ax9cydber {
  width: 3.233px;
  height: 5.985px;
  x: 20.448px;
  y: 19.239px;
  rx: 1px;
}

.bbaomj29x {
  stop-color: var(--svg-color--ab0234, #AB0234);
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cpxa22b6k {
  stop-color: var(--svg-color--c7174b, #C7174B);
}

.dpl2k3m2v {
  stop-color: var(--svg-color--d2186e, #D2186E);
}

.dzqyntbfd {
  stop-color: var(--svg-color--d93864, #D93864);
  stop-opacity: 0;
}

.eibjaokbp {
  stop-color: var(--svg-color--b80844, #B80844);
  stop-opacity: 0;
}

.epn402gwt {
  stop-color: var(--svg-color--dc164e, #DC164E);
}

.fm-pyvb6f {
  stop-color: var(--svg-color--ef1648, #EF1648);
}

.ft5dv1b6b {
  fill: none;
}

.gnm39mblh {
  stop-color: var(--svg-color--e38f64, #E38F64);
}

.hkee3c7nc {
  stop-color: var(--svg-color--e1326f, #E1326F);
}

.iintq0d0c {
  fill-rule: evenodd;
  d: path("M16 24.027c0-1.066 1.498-1.564 2.464-1.086l2.233 1.088l-2.233 1.09c-.966.477-2.464-.02-2.464-1.087zm-.342.003v-.003c0-.72.51-1.21 1.085-1.44c.573-.229 1.29-.24 1.872.047l2.232 1.088a.342.342 0 0 1 0 .615l-2.232 1.088c-.581.287-1.3.276-1.872.047c-.575-.23-1.085-.72-1.085-1.44z");
}

.jf0lffnsc {
  stop-color: var(--svg-color--ffc185, #FFC185);
}

.jn7__3bwi {
  fill-rule: evenodd;
  d: path("M28.277 24.027c0-1.066-1.498-1.564-2.463-1.086l-2.234 1.088l2.234 1.09c.965.477 2.463-.02 2.463-1.087zm.342.003v-.003c0-.72-.51-1.21-1.084-1.44c-.573-.229-1.291-.24-1.872.047h-.001l-2.232 1.088a.342.342 0 0 0 0 .615l2.232 1.088c.582.287 1.3.276 1.873.047c.574-.23 1.084-.72 1.084-1.44z");
}

.jxwl9v2gf {
  stop-color: var(--svg-color--ed193d, #ED193D);
}

.ka0qpbbiz {
  stop-color: var(--svg-color--ffe39f, #FFE39F);
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.l8_po90im {
  stop-color: var(--svg-color--bf3941, #BF3941);
}

.l97i_p84x {
  stop-color: var(--svg-color--cf3162, #CF3162);
}

.l97yfykvf {
  stop-color: var(--svg-color--e6a679, #E6A679);
}

.m-pzp6bpx {
  stop-color: var(--svg-color--ce2074, #CE2074);
}

.m1e1tu26e {
  stop-color: var(--svg-color--cc6f52, #CC6F52);
}

.mf_ksyttz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m25.596 25.79l.844 2.273");
}

.njvj6r3gg {
  stop-color: var(--svg-color--ff5564, #FF5564);
}

.nnycftuor {
  stop-color: var(--svg-color--d93864, #D93864);
}

.p2dtx8b-f {
  stop-color: var(--svg-color--d30631, #D30631);
}

.p3yt7cc0v {
  stop-color: var(--svg-color--e1406f, #E1406F);
}

.p8iocomfz {
  d: path("M16 24.027c0-1.066 1.498-1.564 2.464-1.086l2.233 1.088l-2.233 1.09c-.966.477-2.464-.02-2.464-1.087z");
}

.pc-9n12zk {
  d: path("M28.62 20.585c-.003-1.153-1.376-1.993-2.796-1.493l-1.716.765q-.271.12-.565.15v4.295l5.076-.28z");
}

.pc-thj0xz {
  stop-color: var(--svg-color--bb2825, #BB2825);
}

.pebx9_b5x {
  d: path("M15.658 20.585c.003-1.153 1.375-1.993 2.795-1.493l1.717.765c.179.08.37.13.564.15v4.295l-5.076-.28z");
}

.q_hopibzu {
  d: path("M2.057 22.516A6.516 6.516 0 0 1 8.573 16H23.26a6.516 6.516 0 0 1 6.516 6.516c0 3.598-3.355 6.515-6.953 6.515H8.979c-3.599 0-6.922-2.917-6.922-6.515");
}

.q7eek4buc {
  stop-color: var(--svg-color--b80844, #B80844);
}

.qc-xy-9rm {
  fill: var(--svg-color--c42e65, #C42E65);
  d: path("M8.026 17.938v3.03a2 2 0 0 0 2 2h11.78a2 2 0 0 0 2-2v-3.03a2.25 2.25 0 0 1-2.25 2.25h-11.28a2.25 2.25 0 0 1-2.25-2.25");
}

.qj4-z0gzg {
  d: path("M28.277 24.027c0-1.066-1.498-1.564-2.463-1.086l-2.234 1.088l2.234 1.09c.965.477 2.463-.02 2.463-1.087z");
}

.qkb5pbbwn {
  stop-color: var(--svg-color--e09a6a, #E09A6A);
}

.qlvd7jezf {
  stop-color: var(--svg-color--eb3452, #EB3452);
}

.r65qq8rpw {
  stop-color: var(--svg-color--eb143e, #EB143E);
}

.r8mn7o_ri {
  stop-color: var(--svg-color--c52a54, #C52A54);
}

.s4m2gryvp {
  d: path("m21.894 23.507l.17.075l.172-.075v-2.405l-.171-.082l-.171.082z");
}

.sb537vbhr {
  stop-color: var(--svg-color--ab0234, #AB0234);
  stop-opacity: 0;
}

.tywfg8bsa {
  d: path("M15.374 14.531h7.664A3.53 3.53 0 0 0 19.507 11h-4.133z");
}

.u-e3p3bbw {
  stop-color: var(--svg-color--a20a18, #A20A18);
}

.umzakg-9y {
  stop-color: var(--svg-color--ffc883, #FFC883);
}

.unree3bju {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m21.51 25.688l-1.172 3.156");
}

.unrik3biz {
  stop-color: var(--svg-color--d8396e, #D8396E);
  stop-opacity: 0;
}

.v_sn9vhxe {
  stop-color: var(--svg-color--c77f5d, #C77F5D);
  stop-opacity: 0;
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.w93ughx6u {
  stop-color: var(--svg-color--d2134e, #D2134E);
}

.wpsvwx1kk {
  stop-color: var(--svg-color--de2f5c, #DE2F5C);
}

.x75hib93w {
  stop-color: var(--svg-color--ffe39f, #FFE39F);
  stop-opacity: 0;
}

.xe4rm3b-a {
  cx: 22.962px;
  cy: 23.893px;
  fill: var(--svg-color--ff565b, #FF565B);
  rx: 0.425px;
  ry: 0.279px;
}

.xl8k8-txd {
  stop-color: var(--svg-color--c77f5d, #C77F5D);
}

.xxfcvcb_d {
  stop-color: var(--svg-color--ffd5a1, #FFD5A1);
}

.y5xweczmu {
  stop-color: var(--svg-color--ffd5a1, #FFD5A1);
  stop-opacity: 0;
}

.yrs51ybov {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M28.338 19.11c.656 1.015 1.163 1.88 1.031 3.687c-.201 2.76-2.843 5-5.359 5.406");
}

.yy5kdgb4j {
  d: path("m19.224 23.203l3 1.092l-1.937 5.321a.35.35 0 0 1-.652.016l-.303-.72a.6.6 0 0 0-.819-.306l-.749.37a.35.35 0 0 1-.484-.433z");
}

.z_566_b6l {
  stop-color: var(--svg-color--e38f64, #E38F64);
  stop-opacity: 0;
}

.zns-bvbiy {
  stop-color: var(--svg-color--ff5564, #FF5564);
  stop-opacity: 0;
}

</style>
