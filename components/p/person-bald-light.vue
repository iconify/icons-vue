<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixQrLrs)"><path fill="url(#ilaSsjc)" class="kucajh8au"/></g><g filter="url(#idWeXOr)"><path fill="url(#iLTtGRd)" class="k5zxaccpr"/></g><path fill="url(#iGWfLEr)" class="c6k3m1bhn"/><path fill="url(#iRXiKpd)" class="c6k3m1bhn"/><path fill="url(#ivIgiJc)" class="c6k3m1bhn"/><g filter="url(#i5so2Ge)"><path fill="url(#iBSZzMd)" class="di8l1yblx"/></g><g filter="url(#ijWGTNd)"><path fill="url(#iCuVFle)" class="bo_6btutb"/><path fill="url(#ip3QHyc)" class="bo_6btutb"/><path fill="url(#iHSEgUb)" class="bo_6btutb"/><path fill="url(#iYZi0lb)" class="bo_6btutb"/><path fill="url(#iGjIPpd)" class="bo_6btutb"/><path fill="url(#i0QpMhe)" class="bo_6btutb"/><path fill="url(#iV5clXd)" class="bo_6btutb"/></g><path fill="url(#i49Po8c)" class="bo_6btutb"/><g filter="url(#iI1pvvc)"><path class="io54krb-t"/></g><g filter="url(#itzF6Vb)"><path class="qjty43nui"/><path fill="url(#itjZ8Cb)" class="c8vaqsbda"/><path fill="url(#iOZRxvd)" class="c8vaqsbda"/><path fill="url(#ik9HEJd)" class="c8vaqsbda"/><path fill="url(#ivP02ec)" class="c8vaqsbda"/><path fill="url(#ivZpBZb)" class="c8vaqsbda"/></g><g filter="url(#ikpidHd)"><path stroke="url(#iA76rPc)" class="vmw_irb9y"/></g><path class="wxgfgebei"/><g filter="url(#iPvmGAe)"><path class="i53jeobkn"/></g><g filter="url(#iZZVrsd)"><path class="kjbt9bble"/></g><path class="atqfqlphr"/><path fill="url(#ijaDolb)" class="b7ffjfb7q"/><path class="h7c0c7b5k"/><g filter="url(#i54F7ke)"><path fill="url(#ik6Gqid)" class="mx8aigb4b"/></g><g filter="url(#i2HuNxd)"><ellipse transform="rotate(-27.914 11.27 15.663)" class="hh9yhccaw"/><ellipse fill="url(#i9T9rSb)" transform="rotate(-27.914 11.27 15.663)" class="l34umybke"/></g><path class="gpo-x8s4n"/><path fill="url(#iBzWYrd)" class="lpcbqrzyv"/><path class="dm21cybez"/><g filter="url(#i1yLAje)"><path class="d5irs8bop"/><path fill="url(#io2qQPb)" class="q5qi2rbdr"/></g><g filter="url(#iBFvfTb)"><path fill="url(#ijPjLAb)" class="fofe-abkb"/></g><g filter="url(#itos1Nd)"><path class="zyfqcfbru"/></g><g filter="url(#iH8NJVb)"><path class="r_pw-bfon"/></g><g filter="url(#iuMq5Dc)"><path fill="url(#iwFbA0c)" class="sd9_4o2-h"/></g><defs><radialGradient id="iLTtGRd" cx="0" cy="0" r="1" gradientTransform="translate(6.846 17.051)scale(1.81579)" gradientUnits="userSpaceOnUse"><stop class="h_57ad8xy"/><stop offset="1" class="ie_uvmber"/></radialGradient><radialGradient id="iRXiKpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.45364 4.83871 -5.24475 -.49171 24.222 16.243)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ayg4jacub"/><stop offset=".902" class="rbowec_je"/></radialGradient><radialGradient id="ivIgiJc" cx="0" cy="0" r="1" gradientTransform="rotate(-40.756 34.815 -23.876)scale(3.03419 2.74975)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="pv28hhbpl"/><stop offset="1" class="pohux-bmu"/></radialGradient><radialGradient id="iBSZzMd" cx="0" cy="0" r="1" gradientTransform="translate(25.049 17.051)scale(1.81579)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="hgt94i1zu"/><stop offset="1" class="lec_e1qks"/></radialGradient><radialGradient id="iCuVFle" cx="0" cy="0" r="1" gradientTransform="rotate(117.759 8.593 10.636)scale(17.7152 15.9561)" gradientUnits="userSpaceOnUse"><stop class="icd8fhbfu"/><stop offset="1" class="f5f-a4bem"/></radialGradient><radialGradient id="ip3QHyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.17105 -8.57064 0 21.872 18.34)" gradientUnits="userSpaceOnUse"><stop class="g3c2qj6we"/><stop offset="1" class="ae4egub9n"/></radialGradient><radialGradient id="iHSEgUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.36514 10.5925 0 9.405 28.913)" gradientUnits="userSpaceOnUse"><stop class="ufrzmjiom"/><stop offset="1" class="lk0ka18ei"/></radialGradient><radialGradient id="iYZi0lb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05461 19.43755 -18.9858 -2.98362 18.905 9.801)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="lut-i8bzq"/><stop offset="1" class="cz7k6-b_c"/></radialGradient><radialGradient id="iGjIPpd" cx="0" cy="0" r="1" gradientTransform="matrix(.53947 -2.38004 2.66131 .60323 11.789 14.523)" gradientUnits="userSpaceOnUse"><stop class="qj8d7fbft"/><stop offset="1" class="fp9zhfbup"/></radialGradient><radialGradient id="i0QpMhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.91744 3.21246 0 20.28 14.563)" gradientUnits="userSpaceOnUse"><stop offset=".025" class="cg_kaab0n"/><stop offset="1" class="lqro5bhqi"/></radialGradient><radialGradient id="iV5clXd" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 6.125 -9.05643 5.54475 7.938 1)" gradientUnits="userSpaceOnUse"><stop class="k474snbsw"/><stop offset="1" class="l_k5n4ipq"/></radialGradient><radialGradient id="i49Po8c" cx="0" cy="0" r="1" gradientTransform="matrix(3.61765 5.39474 -14.04102 9.41573 8.742 2.591)" gradientUnits="userSpaceOnUse"><stop class="moz8mrdmc"/><stop offset="1" class="v6ix0we7l"/></radialGradient><radialGradient id="itjZ8Cb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.881 16.502 3.018)scale(5.35112 1.41449)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="xvxnt3n-k"/><stop offset="1" class="ns22v9t-w"/></radialGradient><radialGradient id="ivZpBZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37506 -.99653 0 16.626 19.918)" gradientUnits="userSpaceOnUse"><stop class="rdn92bc4r"/><stop offset="1" class="iyyx2kbun"/></radialGradient><radialGradient id="ijaDolb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53876 -2.44757 0 11.784 15.844)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="i9T9rSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01467 -.93704 1.12636 -.01764 11.241 16.26)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBzWYrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.914 15.838)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="io2qQPb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.661 3.225)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwFbA0c" cx="0" cy="0" r="1" gradientTransform="rotate(70.118 5.083 17.85)scale(5.28368 12.8423)" gradientUnits="userSpaceOnUse"><stop class="scjo-lbpq"/><stop offset="1" class="r9hd54buy"/></radialGradient><filter id="ixQrLrs" width="6.2" height="6" x="3.846" y="14.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.678431 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2062"/></filter><filter id="idWeXOr" width="4.632" height="4.632" x="4.53" y="14.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".25"/></filter><filter id="i5so2Ge" width="4.632" height="4.632" x="22.733" y="14.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".25"/></filter><filter id="ijWGTNd" width="20.485" height="26.75" x="6.108" y="3.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.682353 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2062"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.8 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2062" result="effect2_innerShadow_3930_2062"/></filter><filter id="iI1pvvc" width="4.5" height="5.836" x="13.358" y="15.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".25"/></filter><filter id="itzF6Vb" width="3.571" height="5.2" x="14.061" y="15.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".05"/></filter><filter id="ikpidHd" width="6.619" height="2.54" x="12.537" y="22.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".075"/></filter><filter id="iPvmGAe" width="4.274" height="2.047" x="18.809" y="10.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2062"/></filter><filter id="iZZVrsd" width="4.274" height="2.019" x="9.009" y="10.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2062"/></filter><filter id="i54F7ke" width="1.512" height="1.614" x="12.015" y="15.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".1"/></filter><filter id="i2HuNxd" width="1.552" height="1.157" x="10.493" y="15.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".05"/></filter><filter id="i1yLAje" width="1.294" height="1.125" x="18.632" y="15.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".05"/></filter><filter id="iBFvfTb" width="1.316" height="1.357" x="20.284" y="15.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".1"/></filter><filter id="itos1Nd" width="3.876" height="1.451" x="9.249" y="11.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".125"/></filter><filter id="iH8NJVb" width="3.77" height="1.537" x="19.187" y="11.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation=".125"/></filter><filter id="iuMq5Dc" width="12.281" height="10.228" x="14" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2062" stdDeviation="1"/></filter><linearGradient id="ilaSsjc" x1="4.663" x2="8.195" y1="17.051" y2="16.552" gradientUnits="userSpaceOnUse"><stop class="zik935bna"/><stop offset="1" class="muo4jd2id"/></linearGradient><linearGradient id="iGWfLEr" x1="28.469" x2="27.773" y1="16.031" y2="19.719" gradientUnits="userSpaceOnUse"><stop class="y568znxon"/><stop offset="1" class="jyj9f_bsm"/></linearGradient><linearGradient id="iOZRxvd" x1="15.846" x2="15.846" y1="21.051" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="l79d4nfbe"/><stop offset="1" class="e0wla2b3f"/></linearGradient><linearGradient id="ik9HEJd" x1="13.95" x2="15.615" y1="19.594" y2="19.712" gradientUnits="userSpaceOnUse"><stop class="rc5rm3q2u"/><stop offset="1" class="xy747rbvb"/></linearGradient><linearGradient id="ivP02ec" x1="15.978" x2="15.978" y1="16.051" y2="16.884" gradientUnits="userSpaceOnUse"><stop class="y0xs34bkf"/><stop offset="1" class="dv92htber"/></linearGradient><linearGradient id="iA76rPc" x1="14.608" x2="15.139" y1="24.321" y2="22.973" gradientUnits="userSpaceOnUse"><stop class="yzrfim5ub"/><stop offset="1" class="x4seihbeq"/></linearGradient><linearGradient id="ik6Gqid" x1="13.195" x2="12.6" y1="15.947" y2="16.313" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijPjLAb" x1="21.365" x2="20.78" y1="15.938" y2="16.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bald-light" /></template>
<style>
.ae4egub9n {
  stop-color: var(--svg-color--ffddc0, #FFDDC0);
  stop-opacity: 0;
}

.atqfqlphr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.388 14.424a2.65 2.65 0 0 0-2.57 2.008a.52.52 0 0 0 .508.646h4.232a.436.436 0 0 0 .43-.515a2.66 2.66 0 0 0-2.6-2.139");
}

.ayg4jacub {
  stop-color: var(--svg-color--c29189, #C29189);
  stop-opacity: 0;
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

.c8vaqsbda {
  d: path("m15.16 16.578l-.955 3.17c-.195.651.273 1.303.935 1.303h1.412c.662 0 1.13-.662.935-1.304l-.955-3.17a.71.71 0 0 0-1.373 0");
}

.cg_kaab0n {
  stop-color: var(--svg-color--f7baa9, #F7BAA9);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cz7k6-b_c {
  stop-color: var(--svg-color--b57997, #B57997);
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

.dv92htber {
  stop-color: var(--svg-color--e8bea7, #E8BEA7);
  stop-opacity: 0;
}

.e0wla2b3f {
  stop-color: var(--svg-color--d79d99, #D79D99);
  stop-opacity: 0;
}

.f5f-a4bem {
  stop-color: var(--svg-color--daa697, #DAA697);
}

.fofe-abkb {
  d: path("M21.4 16.394a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.fp9zhfbup {
  stop-color: var(--svg-color--d0958e, #D0958E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3c2qj6we {
  stop-color: var(--svg-color--ffddc0, #FFDDC0);
}

.gpo-x8s4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.304 14.442c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.16a.43.43 0 0 1-.423-.506a2.606 2.606 0 0 1 2.557-2.103");
}

.h_57ad8xy {
  stop-color: var(--svg-color--af7b6e, #AF7B6E);
}

.h7c0c7b5k {
  fill: var(--svg-color--000, #000);
  d: path("M12.75 16.632a.966.966 0 0 0-.97-.97a.966.966 0 0 0-.861 1.416h1.715a.96.96 0 0 0 .116-.446");
}

.hgt94i1zu {
  stop-color: var(--svg-color--d7ac9a, #D7AC9A);
}

.hh9yhccaw {
  cx: 11.27px;
  cy: 15.663px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.739px;
  ry: 0.374px;
}

.i53jeobkn {
  fill: var(--svg-color--202020, #202020);
  d: path("M22.806 11.99c-.327-.284-.707-.585-1.282-.766c-.568-.179-1.278-.227-2.26-.106a.517.517 0 1 0 .125 1.026c.897-.11 1.446-.053 1.824.066c.37.117.62.305.913.56a.517.517 0 0 0 .68-.78");
}

.icd8fhbfu {
  stop-color: var(--svg-color--ffdabe, #FFDABE);
}

.ie_uvmber {
  stop-color: var(--svg-color--b27d6f, #B27D6F);
}

.io54krb-t {
  fill: var(--svg-color--c38b76, #C38B76);
  d: path("m15.108 17.015l-1.204 3.005a1.005 1.005 0 0 0 .97 1.304h1.467c.687 0 1.173-.662.97-1.304l-1.125-3.005c-.213-.703-.855-.703-1.078 0");
}

.iyyx2kbun {
  stop-color: var(--svg-color--ffdac5, #FFDAC5);
  stop-opacity: 0;
}

.jyj9f_bsm {
  stop-color: var(--svg-color--daab9d, #DAAB9D);
}

.k474snbsw {
  stop-color: var(--svg-color--c39877, #C39877);
}

.k5zxaccpr {
  d: path("M6.846 18.867a1.816 1.816 0 1 0 0-3.632a1.816 1.816 0 0 0 0 3.632");
}

.kjbt9bble {
  fill: var(--svg-color--202020, #202020);
  d: path("M9.487 11.788a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.126 1.026a4.14 4.14 0 0 0-2.585.53a3 3 0 0 0-.171.112l-.005.004a.517.517 0 0 1-.634-.817z");
}

.kucajh8au {
  d: path("M6.846 20.051a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.l_k5n4ipq {
  stop-color: var(--svg-color--c39877, #C39877);
  stop-opacity: 0;
}

.l34umybke {
  cx: 11.27px;
  cy: 15.663px;
  rx: 0.739px;
  ry: 0.374px;
}

.l79d4nfbe {
  stop-color: var(--svg-color--d79d99, #D79D99);
}

.lec_e1qks {
  stop-color: var(--svg-color--d5a48e, #D5A48E);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk0ka18ei {
  stop-color: var(--svg-color--c99192, #C99192);
  stop-opacity: 0;
}

.lpcbqrzyv {
  d: path("M19.918 14.949a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.671-1.664");
}

.lqro5bhqi {
  stop-color: var(--svg-color--f7baa9, #F7BAA9);
  stop-opacity: 0;
}

.lut-i8bzq {
  stop-color: var(--svg-color--b57997, #B57997);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.moz8mrdmc {
  stop-color: var(--svg-color--d2a790, #D2A790);
}

.muo4jd2id {
  stop-color: var(--svg-color--ae806f, #AE806F);
}

.mx8aigb4b {
  d: path("M13.327 16.433c0-.547-.445-.911-.565-1.021l-.547.528l.336.686z");
}

.ns22v9t-w {
  stop-color: var(--svg-color--ffddc6, #FFDDC6);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pohux-bmu {
  stop-color: var(--svg-color--d1a18a, #D1A18A);
  stop-opacity: 0;
}

.pv28hhbpl {
  stop-color: var(--svg-color--d1a18a, #D1A18A);
}

.q5qi2rbdr {
  d: path("M19.796 15.3c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.qj8d7fbft {
  stop-color: var(--svg-color--d0958e, #D0958E);
}

.qjty43nui {
  fill: var(--svg-color--f5c1aa, #F5C1AA);
  d: path("m15.16 16.578l-.955 3.17c-.195.651.273 1.303.935 1.303h1.412c.662 0 1.13-.662.935-1.304l-.955-3.17a.71.71 0 0 0-1.373 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_pw-bfon {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.582 12.295c-.5-.484-1.695-.918-3.02-.75");
}

.r9hd54buy {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
  stop-opacity: 0;
}

.rbowec_je {
  stop-color: var(--svg-color--c29189, #C29189);
}

.rc5rm3q2u {
  stop-color: var(--svg-color--d9a18a, #D9A18A);
}

.rdn92bc4r {
  stop-color: var(--svg-color--ffdac5, #FFDAC5);
}

.s-ceiepmf {
  stop-color: var(--svg-color--654843, #654843);
}

.scjo-lbpq {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
}

.sd9_4o2-h {
  d: path("m22.813 6.5l-5.269 1.232A2 2 0 0 0 16 9.68v1.747a1 1 0 0 0 .495.863l.572.335a.745.745 0 0 0 1.12-.643c0-.353.25-.658.595-.729l5.5-1.128c0-1.5-1.042-3.208-1.47-3.625");
}

.ufrzmjiom {
  stop-color: var(--svg-color--c99192, #C99192);
}

.v6ix0we7l {
  stop-color: var(--svg-color--d2a790, #D2A790);
  stop-opacity: 0;
}

.vmw_irb9y {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.235 22.27a.34.34 0 0 0-.407.071a.31.31 0 0 0-.034.4a3.65 3.65 0 0 0 3.052 1.63a3.65 3.65 0 0 0 3.052-1.63a.314.314 0 0 0-.035-.404a.34.34 0 0 0-.406-.066a5.6 5.6 0 0 1-2.611.619a5.66 5.66 0 0 1-2.611-.62Z");
}

.wxgfgebei {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.846 22.94a5.7 5.7 0 0 1-2.634-.625c-.26-.132-.54.161-.376.398a3.6 3.6 0 0 0 3.01 1.608a3.6 3.6 0 0 0 3.01-1.608c.164-.246-.116-.53-.376-.398a5.7 5.7 0 0 1-2.634.625");
}

.x4seihbeq {
  stop-color: var(--svg-color--d49c91, #D49C91);
  stop-opacity: 0;
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xvxnt3n-k {
  stop-color: var(--svg-color--ffddc6, #FFDDC6);
}

.xy747rbvb {
  stop-color: var(--svg-color--d9a18a, #D9A18A);
  stop-opacity: 0;
}

.y0xs34bkf {
  stop-color: var(--svg-color--e8bea7, #E8BEA7);
}

.y568znxon {
  stop-color: var(--svg-color--fdd4be, #FDD4BE);
}

.yzrfim5ub {
  stop-color: var(--svg-color--d49c91, #D49C91);
}

.zik935bna {
  stop-color: var(--svg-color--c08c80, #C08C80);
}

.zyfqcfbru {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.624 12.209c.408-.303 1.689-.808 3.126-.681");
}

</style>
