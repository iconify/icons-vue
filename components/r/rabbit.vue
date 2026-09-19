<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i528slb)"><path fill="url(#ikjabCb)" class="absh5cxna"/><path fill="url(#iHJDmBc)" class="absh5cxna"/><path fill="url(#izCbksc)" class="absh5cxna"/><path fill="url(#iPG02jd)" class="absh5cxna"/><path fill="url(#ibck4ux)" class="absh5cxna"/><path fill="url(#iztzdxe)" class="absh5cxna"/><path fill="url(#i2M1ZKX)" class="absh5cxna"/></g><path fill="url(#im41kvd)" class="cd3a-xh0u"/><path fill="url(#ixc2SHe)" class="cd3a-xh0u"/><g filter="url(#itFJsxe)"><path stroke="url(#iZmIdoc)" class="inkr_6bmh"/></g><path fill="url(#iB8StUd)" class="tyey3acxy"/><path fill="url(#iVWdKGb)" class="tyey3acxy"/><path fill="url(#ihaCSjA)" class="tyey3acxy"/><path fill="url(#imrMO1b)" class="tyey3acxy"/><path fill="url(#iR7KGPe)" class="d1rht2bjk"/><path class="f_gcs9bph"/><path fill="url(#i8Q5Npe)" class="d1rht2bjk"/><path fill="url(#iKQvBgb)" class="d1rht2bjk"/><path fill="url(#ic1d96d)" class="d1rht2bjk"/><path fill="url(#iEkTlxb)" class="d1rht2bjk"/><path fill="url(#in4wUxJ)" class="x-4n1sbgs"/><g filter="url(#iIPbPzm)"><path class="x8v-wmb8s"/><path fill="url(#iGstAxc)" class="mie1mbc7w"/><path fill="url(#i1LTK5c)" class="mie1mbc7w"/></g><path fill="url(#iWafQ0d)" class="mie1mbc7w"/><path fill="url(#i5quz3f)" class="mie1mbc7w"/><path fill="url(#igfDqCd)" class="mie1mbc7w"/><g filter="url(#iZDUxbb)"><path class="g_r7gubhh"/></g><path fill="url(#i57tOnt)" class="b7syu2g4q"/><path fill="url(#iIhKvrc)" class="b7syu2g4q"/><path fill="url(#iq8ofac)" class="b7syu2g4q"/><path fill="url(#iXOUPqc)" class="ekw8a3eot"/><path fill="url(#i5pUdte)" class="ekw8a3eot"/><path fill="url(#ipJTa2V)" class="guzjm2jhl"/><path fill="url(#iEOHtZd)" class="guzjm2jhl"/><path fill="url(#iZpb5Ge)" class="guzjm2jhl"/><path fill="url(#if464Me)" class="i4lalcbtz"/><path fill="url(#iPhdbBd)" class="i4lalcbtz"/><path fill="url(#iumJlDd)" class="i4lalcbtz"/><path fill="url(#iVMgfAg)" class="i4lalcbtz"/><path fill="url(#iejZEzb)" class="fo1ixmb2i"/><path fill="url(#icFzIvc)" class="fo1ixmb2i"/><g filter="url(#iId1g4b)"><path stroke="url(#icf94te)" class="xyygu9b1d"/></g><g filter="url(#i6qgmue)"><path stroke="url(#ikAKflw)" class="hwl-htb3l"/></g><g filter="url(#iAfzRjd)"><path stroke="url(#iqlSlEe)" class="zda8kp16s"/></g><g filter="url(#imkLapd)"><path stroke="url(#iBa3jvb)" class="msh0b0bmy"/></g><g filter="url(#imMEsvb)"><path stroke="url(#i56ESob)" class="mevictbbm"/></g><defs><linearGradient id="ikjabCb" x1="22.195" x2="25.195" y1="28.063" y2="15.625" gradientUnits="userSpaceOnUse"><stop class="qq07jh8ff"/><stop offset="1" class="o90bthbyb"/></linearGradient><linearGradient id="iHJDmBc" x1="18.71" x2="18.71" y1="11.844" y2="14.813" gradientUnits="userSpaceOnUse"><stop class="m-c_d-rde"/><stop offset=".83" class="i66sqmxxb"/></linearGradient><linearGradient id="izCbksc" x1="18.71" x2="18.71" y1="12.188" y2="17.188" gradientUnits="userSpaceOnUse"><stop class="ya1f_8b2z"/><stop offset="1" class="qoeernbaz"/></linearGradient><linearGradient id="iztzdxe" x1="15.632" x2="15.601" y1="31.25" y2="26.973" gradientUnits="userSpaceOnUse"><stop class="rn_358bir"/><stop offset=".577" class="i9lfkzbcw"/></linearGradient><linearGradient id="im41kvd" x1="17.632" x2="16.648" y1="28.063" y2="24.734" gradientUnits="userSpaceOnUse"><stop class="g4ir5_irg"/><stop offset="1" class="dcze57b7u"/></linearGradient><linearGradient id="ixc2SHe" x1="16.976" x2="16.976" y1="27.034" y2="26.156" gradientUnits="userSpaceOnUse"><stop class="k7syk3brx"/><stop offset="1" class="rlti5mboa"/></linearGradient><linearGradient id="iZmIdoc" x1="24.195" x2="16.757" y1="14.65" y2="14.65" gradientUnits="userSpaceOnUse"><stop class="f9lbf8blm"/><stop offset="1" class="q2sk3g_gm"/></linearGradient><linearGradient id="i8Q5Npe" x1="10.132" x2="10.695" y1="4.703" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="q5bhxbkvc"/><stop offset="1" class="r6qd37uwh"/></linearGradient><linearGradient id="iKQvBgb" x1="13.695" x2="13.32" y1="7.906" y2="5.594" gradientUnits="userSpaceOnUse"><stop class="q5bhxbkvc"/><stop offset="1" class="r6qd37uwh"/></linearGradient><linearGradient id="iGstAxc" x1="19.288" x2="19.288" y1="30.969" y2="28" gradientUnits="userSpaceOnUse"><stop class="rn_358bir"/><stop offset=".678" class="i9lfkzbcw"/></linearGradient><linearGradient id="iWafQ0d" x1="28.109" x2="21.152" y1="20.734" y2="27.563" gradientUnits="userSpaceOnUse"><stop class="st7_5ybbw"/><stop offset="1" class="hjezcrbuz"/></linearGradient><linearGradient id="igfDqCd" x1="27.132" x2="25.507" y1="25.844" y2="25.211" gradientUnits="userSpaceOnUse"><stop offset=".283" class="st7_5ybbw"/><stop offset="1" class="hjezcrbuz"/></linearGradient><linearGradient id="i57tOnt" x1="12.195" x2="7.32" y1="16.281" y2="16.281" gradientUnits="userSpaceOnUse"><stop class="fatndpbme"/><stop offset="1" class="gm2_mnbjs"/></linearGradient><linearGradient id="iIhKvrc" x1="7.945" x2="8.507" y1="20" y2="15.938" gradientUnits="userSpaceOnUse"><stop class="jgxf0mb8j"/><stop offset=".902" class="e-nyzdcdb"/></linearGradient><linearGradient id="iq8ofac" x1="-1.805" x2="12.195" y1="-.875" y2="20.688" gradientUnits="userSpaceOnUse"><stop offset=".844" class="e-nyzdcdb"/><stop offset=".997" class="jgxf0mb8j"/></linearGradient><linearGradient id="iXOUPqc" x1="2.601" x2="2.79" y1="14.875" y2="16.703" gradientUnits="userSpaceOnUse"><stop class="ywsfy6m9x"/><stop offset="1" class="jsot_71pz"/></linearGradient><linearGradient id="ipJTa2V" x1="15.726" x2="15.648" y1="11.469" y2="10" gradientUnits="userSpaceOnUse"><stop class="kiwroxerl"/><stop offset="1" class="n93-yebyr"/></linearGradient><linearGradient id="iEOHtZd" x1="12.039" x2="14.289" y1="10.875" y2="10.844" gradientUnits="userSpaceOnUse"><stop class="fatndpbme"/><stop offset="1" class="gm2_mnbjs"/></linearGradient><linearGradient id="if464Me" x1="11.507" x2="19.757" y1="9.312" y2="8.625" gradientUnits="userSpaceOnUse"><stop class="h33vfjfoc"/><stop offset="1" class="m7kjiplhc"/></linearGradient><linearGradient id="iPhdbBd" x1="16.07" x2="16.07" y1="10.094" y2="8.75" gradientUnits="userSpaceOnUse"><stop class="x50haab-b"/><stop offset="1" class="vq_vnvb6e"/></linearGradient><linearGradient id="icf94te" x1="13.614" x2="13.614" y1="11.876" y2="14.924" gradientUnits="userSpaceOnUse"><stop class="f9lbf8blm"/><stop offset="1" class="q2sk3g_gm"/></linearGradient><linearGradient id="ikAKflw" x1="21.539" x2="20.679" y1="7.031" y2="7.813" gradientUnits="userSpaceOnUse"><stop offset=".057" class="z98quqa1o"/><stop offset="1" class="q2sk3g_gm"/></linearGradient><linearGradient id="iqlSlEe" x1="7.203" x2="6.363" y1="7.894" y2="9.323" gradientUnits="userSpaceOnUse"><stop offset=".057" class="f9lbf8blm"/><stop offset="1" class="q2sk3g_gm"/><stop offset="1" class="q2sk3g_gm"/></linearGradient><linearGradient id="iBa3jvb" x1="14.295" x2="13.108" y1="25.711" y2="26.117" gradientUnits="userSpaceOnUse"><stop offset=".057" class="ub05spv7w"/><stop offset="1" class="q2sk3g_gm"/><stop offset="1" class="q2sk3g_gm"/></linearGradient><linearGradient id="i56ESob" x1="25.817" x2="24.774" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="f9lbf8blm"/><stop offset="1" class="q2sk3g_gm"/></linearGradient><radialGradient id="iPG02jd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40624 -.96877 .69018 -1.71429 25.289 13.281)" gradientUnits="userSpaceOnUse"><stop class="au8s6jx-n"/><stop offset=".83" class="pq-2w2bni"/></radialGradient><radialGradient id="ibck4ux" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89063 2.71874 -2.74411 -1.90827 9.554 17.297)" gradientUnits="userSpaceOnUse"><stop class="hiqkagb3k"/><stop offset="1" class="a531y7b9b"/></radialGradient><radialGradient id="i2M1ZKX" cx="0" cy="0" r="1" gradientTransform="rotate(-164.438 11.6 10.32)scale(5.12538 6.37959)" gradientUnits="userSpaceOnUse"><stop class="cn0kyns1c"/><stop offset=".968" class="n25ukpqsw"/></radialGradient><radialGradient id="iB8StUd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.37501 3.43748 -3.5611 -4.53235 29.132 12.563)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="kuot97fmj"/><stop offset=".668" class="jy328kbdg"/><stop offset="1" class="odebtccyv"/></radialGradient><radialGradient id="iVWdKGb" cx="0" cy="0" r="1" gradientTransform="rotate(-101.031 21.922 -2.69)scale(8.8192 5.66768)" gradientUnits="userSpaceOnUse"><stop offset=".804" class="dbi1ugn_j"/><stop offset="1" class="odebtccyv"/></radialGradient><radialGradient id="ihaCSjA" cx="0" cy="0" r="1" gradientTransform="matrix(2.23482 .52456 -.95074 4.0505 24.078 13.638)" gradientUnits="userSpaceOnUse"><stop class="odebtccyv"/><stop offset="1" class="dbi1ugn_j"/></radialGradient><radialGradient id="imrMO1b" cx="0" cy="0" r="1" gradientTransform="rotate(26.35 -14.575 58.943)scale(2.14472 4.41205)" gradientUnits="userSpaceOnUse"><stop class="lvda8uous"/><stop offset=".357" class="sqmrghbhm"/></radialGradient><radialGradient id="iR7KGPe" cx="0" cy="0" r="1" gradientTransform="translate(5.385 12.135)scale(20.1393)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></radialGradient><radialGradient id="ic1d96d" cx="0" cy="0" r="1" gradientTransform="rotate(-39.8 17.499 -8.42)scale(10.362 5.02976)" gradientUnits="userSpaceOnUse"><stop offset=".948" class="fadiuybiu"/><stop offset="1" class="t8ut0kb3z"/></radialGradient><radialGradient id="iEkTlxb" cx="0" cy="0" r="1" gradientTransform="matrix(7.93751 -6.6719 2.45583 2.92169 9.445 9.25)" gradientUnits="userSpaceOnUse"><stop offset=".966" class="wi3f89tni"/><stop offset="1" class="fy8ov2q3l"/></radialGradient><radialGradient id="in4wUxJ" cx="0" cy="0" r="1" gradientTransform="rotate(136.848 8.703 4.869)scale(4.1122 4.42373)" gradientUnits="userSpaceOnUse"><stop class="w5zu9bbxm"/><stop offset="0" class="t66gsfbqy"/><stop offset="1" class="ll8olt71l"/></radialGradient><radialGradient id="i1LTK5c" cx="0" cy="0" r="1" gradientTransform="rotate(-123.265 21.093 11.697)scale(9.34349 8.78037)" gradientUnits="userSpaceOnUse"><stop class="rn_358bir"/><stop offset="1" class="i9lfkzbcw"/></radialGradient><radialGradient id="i5quz3f" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 2.6875 -1.80805 -3.11154 28.57 20)" gradientUnits="userSpaceOnUse"><stop class="nadv8kbas"/><stop offset=".859" class="et28x0bjs"/></radialGradient><radialGradient id="i5pUdte" cx="0" cy="0" r="1" gradientTransform="matrix(1.90035 -.84375 .77846 1.7533 1.601 16.172)" gradientUnits="userSpaceOnUse"><stop offset=".763" class="td_bh-bfs"/><stop offset="1" class="klxmqvbfb"/></radialGradient><radialGradient id="iZpb5Ge" cx="0" cy="0" r="1" gradientTransform="rotate(134.549 9.55 7.6)scale(2.80642 6.31681)" gradientUnits="userSpaceOnUse"><stop class="jhw8u1_lr"/><stop offset="1" class="vm-zowbtz"/></radialGradient><radialGradient id="iumJlDd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.25562 4.82806 -2.63368 -4.5034 20.507 5)" gradientUnits="userSpaceOnUse"><stop offset=".925" class="s8b70abhu"/><stop offset="1" class="ot44suv_o"/></radialGradient><radialGradient id="iVMgfAg" cx="0" cy="0" r="1" gradientTransform="matrix(11.7187 -2.90623 1.57343 6.3445 9.914 10.906)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="rszv48b_w"/><stop offset="1" class="k9ld7vlnk"/></radialGradient><radialGradient id="iejZEzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.41159 .56988 -.50807 -.36695 7.375 12.987)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="icFzIvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.22162 .30077 -.25354 -.18682 7.391 13.042)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><filter id="i528slb" width="23.97" height="19" x="7.225" y="10.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.654902 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3886"/></filter><filter id="itFJsxe" width="18.161" height="16.344" x="11.213" y="11.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3886" stdDeviation="1"/></filter><filter id="iIPbPzm" width="14.414" height="8.953" x="14.195" y="20.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.684551 0 0 0 0 0.639167 0 0 0 0 0.7375 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3886"/></filter><filter id="iZDUxbb" width="20.8" height="12.807" x="2.195" y="5.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.731183 0 0 0 0 0.689427 0 0 0 0 0.7625 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3886"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.883333 0 0 0 0 0.883333 0 0 0 0 0.883333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_3886" result="effect2_innerShadow_28327_3886"/></filter><filter id="iId1g4b" width="4.237" height="7.688" x="11.101" y="9.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3886" stdDeviation=".5"/></filter><filter id="i6qgmue" width="2.306" height="2.462" x="19.792" y="6.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3886" stdDeviation=".125"/></filter><filter id="iAfzRjd" width="2.758" height="3.086" x="4.838" y="7.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3886" stdDeviation=".2"/></filter><filter id="imkLapd" width="2.211" height="4.58" x="12.589" y="24.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3886" stdDeviation=".2"/></filter><filter id="imMEsvb" width="4.625" height="8.25" x="23.007" y="20.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3886" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rabbit" /></template>
<style>
.a531y7b9b {
  stop-color: var(--svg-color--af9bc4, #AF9BC4);
  stop-opacity: 0;
}

.absh5cxna {
  d: path("M27.506 16.672a3 3 0 1 0-3.294-3.303a7 7 0 0 0-3.017-.681h-13l.09 3h.94v11.4c0 .33-.275.59-.591.69a2.01 2.01 0 0 0-1.41 1.91h5.07c.55 0 1.04-.35 1.22-.88l.71-2.12h6.97c2.56 0 4.606-1.21 5.836-3.26a1 1 0 0 0 .05-.08a4 4 0 0 0 .255-.496l.015-.035q.022-.044.04-.085l.04-.085l.02-.05l.01-.03q.016-.044.035-.085q.02-.04.035-.085l.015-.04l.015-.04c.02-.06.04-.12.07-.18c.01-.02.02-.05.02-.07l.035-.11q.02-.056.035-.11c.19-.63.522-1.128.522-2.16c0-.69-.147-1.37-.337-2l-.035-.115q-.02-.055-.035-.114a.2.2 0 0 1-.02-.07c-.02-.06-.04-.12-.07-.18l-.015-.04l-.015-.04a1 1 0 0 0-.07-.17c-.01-.03-.02-.06-.04-.08a.8.8 0 0 0-.08-.16a.3.3 0 0 0-.02-.046");
}

.au8s6jx-n {
  stop-color: var(--svg-color--aba9ac, #ABA9AC);
}

.b7syu2g4q {
  d: path("m19.605 5.888l-10.41.8c-2.48.19-4.52 1.44-5.46 3.51c-.05.11-.1.23-.15.35l-1.05 2.53c-.23.53-.34 1.11-.34 1.69c0 2.16 1.76 3.92 3.92 3.92h3.28c3.22-.1 5.8-2.75 5.8-6c0-.7-.12-1.37-.34-2h4.94a2.404 2.404 0 1 0-.19-4.8");
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cd3a-xh0u {
  d: path("M22.742 26.53v-3.218h-7.547l-.97 3.375h6.97q.81 0 1.547-.157");
}

.cn0kyns1c {
  stop-color: var(--svg-color--baadc9, #BAADC9);
}

.d1rht2bjk {
  d: path("m16.675 6.177l-9.18 5.29l-2-3.46l8.62-5.9c1.16-.79 2.74-.43 3.44.78c.66 1.15.27 2.62-.88 3.29");
}

.dbi1ugn_j {
  stop-color: var(--svg-color--c0bbc3, #C0BBC3);
  stop-opacity: 0;
}

.dcze57b7u {
  stop-color: var(--svg-color--9180a2, #9180A2);
  stop-opacity: 0;
}

.e-nyzdcdb {
  stop-color: var(--svg-color--ae8ecd, #AE8ECD);
  stop-opacity: 0;
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ekw8a3eot {
  d: path("M2.47 14.65a1 1 0 0 0-.234.03a.21.21 0 0 0-.155.22c.024.599.177 1.16.433 1.658a.21.21 0 0 0 .242.113c.434-.124.745-.52.745-.99c0-.567-.453-1.031-1.031-1.031");
}

.et28x0bjs {
  stop-color: var(--svg-color--e8e2ef, #E8E2EF);
  stop-opacity: 0;
}

.f_gcs9bph {
  fill: var(--svg-color--d2cbd5, #D2CBD5);
  d: path("m16.675 6.177l-9.18 5.29l-2-3.46l8.62-5.9c1.16-.79 2.74-.43 3.44.78c.66 1.15.27 2.62-.88 3.29");
}

.f9lbf8blm {
  stop-color: var(--svg-color--e0d6ed, #E0D6ED);
}

.fadiuybiu {
  stop-color: var(--svg-color--faf1ff, #FAF1FF);
  stop-opacity: 0;
}

.fatndpbme {
  stop-color: var(--svg-color--cdc0da, #CDC0DA);
}

.fo1ixmb2i {
  d: path("M7.225 13.656a.507.507 0 1 0 0-1.013a.507.507 0 0 0 0 1.013");
}

.ft5dv1b6b {
  fill: none;
}

.fy8ov2q3l {
  stop-color: var(--svg-color--d2cbd5, #D2CBD5);
}

.g_r7gubhh {
  fill: var(--svg-color--cdc0da, #CDC0DA);
  d: path("m19.605 5.888l-10.41.8c-2.48.19-4.52 1.44-5.46 3.51c-.05.11-.1.23-.15.35l-1.05 2.53c-.23.53-.34 1.11-.34 1.69c0 2.16 1.76 3.92 3.92 3.92h3.28c3.22-.1 5.8-2.75 5.8-6c0-.7-.12-1.37-.34-2h4.94a2.404 2.404 0 1 0-.19-4.8");
}

.g4ir5_irg {
  stop-color: var(--svg-color--9180a2, #9180A2);
}

.gm2_mnbjs {
  stop-color: var(--svg-color--cdc0da, #CDC0DA);
  stop-opacity: 0;
}

.guzjm2jhl {
  d: path("M11.685 10.688h8.111a2.404 2.404 0 1 0-.191-4.8l-7.92.608z");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h33vfjfoc {
  stop-color: var(--svg-color--d55f78, #D55F78);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hiqkagb3k {
  stop-color: var(--svg-color--af9bc4, #AF9BC4);
}

.hjezcrbuz {
  stop-color: var(--svg-color--c6b7d5, #C6B7D5);
  stop-opacity: 0;
}

.hwl-htb3l {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.117 6.406c.5.026 1.5.485 1.656 1.813");
}

.i4lalcbtz {
  d: path("M19.795 6.877h-.11l-5.27.41a2.4 2.4 0 0 0-2.15 1.83c-.07.29.15.57.44.57h7.04c.76 0 1.41-.59 1.44-1.35c.04-.8-.6-1.46-1.39-1.46");
}

.i66sqmxxb {
  stop-color: var(--svg-color--c1bec2, #C1BEC2);
  stop-opacity: 0;
}

.i9lfkzbcw {
  stop-color: var(--svg-color--9c69cc, #9C69CC);
  stop-opacity: 0;
}

.inkr_6bmh {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.963 14.65h6.945c1.479 0 2.9.573 3.965 1.6v0a5.72 5.72 0 0 1 1.536 5.668l-1.008 3.576");
}

.jgxf0mb8j {
  stop-color: var(--svg-color--ae8ecd, #AE8ECD);
}

.jhw8u1_lr {
  stop-color: var(--svg-color--dcd4df, #DCD4DF);
}

.jsot_71pz {
  stop-color: var(--svg-color--d56586, #D56586);
}

.jy328kbdg {
  stop-color: var(--svg-color--cdbfdb, #CDBFDB);
}

.k7syk3brx {
  stop-color: var(--svg-color--9d7fb8, #9D7FB8);
}

.k9ld7vlnk {
  stop-color: var(--svg-color--b63a4d, #B63A4D);
}

.kiwroxerl {
  stop-color: var(--svg-color--b090ce, #B090CE);
}

.klxmqvbfb {
  stop-color: var(--svg-color--e68e97, #E68E97);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kuot97fmj {
  stop-color: var(--svg-color--f2eaf6, #F2EAF6);
}

.ll8olt71l {
  stop-color: var(--svg-color--ede9ef, #EDE9EF);
  stop-opacity: 0.083;
}

.lvda8uous {
  stop-color: var(--svg-color--d6d3d8, #D6D3D8);
}

.m-c_d-rde {
  stop-color: var(--svg-color--c1bec2, #C1BEC2);
}

.m7kjiplhc {
  stop-color: var(--svg-color--d26777, #D26777);
}

.mevictbbm {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m26.257 21.906l-1.875 5.5");
}

.mie1mbc7w {
  d: path("m28.109 20.734l-5.074.024c-2.969 0-5.75 1.76-5.83 4.77v1.85c0 .17-.14.31-.31.31h-.7c-1.1 0-2 .9-2 2h7.97a4.23 4.23 0 0 0 4-2.87z");
}

.msh0b0bmy {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m14.225 25.21l-1.061 3.43");
}

.n25ukpqsw {
  stop-color: var(--svg-color--baadc9, #BAADC9);
  stop-opacity: 0;
}

.n93-yebyr {
  stop-color: var(--svg-color--b090ce, #B090CE);
  stop-opacity: 0;
}

.nadv8kbas {
  stop-color: var(--svg-color--e8e2ef, #E8E2EF);
}

.o90bthbyb {
  stop-color: var(--svg-color--cec1da, #CEC1DA);
}

.odebtccyv {
  stop-color: var(--svg-color--c0bbc3, #C0BBC3);
}

.ot44suv_o {
  stop-color: var(--svg-color--e7878e, #E7878E);
}

.pq-2w2bni {
  stop-color: var(--svg-color--aba9ac, #ABA9AC);
  stop-opacity: 0;
}

.q2sk3g_gm {
  stop-color: var(--svg-color--e0d6ed, #E0D6ED);
  stop-opacity: 0;
}

.q5bhxbkvc {
  stop-color: var(--svg-color--cac1ce, #CAC1CE);
}

.qoeernbaz {
  stop-color: var(--svg-color--cfc7d1, #CFC7D1);
  stop-opacity: 0;
}

.qq07jh8ff {
  stop-color: var(--svg-color--bdadcd, #BDADCD);
}

.r6qd37uwh {
  stop-color: var(--svg-color--cac1ce, #CAC1CE);
  stop-opacity: 0;
}

.rlti5mboa {
  stop-color: var(--svg-color--9d7fb8, #9D7FB8);
  stop-opacity: 0;
}

.rn_358bir {
  stop-color: var(--svg-color--9c69cc, #9C69CC);
}

.rszv48b_w {
  stop-color: var(--svg-color--d6586c, #D6586C);
  stop-opacity: 0;
}

.s8b70abhu {
  stop-color: var(--svg-color--e7878e, #E7878E);
  stop-opacity: 0;
}

.sqmrghbhm {
  stop-color: var(--svg-color--d6d3d8, #D6D3D8);
  stop-opacity: 0;
}

.st7_5ybbw {
  stop-color: var(--svg-color--c6b7d5, #C6B7D5);
}

.t66gsfbqy {
  stop-color: var(--svg-color--ede9ef, #EDE9EF);
}

.t8ut0kb3z {
  stop-color: var(--svg-color--faf1ff, #FAF1FF);
}

.td_bh-bfs {
  stop-color: var(--svg-color--e68e97, #E68E97);
  stop-opacity: 0;
}

.tyey3acxy {
  d: path("M25.273 15.438c1.166 1.177 2.313 1.828 4.033.381a3 3 0 1 0-4.222-4.263c-1.368 1.355-.977 2.704.189 3.882");
}

.ub05spv7w {
  stop-color: var(--svg-color--e0d6ed, #E0D6ED);
  stop-opacity: 0.5;
}

.vm-zowbtz {
  stop-color: var(--svg-color--dcd4df, #DCD4DF);
  stop-opacity: 0;
}

.vq_vnvb6e {
  stop-color: var(--svg-color--d46d75, #D46D75);
  stop-opacity: 0;
}

.w5zu9bbxm {
  stop-color: var(--svg-color--ede9ef, #EDE9EF);
  stop-opacity: 0;
}

.wi3f89tni {
  stop-color: var(--svg-color--d2cbd5, #D2CBD5);
  stop-opacity: 0;
}

.x-4n1sbgs {
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  d: path("m16.675 6.177l-9.18 5.29l-2-3.46l8.62-5.9c1.16-.79 2.74-.43 3.44.78c.66 1.15.27 2.62-.88 3.29");
}

.x50haab-b {
  stop-color: var(--svg-color--d46d75, #D46D75);
}

.x8v-wmb8s {
  fill: var(--svg-color--c6b7d5, #C6B7D5);
  d: path("m28.109 20.734l-5.074.024c-2.969 0-5.75 1.76-5.83 4.77v1.85c0 .17-.14.31-.31.31h-.7c-1.1 0-2 .9-2 2h7.97a4.23 4.23 0 0 0 4-2.87z");
}

.xyygu9b1d {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M13.625 10.688c.425 1.087.79 3.596-1.149 4.937");
}

.ya1f_8b2z {
  stop-color: var(--svg-color--cfc7d1, #CFC7D1);
}

.ywsfy6m9x {
  stop-color: var(--svg-color--d66f77, #D66F77);
}

.z98quqa1o {
  stop-color: var(--svg-color--ede7f4, #EDE7F4);
}

.zda8kp16s {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M5.413 9.578c.005-.45.333-1.469 1.608-1.937");
}

</style>
