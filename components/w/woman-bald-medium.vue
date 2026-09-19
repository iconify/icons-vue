<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVlbzbe)"><path fill="url(#iZEe8Fe)" class="ncy9bqbkn"/></g><g filter="url(#ie59tZq)"><path fill="url(#iRvbSQl)" class="x94480byg"/><path fill="url(#ijfWl6c)" class="x94480byg"/></g><g filter="url(#iwXq3Mb)"><path class="j_el38b9n"/><path fill="url(#iTsmORb)" class="r43deen9f"/></g><g filter="url(#ictdEud)"><path class="r-9eh5bcx"/><path fill="url(#iBYbCIb)" class="lfw1shxwz"/></g><g filter="url(#ikni43s)"><path fill="url(#i06Qg4d)" class="k9h7vnu-y"/><path fill="url(#igf69nt)" class="k9h7vnu-y"/><path fill="url(#i2XP3vb)" class="k9h7vnu-y"/><path fill="url(#ibrXEjd)" class="k9h7vnu-y"/><path fill="url(#ijjv8ue)" class="k9h7vnu-y"/><path fill="url(#iw8ob4c)" class="k9h7vnu-y"/><path fill="url(#iVUkT6c)" class="k9h7vnu-y"/></g><g filter="url(#itnHGbb)"><path class="y3qzyev9r"/></g><path class="ffof_ivbs"/><path fill="url(#iapgMOl)" class="bjqa6l_2a"/><path fill="url(#i5WetXb)" class="bjqa6l_2a"/><path fill="url(#iiuWzkc)" class="bjqa6l_2a"/><path fill="url(#i30l4zb)" class="bjqa6l_2a"/><path fill="url(#iyZlQzb)" class="bjqa6l_2a"/><path fill="url(#imBjGAe)" class="bjqa6l_2a"/><path stroke="url(#iV9W65s)" class="q461gmbkw"/><g filter="url(#ifafVSd)"><path class="cclflvwog"/></g><g filter="url(#i20q0ib)"><path class="tcl3yxb0x"/></g><path class="hqp389grr"/><path fill="url(#iwi4h1c)" class="szry8ybac"/><path class="kdei44q3v"/><g filter="url(#ikcRo0b)"><path class="ky1l4bg6x"/><path fill="url(#i7uof9c)" class="c1p0_uefu"/></g><g filter="url(#iSM2M1d)"><path fill="url(#iVE6cIa)" class="j7in6hkox"/></g><path class="u_w-dpb5a"/><path fill="url(#iB6um3d)" class="o90amr4pw"/><path class="ycgryjbjh"/><g filter="url(#iObvwqc)"><path fill="url(#iutD35c)" class="s63wcy6_y"/></g><g filter="url(#ieq46gc)"><ellipse transform="rotate(-27.914 11.478 16.624)" class="xsy-02zfw"/><ellipse fill="url(#iB0afFc)" transform="rotate(-27.914 11.478 16.624)" class="m4pbfdb7q"/></g><g filter="url(#imuuzTd)"><path fill="url(#iplwALb)" class="zx4jrhbsj"/></g><g filter="url(#i2iItZb)"><path class="wcw_63ygg"/></g><g filter="url(#iviCEih)"><path clip-rule="evenodd" class="lhv9y7bzt"/></g><g filter="url(#iPBASne)"><path class="z319e1bdv"/></g><g filter="url(#iYqxj8b)"><path class="ieym7ob7b"/></g><defs><radialGradient id="iRvbSQl" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 55.036 -45.07)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="ijfWl6c" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 0 0 .96875 25.271 14.734)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iTsmORb" cx="0" cy="0" r="1" gradientTransform="matrix(2.81506 -.2094 .1637 2.2006 24.24 18.125)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iBYbCIb" cx="0" cy="0" r="1" gradientTransform="rotate(-180 3.737 8.958)scale(1.96875)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="i06Qg4d" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7736 5.48461 -6.56529 -14.09343 21.313 15.919)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="b5g_dkyzh"/><stop offset="1" class="us5ghnb_y"/></radialGradient><radialGradient id="igf69nt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.375 2.51563 0 12.281 16.013)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="lpfb1vb-o"/><stop offset="1" class="lntde0blj"/></radialGradient><radialGradient id="i2XP3vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81248 -2 2.66668 -1.08331 20.188 15.919)" gradientUnits="userSpaceOnUse"><stop class="jo2v4l1-j"/><stop offset="1" class="jj6ff-bnb"/></radialGradient><radialGradient id="ibrXEjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.03125 -1.93296 0 11.781 17.575)" gradientUnits="userSpaceOnUse"><stop class="s72udxbeu"/><stop offset="1" class="moelwiuzg"/></radialGradient><radialGradient id="ijjv8ue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93756 15.94082 -15.66152 -4.85104 19.188 13.106)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="oy5pvp6fc"/><stop offset="1" class="bhm5c331u"/></radialGradient><radialGradient id="iw8ob4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.9375 -4.04687 0 17.5 4.169)" gradientUnits="userSpaceOnUse"><stop class="bcgtg7bvy"/><stop offset="1" class="a0nd18k4m"/></radialGradient><radialGradient id="iVUkT6c" cx="0" cy="0" r="1" gradientTransform="rotate(56.622 -.187 11.366)scale(8.40363 11.4711)" gradientUnits="userSpaceOnUse"><stop class="gjvikqbom"/><stop offset="1" class="urg7j3p-g"/></radialGradient><radialGradient id="iapgMOl" cx="0" cy="0" r="1" gradientTransform="matrix(-.84932 -3.81088 1.17448 -.26175 17.515 20.262)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="i30l4zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45312 0 0 -.40625 17.068 20.656)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="imBjGAe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5565 1.75513 -2.1094 -3.07252 16.755 19.547)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="iwi4h1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 20.12 16.802)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7uof9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.695 16.96)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iB6um3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.984 16.802)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iB0afFc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.197 2.97)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iVlbzbe" width="6.15" height="6" x="4.316" y="14.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19251"/></filter><filter id="ie59tZq" width="6" height="6.25" x="22.052" y="14.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19251"/></filter><filter id="iwXq3Mb" width="5.005" height="5.005" x="22.55" y="15.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".25"/></filter><filter id="ictdEud" width="4.705" height="4.705" x="5" y="15.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".175"/></filter><filter id="ikni43s" width="19.853" height="24.601" x="6.699" y="4.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy=".25"/><feGaussianBlur stdDeviation=".875"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.447059 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19251"/></filter><filter id="itnHGbb" width="4.5" height="5.719" x="13.423" y="16.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".25"/></filter><filter id="ifafVSd" width="5.423" height="2.397" x="17.982" y="15.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19251"/></filter><filter id="i20q0ib" width="5.423" height="2.397" x="8.7" y="15.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19251"/></filter><filter id="ikcRo0b" width="1.294" height="1.125" x="18.838" y="16.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".05"/></filter><filter id="iSM2M1d" width="1.316" height="1.357" x="20.491" y="16.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".1"/></filter><filter id="iObvwqc" width="1.493" height="1.594" x="12.207" y="16.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".1"/></filter><filter id="ieq46gc" width="1.529" height="1.141" x="10.713" y="16.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".05"/></filter><filter id="imuuzTd" width="12.86" height="11.918" x="14.098" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation="1.25"/></filter><filter id="i2iItZb" width="4.4" height="1.861" x="8.952" y="12.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19251"/></filter><filter id="iviCEih" width="4.4" height="1.861" x="19.052" y="12.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19251"/></filter><filter id="iPBASne" width="4.296" height="1.904" x="19.068" y="12.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".2"/></filter><filter id="iYqxj8b" width="4.296" height="1.904" x="8.904" y="12.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19251" stdDeviation=".2"/></filter><linearGradient id="iZEe8Fe" x1="4.316" x2="7.779" y1="18.078" y2="18.078" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i5WetXb" x1="14.302" x2="16.052" y1="20.398" y2="20.398" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iiuWzkc" x1="16.052" x2="16.052" y1="21.716" y2="20.547" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iyZlQzb" x1="16.198" x2="16.198" y1="21.838" y2="21.578" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iV9W65s" x1="14.068" x2="14.927" y1="24.516" y2="23.188" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iVE6cIa" x1="21.571" x2="20.986" y1="16.903" y2="17.263" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iutD35c" x1="13.371" x2="12.786" y1="16.903" y2="17.263" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iplwALb" x1="19.591" x2="25.45" y1="12.367" y2="5.054" gradientUnits="userSpaceOnUse"><stop class="c3frvkbxg"/><stop offset="1" class="jw1j8wrph"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bald-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a0nd18k4m {
  stop-color: var(--svg-color--ac917a, #AC917A);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.b5g_dkyzh {
  stop-color: var(--svg-color--c4967b, #C4967B);
}

.bcgtg7bvy {
  stop-color: var(--svg-color--ac917a, #AC917A);
}

.bhm5c331u {
  stop-color: var(--svg-color--9d5d8e, #9D5D8E);
}

.bjqa6l_2a {
  d: path("m15.34 17.242l-.992 3.17a1.005 1.005 0 0 0 .971 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.c1p0_uefu {
  d: path("M20.002 16.265c.118.158-.13.352-.411.562c-.282.21-.49.36-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

.c3frvkbxg {
  stop-color: var(--svg-color--cba28d, #CBA28D);
}

.cclflvwog {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M18.182 16.855c.494-.87 1.247-1.558 2.866-1.558c.709 0 1.392.196 2 .687c.501.405.434.924.046 1.118l-1.037.591c-1.215-.392-2.559-.446-3.875-.838");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.ffof_ivbs {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.34 17.242l-.992 3.17a1.005 1.005 0 0 0 .971 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.ft5dv1b6b {
  fill: none;
}

.gjvikqbom {
  stop-color: var(--svg-color--8e725d, #8E725D);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hqp389grr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.51 15.406c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.159a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.ieym7ob7b {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.6 13.492c-.6-.146-2.096-.073-3.096.642");
}

.j_el38b9n {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M25.052 19.918a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j7in6hkox {
  d: path("M21.606 17.358a1.57 1.57 0 0 0-.431-.863l-.485.532l.22.425z");
}

.jj6ff-bnb {
  stop-color: var(--svg-color--ae7a74, #AE7A74);
  stop-opacity: 0;
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo2v4l1-j {
  stop-color: var(--svg-color--ae7a74, #AE7A74);
}

.jw1j8wrph {
  stop-color: var(--svg-color--cba28d, #CBA28D);
  stop-opacity: 0;
}

.k9h7vnu-y {
  d: path("M6.699 20.314c.23 5.225 4.31 8.733 9.29 8.733c4.981 0 9.061-3.508 9.291-8.733l.021-8.722c0-3.3-2.057-5.92-6.3-6.736c-1.6-.211-4.5-.214-6 0c-4.242.816-6.3 3.435-6.3 6.736z");
}

.kdei44q3v {
  fill: var(--svg-color--000, #000);
  d: path("M19.171 17.577c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.114-.44");
}

.ky1l4bg6x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.002 16.265c.118.158-.13.352-.411.562c-.282.21-.49.36-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lfw1shxwz {
  d: path("M7.352 19.918a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.lhv9y7bzt {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m23.01 13.748l-.258.429za.5.5 0 0 1-.514.859l-.008-.005l-.04-.023a5 5 0 0 0-.809-.338c-.542-.172-1.255-.302-1.999-.17a.5.5 0 0 1-.174-.985c.957-.17 1.843 0 2.477.203a6 6 0 0 1 .98.411q.04.02.061.034l.018.01l.005.003z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lntde0blj {
  stop-color: var(--svg-color--8d5c64, #8D5C64);
  stop-opacity: 0;
}

.lpfb1vb-o {
  stop-color: var(--svg-color--8d5c64, #8D5C64);
}

.m4pbfdb7q {
  cx: 11.478px;
  cy: 16.624px;
  rx: 0.726px;
  ry: 0.368px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.moelwiuzg {
  stop-color: var(--svg-color--9e7766, #9E7766);
  stop-opacity: 0;
}

.ncy9bqbkn {
  d: path("M7.316 20.916a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.o90amr4pw {
  d: path("M11.98 15.913a1.664 1.664 0 0 0-1.603 2.103h3.214q.058-.214.06-.44a1.675 1.675 0 0 0-1.67-1.663");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oy5pvp6fc {
  stop-color: var(--svg-color--9d5d8e, #9D5D8E);
  stop-opacity: 0;
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q461gmbkw {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.425 22.657a.34.34 0 0 0-.41.072a.32.32 0 0 0-.034.409a3.65 3.65 0 0 0 3.071 1.678a3.65 3.65 0 0 0 3.071-1.679a.33.33 0 0 0-.034-.412a.34.34 0 0 0-.41-.068a5.6 5.6 0 0 1-2.627.637a5.6 5.6 0 0 1-2.627-.637Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-9eh5bcx {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M7.352 19.918a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.r43deen9f {
  d: path("M25.052 19.918a2.003 2.003 0 1 0 0-4.005a2.003 2.003 0 0 0 0 4.005");
}

.s63wcy6_y {
  d: path("M13.5 17.382c0-.538-.437-.897-.555-1.005l-.538.52l.331.674z");
}

.s72udxbeu {
  stop-color: var(--svg-color--9e7766, #9E7766);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.szry8ybac {
  d: path("M20.124 15.913a1.664 1.664 0 0 1 1.604 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tcl3yxb0x {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.923 16.855c-.495-.87-1.247-1.558-2.866-1.558c-.709 0-1.393.196-2 .687c-.501.405-.434.924-.046 1.118l1.037.591c1.215-.392 2.559-.446 3.875-.838");
}

.u_w-dpb5a {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.595 15.406c-1.218 0-2.247.84-2.527 1.974a.51.51 0 0 0 .5.636h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.urg7j3p-g {
  stop-color: var(--svg-color--8e725d, #8E725D);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.us5ghnb_y {
  stop-color: var(--svg-color--997165, #997165);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.wcw_63ygg {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m9.718 14.6l-.008.006h-.001a.5.5 0 0 1-.514-.858h.001l.002-.002l.006-.003l.017-.01l.06-.034a6 6 0 0 1 .98-.411c.635-.202 1.522-.372 2.478-.203a.5.5 0 0 1-.174.984c-.743-.13-1.457-.001-1.998.172a5 5 0 0 0-.85.36");
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.x94480byg {
  d: path("M25.052 20.916a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xsy-02zfw {
  cx: 11.478px;
  cy: 16.624px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.y3qzyev9r {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.244 17.718l-1.274 2.888a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.991-2.888c-.212-.702-.92-.702-1.142 0");
}

.ycgryjbjh {
  fill: var(--svg-color--000, #000);
  d: path("M12.933 17.577a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.038.31.106.439h1.687a.95.95 0 0 0 .113-.44");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.z319e1bdv {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.668 13.492c.602-.146 2.097-.073 3.097.642");
}

.zx4jrhbsj {
  d: path("m17.296 9.271l3.25-3.07c2.938 1.109 3.735 4.062 3.913 5.446l-5.041 1.39a2.227 2.227 0 0 1-2.122-3.766");
}

</style>
