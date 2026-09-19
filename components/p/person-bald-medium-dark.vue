<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJzuh4c)"><path fill="url(#ioERUBb)" class="kucajh8au"/></g><g filter="url(#iYXL3ba)"><path fill="url(#iK8Mkqb)" class="k5zxaccpr"/></g><g filter="url(#iQAzfRc)"><path fill="url(#iCwJcHb)" class="c6k3m1bhn"/><path fill="url(#ix8Zdyb)" class="c6k3m1bhn"/></g><g filter="url(#ijmE8Hd)"><path fill="url(#ifbaPUS)" class="di8l1yblx"/></g><g filter="url(#ir1xR6d)"><path fill="url(#iC8NZWc)" class="bo_6btutb"/><path fill="url(#iN8pERd)" class="bo_6btutb"/><path fill="url(#iXIeAzc)" class="bo_6btutb"/><path fill="url(#ikHx9Vc)" class="bo_6btutb"/><path fill="url(#icZ7KRl)" class="bo_6btutb"/><path fill="url(#ixFZMme)" class="bo_6btutb"/><path fill="url(#iBS6ucd)" class="bo_6btutb"/><path fill="url(#ioKddQd)" class="bo_6btutb"/></g><g filter="url(#iE6SKpd)"><path fill="url(#iuQ8Ibb)" class="w_kracfzs"/></g><g filter="url(#i1gYUfd)"><path class="jwu5g3bcn"/><path fill="url(#iURXubc)" class="k1ao7jbts"/><path fill="url(#iCFbgAe)" class="k1ao7jbts"/><path fill="url(#iUv3Gfb)" class="k1ao7jbts"/><path fill="url(#iudOd8c)" class="k1ao7jbts"/><path fill="url(#i1fWilc)" class="k1ao7jbts"/></g><g filter="url(#iib7Xsb)"><path stroke="url(#i2fXMbc)" class="vmw_irb9y"/></g><path class="hnqjjqb7h"/><g filter="url(#iQtBSHQ)"><path class="g-ewdkb-a"/></g><g filter="url(#iU7aDbc)"><path class="sna7wccsz"/></g><path class="atqfqlphr"/><path fill="url(#ijaDolb)" class="b7ffjfb7q"/><path class="h7c0c7b5k"/><g filter="url(#iK63ESb)"><path fill="url(#ik6Gqid)" class="mx8aigb4b"/></g><g filter="url(#i38PE1b)"><ellipse transform="rotate(-27.914 11.27 15.663)" class="hh9yhccaw"/><ellipse fill="url(#i9T9rSb)" transform="rotate(-27.914 11.27 15.663)" class="l34umybke"/></g><path class="gpo-x8s4n"/><path fill="url(#iBzWYrd)" class="lpcbqrzyv"/><path class="dm21cybez"/><g filter="url(#iuLFFrV)"><path class="d5irs8bop"/><path fill="url(#io2qQPb)" class="q5qi2rbdr"/></g><g filter="url(#id84r9S)"><path fill="url(#ijPjLAb)" class="fofe-abkb"/></g><g filter="url(#iSyvCne)"><path class="epeoc23gb"/></g><g filter="url(#i7z4pwd)"><path class="xrnjbqiae"/></g><g filter="url(#igfB9Pe)"><path fill="url(#ivQEWqb)" class="sd9_4o2-h"/></g><defs><radialGradient id="ioERUBb" cx="0" cy="0" r="1" gradientTransform="matrix(3.15625 0 0 5.09375 3.436 17.27)" gradientUnits="userSpaceOnUse"><stop class="qpc5u4x8h"/><stop offset="1" class="hrcxa3bwu"/></radialGradient><radialGradient id="iK8Mkqb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48723 .21943 -.29636 -2.00865 6.643 17.182)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="e81v169zw"/><stop offset="1" class="pz_p1lmya"/></radialGradient><radialGradient id="ix8Zdyb" cx="0" cy="0" r="1" gradientTransform="rotate(-50.244 30.214 -18.39)scale(2.29666 2.22246)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="k3msex97a"/><stop offset="1" class="ygrwrlqes"/></radialGradient><radialGradient id="iC8NZWc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.13152 18.00003 -16.21274 -4.622 20.451 9.183)" gradientUnits="userSpaceOnUse"><stop class="o5z1w79uy"/><stop offset="1" class="elotk1bpm"/></radialGradient><radialGradient id="iN8pERd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.17105 -8.57064 0 21.872 18.34)" gradientUnits="userSpaceOnUse"><stop class="agzndubcb"/><stop offset="1" class="xvfg4kbme"/></radialGradient><radialGradient id="iXIeAzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.36514 10.5925 0 9.405 28.913)" gradientUnits="userSpaceOnUse"><stop class="mk31bzahg"/><stop offset="1" class="jlyzght3m"/></radialGradient><radialGradient id="ikHx9Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05461 19.43755 -18.9858 -2.98362 18.905 9.801)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="h5qqfq7pe"/><stop offset="1" class="yjft54wef"/></radialGradient><radialGradient id="icZ7KRl" cx="0" cy="0" r="1" gradientTransform="matrix(.56137 -2.91744 3.26223 .62772 11.813 14.469)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="lqb4cab_v"/><stop offset="1" class="y8_3z_b1m"/></radialGradient><radialGradient id="ixFZMme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.91744 3.21246 0 20.28 14.563)" gradientUnits="userSpaceOnUse"><stop offset=".025" class="tfzb8xbux"/><stop offset="1" class="kskg26fiv"/></radialGradient><radialGradient id="iBS6ucd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75 -4.02907 0 17.625 3.719)" gradientUnits="userSpaceOnUse"><stop class="wci4pmb_q"/><stop offset="1" class="sczacobut"/></radialGradient><radialGradient id="ioKddQd" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 6.6875 -9.88813 4.99026 9.096 2.75)" gradientUnits="userSpaceOnUse"><stop class="fkzccdb6u"/><stop offset="1" class="yv_7ag7dw"/></radialGradient><radialGradient id="iCFbgAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.93748 -4.46875 1.47905 -.31028 17.344 19.656)" gradientUnits="userSpaceOnUse"><stop class="tp32gibdm"/><stop offset="1" class="ij06bg9_u"/></radialGradient><radialGradient id="iudOd8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 0 0 -.28125 17.063 19.875)" gradientUnits="userSpaceOnUse"><stop class="kfp246b9o"/><stop offset="1" class="v4uvs797i"/></radialGradient><radialGradient id="ijaDolb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53876 -2.44757 0 11.784 15.844)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="i9T9rSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01467 -.93704 1.12636 -.01764 11.241 16.26)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBzWYrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.914 15.838)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="io2qQPb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.661 3.225)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivQEWqb" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 4.71875 -11.46927 12.00094 17 7.25)" gradientUnits="userSpaceOnUse"><stop class="fjibmkb9z"/><stop offset="1" class="o2s2dpbxk"/></radialGradient><filter id="iJzuh4c" width="6" height="6.2" x="3.846" y="13.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2078"/></filter><filter id="iYXL3ba" width="4.132" height="4.132" x="4.78" y="14.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".125"/></filter><filter id="iQAzfRc" width="6.2" height="6.2" x="21.846" y="13.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.286275 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2078"/></filter><filter id="ijmE8Hd" width="4.632" height="4.632" x="22.733" y="14.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".25"/></filter><filter id="ir1xR6d" width="20.485" height="26.25" x="6.108" y="3.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.5875 0 0 0 0 0.428101 0 0 0 0 0.391667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2078"/></filter><filter id="iE6SKpd" width="4.5" height="5.836" x="13.358" y="15.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".25"/></filter><filter id="i1gYUfd" width="3.7" height="5.2" x="13.996" y="15.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".05"/></filter><filter id="iib7Xsb" width="6.619" height="2.54" x="12.537" y="22.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".075"/></filter><filter id="iQtBSHQ" width="4.424" height="2.097" x="18.809" y="10.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0823529 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2078"/></filter><filter id="iU7aDbc" width="4.424" height="2.069" x="9.009" y="10.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0823529 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2078"/></filter><filter id="iK63ESb" width="1.512" height="1.614" x="12.015" y="15.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".1"/></filter><filter id="i38PE1b" width="1.552" height="1.157" x="10.493" y="15.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".05"/></filter><filter id="iuLFFrV" width="1.294" height="1.125" x="18.632" y="15.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".05"/></filter><filter id="id84r9S" width="1.316" height="1.357" x="20.284" y="15.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".1"/></filter><filter id="iSyvCne" width="4.076" height="1.651" x="9.149" y="11.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".175"/></filter><filter id="i7z4pwd" width="3.97" height="1.737" x="19.087" y="11.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation=".175"/></filter><filter id="igfB9Pe" width="12.281" height="10.228" x="14" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2078" stdDeviation="1"/></filter><linearGradient id="iCwJcHb" x1="26.936" x2="24.846" y1="14.582" y2="19.645" gradientUnits="userSpaceOnUse"><stop class="qy4ie5b3z"/><stop offset="1" class="z16r6xbkx"/></linearGradient><linearGradient id="ifbaPUS" x1="25.83" x2="25.049" y1="16.078" y2="19.219" gradientUnits="userSpaceOnUse"><stop class="nru385bmt"/><stop offset="1" class="te_j-049v"/></linearGradient><linearGradient id="iuQ8Ibb" x1="14.611" x2="15.608" y1="19.287" y2="21.324" gradientUnits="userSpaceOnUse"><stop class="t95r3ob6z"/><stop offset="1" class="n4_tdjrjb"/></linearGradient><linearGradient id="iURXubc" x1="13.655" x2="15.436" y1="19.614" y2="19.926" gradientUnits="userSpaceOnUse"><stop class="jjg-8xbvc"/><stop offset="1" class="z79mj5b1l"/></linearGradient><linearGradient id="iUv3Gfb" x1="15.846" x2="15.846" y1="21.239" y2="19.77" gradientUnits="userSpaceOnUse"><stop class="gao1x89bs"/><stop offset="1" class="fojybzbzm"/></linearGradient><linearGradient id="i1fWilc" x1="15.846" x2="15.846" y1="16.051" y2="17.125" gradientUnits="userSpaceOnUse"><stop class="b4a_4fkzi"/><stop offset="1" class="v69jurkna"/></linearGradient><linearGradient id="i2fXMbc" x1="14.608" x2="15.139" y1="24.321" y2="22.973" gradientUnits="userSpaceOnUse"><stop class="f40hp1bbd"/><stop offset="1" class="i8aar7b0c"/></linearGradient><linearGradient id="ik6Gqid" x1="13.195" x2="12.6" y1="15.947" y2="16.313" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijPjLAb" x1="21.365" x2="20.78" y1="15.938" y2="16.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bald-medium-dark" /></template>
<style>
.agzndubcb {
  stop-color: var(--svg-color--9a6b5e, #9A6B5E);
}

.atqfqlphr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.388 14.424a2.65 2.65 0 0 0-2.57 2.008a.52.52 0 0 0 .508.646h4.232a.436.436 0 0 0 .43-.515a2.66 2.66 0 0 0-2.6-2.139");
}

.b4a_4fkzi {
  stop-color: var(--svg-color--8e625b, #8E625B);
}

.b7ffjfb7q {
  d: path("M11.78 14.94a1.693 1.693 0 0 0-1.63 2.138h3.27q.059-.217.06-.446a1.704 1.704 0 0 0-1.7-1.692");
}

.bo_6btutb {
  d: path("M17.912 3.163h-4.147c-5.57 0-8.018 3.75-7.614 8.71l.7 10.69a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35l.67-10.69c.53-4.703-2.115-8.71-7.615-8.71");
}

.c6k3m1bhn {
  d: path("M24.846 20.051a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d5irs8bop {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.796 15.3c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.di8l1yblx {
  d: path("M25.049 18.867a1.816 1.816 0 1 0 0-3.631a1.816 1.816 0 0 0 0 3.631");
}

.dm21cybez {
  fill: var(--svg-color--000, #000);
  d: path("M18.965 16.613c0-.53.424-.953.953-.953c.53 0 .953.423.953.953a.94.94 0 0 1-.106.438h-1.687a.86.86 0 0 1-.113-.438");
}

.e81v169zw {
  stop-color: var(--svg-color--5b353c, #5B353C);
}

.elotk1bpm {
  stop-color: var(--svg-color--74474f, #74474F);
}

.epeoc23gb {
  stroke: var(--svg-color--453a3b, #453A3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.624 12.209c.408-.303 1.689-.808 3.126-.681");
}

.f40hp1bbd {
  stop-color: var(--svg-color--876163, #876163);
}

.fjibmkb9z {
  stop-color: var(--svg-color--a37d72, #A37D72);
}

.fkzccdb6u {
  stop-color: var(--svg-color--73584e, #73584E);
}

.fofe-abkb {
  d: path("M21.4 16.394a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.fojybzbzm {
  stop-color: var(--svg-color--7b4258, #7B4258);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-ewdkb-a {
  fill: var(--svg-color--302120, #302120);
  d: path("M22.806 11.99c-.327-.284-.707-.585-1.282-.766c-.568-.179-1.278-.227-2.26-.106a.517.517 0 1 0 .125 1.026c.897-.11 1.446-.053 1.824.066c.37.117.62.305.913.56a.517.517 0 0 0 .68-.78");
}

.gao1x89bs {
  stop-color: var(--svg-color--7b4258, #7B4258);
}

.gpo-x8s4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.304 14.442c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.16a.43.43 0 0 1-.423-.506a2.606 2.606 0 0 1 2.557-2.103");
}

.h5qqfq7pe {
  stop-color: var(--svg-color--7f4574, #7F4574);
  stop-opacity: 0;
}

.h7c0c7b5k {
  fill: var(--svg-color--000, #000);
  d: path("M12.75 16.632a.966.966 0 0 0-.97-.97a.966.966 0 0 0-.861 1.416h1.715a.96.96 0 0 0 .116-.446");
}

.hh9yhccaw {
  cx: 11.27px;
  cy: 15.663px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.739px;
  ry: 0.374px;
}

.hnqjjqb7h {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.846 22.94a5.7 5.7 0 0 1-2.634-.625c-.26-.132-.54.161-.376.398a3.6 3.6 0 0 0 3.01 1.608a3.6 3.6 0 0 0 3.01-1.608c.164-.246-.116-.53-.376-.398a5.7 5.7 0 0 1-2.634.625");
}

.hrcxa3bwu {
  stop-color: var(--svg-color--684249, #684249);
}

.i8aar7b0c {
  stop-color: var(--svg-color--876163, #876163);
  stop-opacity: 0;
}

.ij06bg9_u {
  stop-color: var(--svg-color--9f7b70, #9F7B70);
  stop-opacity: 0;
}

.jjg-8xbvc {
  stop-color: var(--svg-color--744c44, #744C44);
}

.jlyzght3m {
  stop-color: var(--svg-color--75405a, #75405A);
  stop-opacity: 0;
}

.jwu5g3bcn {
  fill: var(--svg-color--855d53, #855D53);
  d: path("m15.133 16.578l-.99 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.k1ao7jbts {
  d: path("m15.133 16.578l-.99 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.k3msex97a {
  stop-color: var(--svg-color--7e4c45, #7E4C45);
}

.k5zxaccpr {
  d: path("M6.846 18.867a1.816 1.816 0 1 0 0-3.632a1.816 1.816 0 0 0 0 3.632");
}

.kfp246b9o {
  stop-color: var(--svg-color--9b756f, #9B756F);
}

.kskg26fiv {
  stop-color: var(--svg-color--865454, #865454);
  stop-opacity: 0;
}

.kucajh8au {
  d: path("M6.846 20.051a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.l34umybke {
  cx: 11.27px;
  cy: 15.663px;
  rx: 0.739px;
  ry: 0.374px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpcbqrzyv {
  d: path("M19.918 14.949a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.671-1.664");
}

.lqb4cab_v {
  stop-color: var(--svg-color--70414e, #70414E);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mk31bzahg {
  stop-color: var(--svg-color--75405a, #75405A);
}

.mx8aigb4b {
  d: path("M13.327 16.433c0-.547-.445-.911-.565-1.021l-.547.528l.336.686z");
}

.n4_tdjrjb {
  stop-color: var(--svg-color--733e4f, #733E4F);
}

.nru385bmt {
  stop-color: var(--svg-color--815954, #815954);
}

.o2s2dpbxk {
  stop-color: var(--svg-color--a37d72, #A37D72);
  stop-opacity: 0;
}

.o5z1w79uy {
  stop-color: var(--svg-color--9b7261, #9B7261);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pz_p1lmya {
  stop-color: var(--svg-color--5f3537, #5F3537);
}

.q5qi2rbdr {
  d: path("M19.796 15.3c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.qpc5u4x8h {
  stop-color: var(--svg-color--6b4645, #6B4645);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy4ie5b3z {
  stop-color: var(--svg-color--98746a, #98746A);
}

.s-ceiepmf {
  stop-color: var(--svg-color--654843, #654843);
}

.sczacobut {
  stop-color: var(--svg-color--8b6454, #8B6454);
  stop-opacity: 0;
}

.sd9_4o2-h {
  d: path("m22.813 6.5l-5.269 1.232A2 2 0 0 0 16 9.68v1.747a1 1 0 0 0 .495.863l.572.335a.745.745 0 0 0 1.12-.643c0-.353.25-.658.595-.729l5.5-1.128c0-1.5-1.042-3.208-1.47-3.625");
}

.sna7wccsz {
  fill: var(--svg-color--302120, #302120);
  d: path("M9.487 11.788a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.126 1.026a4.14 4.14 0 0 0-2.585.53a3 3 0 0 0-.171.112l-.005.004a.517.517 0 0 1-.634-.817z");
}

.t95r3ob6z {
  stop-color: var(--svg-color--6e4240, #6E4240);
}

.te_j-049v {
  stop-color: var(--svg-color--7e4d46, #7E4D46);
}

.tfzb8xbux {
  stop-color: var(--svg-color--865454, #865454);
}

.tp32gibdm {
  stop-color: var(--svg-color--9f7b70, #9F7B70);
}

.v4uvs797i {
  stop-color: var(--svg-color--9b756f, #9B756F);
  stop-opacity: 0;
}

.v69jurkna {
  stop-color: var(--svg-color--8e625b, #8E625B);
  stop-opacity: 0;
}

.vmw_irb9y {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.235 22.27a.34.34 0 0 0-.407.071a.31.31 0 0 0-.034.4a3.65 3.65 0 0 0 3.052 1.63a3.65 3.65 0 0 0 3.052-1.63a.314.314 0 0 0-.035-.404a.34.34 0 0 0-.406-.066a5.6 5.6 0 0 1-2.611.619a5.66 5.66 0 0 1-2.611-.62Z");
}

.w_kracfzs {
  d: path("m15.108 17.015l-1.204 3.005a1.005 1.005 0 0 0 .97 1.304h1.467c.687 0 1.173-.662.97-1.304l-1.125-3.005c-.213-.703-.855-.703-1.078 0");
}

.wci4pmb_q {
  stop-color: var(--svg-color--927061, #927061);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xrnjbqiae {
  stroke: var(--svg-color--453a3b, #453A3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.582 12.295c-.5-.484-1.695-.918-3.02-.75");
}

.xvfg4kbme {
  stop-color: var(--svg-color--9a6b5e, #9A6B5E);
  stop-opacity: 0;
}

.y8_3z_b1m {
  stop-color: var(--svg-color--70414e, #70414E);
  stop-opacity: 0;
}

.ygrwrlqes {
  stop-color: var(--svg-color--7e4c45, #7E4C45);
  stop-opacity: 0;
}

.yjft54wef {
  stop-color: var(--svg-color--7f4574, #7F4574);
}

.yv_7ag7dw {
  stop-color: var(--svg-color--73584e, #73584E);
  stop-opacity: 0;
}

.z16r6xbkx {
  stop-color: var(--svg-color--825758, #825758);
}

.z79mj5b1l {
  stop-color: var(--svg-color--744c44, #744C44);
  stop-opacity: 0;
}

</style>
