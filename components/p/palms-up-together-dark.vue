<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipyiSic)"><path class="fkyocdbjm"/></g><path fill="url(#iQkAYfc)" class="bsvlz-bbs"/><path fill="url(#iNQnJNd)" class="bsvlz-bbs"/><path fill="url(#iVWT2wd)" class="bsvlz-bbs"/><path fill="url(#ikDJ5mC)" class="bsvlz-bbs"/><path fill="url(#itGIBib)" class="bsvlz-bbs"/><path fill="url(#ir4jKeb)" class="lgbd-k7ej"/><path fill="url(#ioX2LIe)" class="lgbd-k7ej"/><path fill="url(#iGneSvE)" class="lgbd-k7ej"/><path fill="url(#izOHmhe)" class="lgbd-k7ej"/><path fill="url(#ivSje9c)" class="jw00e5bpm"/><path fill="url(#iGMtBUb)" class="jw00e5bpm"/><path fill="url(#iQQhNhb)" class="jw00e5bpm"/><path fill="url(#i67wLjb)" class="jw00e5bpm"/><path fill="url(#i0j7Sre)" class="kwe384bnh"/><path fill="url(#iG4Jcgb)" class="kwe384bnh"/><path fill="url(#iv8hPwb)" class="kwe384bnh"/><path fill="url(#iNNK8xe)" class="kwe384bnh"/><path fill="url(#imUn7me)" class="ujhqir03i"/><path fill="url(#iLz9QKe)" class="ujhqir03i"/><g filter="url(#ihG7tMd)"><path fill="url(#iP9PFhe)" class="g16yvvb2b"/></g><g filter="url(#iPv7cGe)"><rect fill="url(#i417xyc)" class="wp3fp9bsg"/></g><g filter="url(#iYdWLBc)"><path stroke="url(#iujDzze)" class="xm0z3ccpp"/></g><g filter="url(#if0CwYb)"><path stroke="url(#itavOUd)" class="awp5c0tzb"/></g><g filter="url(#ipf5cHj)"><path class="nkah9cccq"/></g><g filter="url(#iMo0mie)"><path stroke="url(#ihA0Zyb)" class="w4t3qsb6h"/></g><g filter="url(#ifpmeab)"><path stroke="url(#iyw8UOb)" class="g070gfeiw"/></g><g filter="url(#ifce3mb)"><path stroke="url(#i45rhDb)" class="fg6ge-bkj"/></g><g filter="url(#iUCkAFd)"><path class="rylfg0byf"/></g><path fill="url(#iPAZBGs)" class="lwjej9mny"/><path fill="url(#imOEUgC)" class="lwjej9mny"/><path fill="url(#i8KzLlc)" class="soqxlnoxv"/><path fill="url(#iMSHSlc)" class="soqxlnoxv"/><path fill="url(#iimuy9c)" class="soqxlnoxv"/><path fill="url(#iAGpNQc)" class="soqxlnoxv"/><path fill="url(#iUELyHc)" class="soqxlnoxv"/><path fill="url(#i5V6xvd)" class="nqfo7ub1d"/><path fill="url(#iVWrW2x)" class="nqfo7ub1d"/><path fill="url(#i5MfaLb)" class="nqfo7ub1d"/><path fill="url(#iccPkce)" class="nqfo7ub1d"/><path fill="url(#i7r3oir)" class="o14407o9p"/><path fill="url(#inNrSad)" class="o14407o9p"/><path fill="url(#ict7AZd)" class="o14407o9p"/><path fill="url(#ins98zf)" class="qhs9-n4dm"/><path fill="url(#iwJTBIc)" class="dbs6_713q"/><g filter="url(#icCcVdc)"><path class="u786dxbci"/></g><g filter="url(#iXpPIXn)"><path fill="url(#irPGdHd)" class="gdv8uzb_s"/></g><g filter="url(#iDuBiIb)"><path fill="url(#iGpSlKe)" class="bw_o2dbrt"/></g><g filter="url(#imqB1xC)"><path stroke="url(#ipy2DNc)" class="ab6ade43t"/></g><defs><linearGradient id="iQkAYfc" x1="2.444" x2="4.561" y1="16.976" y2="16.909" gradientUnits="userSpaceOnUse"><stop class="pte74toty"/><stop offset="1" class="ub7gi2bmx"/></linearGradient><linearGradient id="iNQnJNd" x1="7.875" x2="6.183" y1="16.206" y2="16.43" gradientUnits="userSpaceOnUse"><stop class="lfa-6sb1p"/><stop offset="1" class="v-j7c0b-t"/></linearGradient><linearGradient id="itGIBib" x1="7.106" x2="5.649" y1="19.599" y2="18.866" gradientUnits="userSpaceOnUse"><stop class="is0haqy_b"/><stop offset="1" class="tc4b3ybft"/></linearGradient><linearGradient id="ir4jKeb" x1="6.193" x2="7.966" y1="14.519" y2="14.479" gradientUnits="userSpaceOnUse"><stop class="n92kk_btl"/><stop offset="1" class="kmtol5b4v"/></linearGradient><linearGradient id="ioX2LIe" x1="10.373" x2="8.922" y1="14.479" y2="14.479" gradientUnits="userSpaceOnUse"><stop class="zqa8kxb8c"/><stop offset="1" class="qb4sxkb_y"/></linearGradient><linearGradient id="iGneSvE" x1="8.146" x2="7.966" y1="18.528" y2="16.841" gradientUnits="userSpaceOnUse"><stop class="is0haqy_b"/><stop offset="1" class="tc4b3ybft"/></linearGradient><linearGradient id="ivSje9c" x1="9.604" x2="11.048" y1="16.065" y2="16.068" gradientUnits="userSpaceOnUse"><stop class="qytwim12n"/><stop offset="1" class="x73-25biy"/></linearGradient><linearGradient id="iGMtBUb" x1="13.614" x2="12.222" y1="16.065" y2="16.065" gradientUnits="userSpaceOnUse"><stop class="lp4ys8baq"/><stop offset="1" class="f6qwdbcau"/></linearGradient><linearGradient id="iQQhNhb" x1="10.947" x2="11.284" y1="20.114" y2="17.513" gradientUnits="userSpaceOnUse"><stop offset=".329" class="is0haqy_b"/><stop offset="1" class="tc4b3ybft"/></linearGradient><linearGradient id="i0j7Sre" x1="12.012" x2="14.299" y1="18.239" y2="18.177" gradientUnits="userSpaceOnUse"><stop class="amnlcylra"/><stop offset="1" class="opyd820qr"/></linearGradient><linearGradient id="iG4Jcgb" x1="16.608" x2="15.216" y1="18.172" y2="18.172" gradientUnits="userSpaceOnUse"><stop class="iehpltblr"/><stop offset="1" class="uwnupq6_u"/></linearGradient><linearGradient id="iP9PFhe" x1="5.331" x2="6.978" y1="12.202" y2="21.89" gradientUnits="userSpaceOnUse"><stop class="p6wb4qngy"/><stop offset="1" class="bt5-dxofg"/></linearGradient><linearGradient id="i417xyc" x1="8.695" x2="10.188" y1="9.904" y2="17.956" gradientUnits="userSpaceOnUse"><stop class="vs7zzbbji"/><stop offset="1" class="edrtumbhu"/></linearGradient><linearGradient id="iujDzze" x1="15.875" x2="12.598" y1="15.534" y2="27.346" gradientUnits="userSpaceOnUse"><stop class="v99wjxblu"/><stop offset="1" class="sa3_22bqp"/></linearGradient><linearGradient id="itavOUd" x1="13.883" x2="5.886" y1="20.148" y2="19.743" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ihA0Zyb" x1="7.129" x2="6.894" y1="18.562" y2="20.983" gradientUnits="userSpaceOnUse"><stop class="bc317bc9n"/><stop offset="1" class="uxjoc6-3b"/></linearGradient><linearGradient id="iyw8UOb" x1="9.656" x2="9.715" y1="18.534" y2="18.76" gradientUnits="userSpaceOnUse"><stop class="bc317bc9n"/><stop offset="1" class="uxjoc6-3b"/></linearGradient><linearGradient id="i45rhDb" x1="12.719" x2="12.513" y1="19.659" y2="20.131" gradientUnits="userSpaceOnUse"><stop class="bc317bc9n"/><stop offset="1" class="uxjoc6-3b"/></linearGradient><linearGradient id="i8KzLlc" x1="24.703" x2="27.089" y1="16.221" y2="16.706" gradientUnits="userSpaceOnUse"><stop class="jtyu0qbkd"/><stop offset="1" class="ve-vmqe4t"/></linearGradient><linearGradient id="iMSHSlc" x1="26.047" x2="26.672" y1="19.252" y2="17.221" gradientUnits="userSpaceOnUse"><stop class="i1x_wqbtu"/><stop offset="1" class="u9ikxob2z"/></linearGradient><linearGradient id="iAGpNQc" x1="28.672" x2="27.266" y1="17.08" y2="17.002" gradientUnits="userSpaceOnUse"><stop class="grg56zbuu"/><stop offset="1" class="ilt-m99sq"/></linearGradient><linearGradient id="i5V6xvd" x1="21.704" x2="24.379" y1="14.015" y2="14.015" gradientUnits="userSpaceOnUse"><stop class="ac4ct03wb"/><stop offset="1" class="tza9f7w5n"/></linearGradient><linearGradient id="iVWrW2x" x1="26.234" x2="24.922" y1="14.284" y2="14.19" gradientUnits="userSpaceOnUse"><stop class="pay8bb9yx"/><stop offset="1" class="qmpwn-bkt"/></linearGradient><linearGradient id="i5MfaLb" x1="23.293" x2="23.293" y1="18.397" y2="16.015" gradientUnits="userSpaceOnUse"><stop class="i1x_wqbtu"/><stop offset="1" class="u9ikxob2z"/></linearGradient><linearGradient id="i7r3oir" x1="18.46" x2="21.026" y1="15.603" y2="15.603" gradientUnits="userSpaceOnUse"><stop class="n92kk_btl"/><stop offset="1" class="kmtol5b4v"/></linearGradient><linearGradient id="inNrSad" x1="19.984" x2="19.984" y1="19.971" y2="17.596" gradientUnits="userSpaceOnUse"><stop class="i1x_wqbtu"/><stop offset="1" class="u9ikxob2z"/></linearGradient><linearGradient id="irPGdHd" x1="18.308" x2="19.096" y1="14.216" y2="23.089" gradientUnits="userSpaceOnUse"><stop class="hejq6m4al"/><stop offset="1" class="r-g3baczj"/></linearGradient><linearGradient id="iGpSlKe" x1="21.3" x2="22.088" y1="12.075" y2="20.948" gradientUnits="userSpaceOnUse"><stop class="i9owjtb5v"/><stop offset="1" class="lxab-jhcs"/></linearGradient><linearGradient id="ipy2DNc" x1="25.984" x2="17.334" y1="21.076" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="v1py5ilpz"/><stop offset="1" class="jjcq5q_2o"/></linearGradient><radialGradient id="iVWT2wd" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -.14062 .68202 3.94055 4.75 19.3)" gradientUnits="userSpaceOnUse"><stop class="hr2caabjb"/><stop offset="1" class="lkfchcb_y"/></radialGradient><radialGradient id="ikDJ5mC" cx="0" cy="0" r="1" gradientTransform="matrix(-.93245 2.07151 -1.98394 -.89303 5.721 10.855)" gradientUnits="userSpaceOnUse"><stop class="djf6kz18d"/><stop offset="1" class="awgt5hbdv"/></radialGradient><radialGradient id="izOHmhe" cx="0" cy="0" r="1" gradientTransform="rotate(122.261 2.176 7.163)scale(2.67608 4.1835)" gradientUnits="userSpaceOnUse"><stop class="x_cmizb4i"/><stop offset="1" class="d6yo06b5l"/></radialGradient><radialGradient id="i67wLjb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37018 2.25576 -1.37018 -.83226 12.675 10.749)" gradientUnits="userSpaceOnUse"><stop class="n9vcambar"/><stop offset="1" class="e_kfwziyy"/></radialGradient><radialGradient id="iv8hPwb" cx="0" cy="0" r="1" gradientTransform="rotate(-38.158 36.47 -7.777)scale(3.13529 4.90608)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="is0haqy_b"/><stop offset="1" class="tc4b3ybft"/></radialGradient><radialGradient id="iNNK8xe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58526 2.25577 -1.30627 -.918 15.884 12.855)" gradientUnits="userSpaceOnUse"><stop class="hne-y6tnr"/><stop offset="1" class="d9ca06lui"/></radialGradient><radialGradient id="imUn7me" cx="0" cy="0" r="1" gradientTransform="rotate(161.655 .935 9.547)scale(2.33228 4.21779)" gradientUnits="userSpaceOnUse"><stop offset=".007" class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></radialGradient><radialGradient id="iLz9QKe" cx="0" cy="0" r="1" gradientTransform="matrix(2.66567 -2.49056 5.591 5.9841 1.505 20.06)" gradientUnits="userSpaceOnUse"><stop offset=".615" class="t053lrn-h"/><stop offset="1" class="g21mwkboc"/></radialGradient><radialGradient id="iPAZBGs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99618 1.49687 -.76417 -1.01907 30.887 18.045)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset=".767" class="iv6sy1bym"/></radialGradient><radialGradient id="imOEUgC" cx="0" cy="0" r="1" gradientTransform="matrix(11.59374 4.0625 -5.91453 16.87915 18.797 19.252)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="zxejkjaut"/><stop offset="1" class="lwymtn5sn"/></radialGradient><radialGradient id="iimuy9c" cx="0" cy="0" r="1" gradientTransform="rotate(148.922 12.897 9.99)scale(1.92685 1.61741)" gradientUnits="userSpaceOnUse"><stop class="eser-fblc"/><stop offset="1" class="v41ltixcj"/></radialGradient><radialGradient id="iUELyHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.52312 2.99392 -1.25346 -.21901 27.612 19.462)" gradientUnits="userSpaceOnUse"><stop class="p5tbgbb7d"/><stop offset="1" class="i4_jyh5ct"/></radialGradient><radialGradient id="iccPkce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9104 1.45892 -.88699 -1.16148 25.807 9.614)" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></radialGradient><radialGradient id="ict7AZd" cx="0" cy="0" r="1" gradientTransform="rotate(132.113 8.486 10.565)scale(1.96669 1.26799)" gradientUnits="userSpaceOnUse"><stop class="mjqbe5bnr"/><stop offset="1" class="os2jw8bcg"/></radialGradient><radialGradient id="ins98zf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27068 1.29423 -.92672 -.90986 19.143 13.473)" gradientUnits="userSpaceOnUse"><stop class="ynf5v8bww"/><stop offset="1" class="dbni4sbmg"/></radialGradient><radialGradient id="iwJTBIc" cx="0" cy="0" r="1" gradientTransform="rotate(20.056 -42.317 84.917)scale(1.57817 4.28098)" gradientUnits="userSpaceOnUse"><stop class="cf355xb_x"/><stop offset="1" class="h2ubgccbo"/></radialGradient><filter id="ipyiSic" width="15.887" height="21.793" x="1.113" y="8.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.133333 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3855"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.239216 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3855" result="effect2_innerShadow_20020_3855"/></filter><filter id="ihG7tMd" width="2.833" height="10.003" x="4.201" y="11.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".25"/></filter><filter id="iPv7cGe" width="2.063" height="9.793" x="7.663" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".25"/></filter><filter id="iYdWLBc" width="6.045" height="16.977" x="10.723" y="12.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".625"/></filter><filter id="if0CwYb" width="11.477" height="5.166" x="4.28" y="17.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".625"/></filter><filter id="ipf5cHj" width="7.738" height="10.182" x=".766" y="16.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation="1"/></filter><filter id="iMo0mie" width="2.012" height="2.673" x="5.305" y="18.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".125"/></filter><filter id="ifpmeab" width="2.609" height="1.594" x="7.375" y="18.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".125"/></filter><filter id="ifce3mb" width="3.141" height="1.381" x="9.844" y="18.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".125"/></filter><filter id="iUCkAFd" width="15.887" height="21.293" x="16" y="8.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.133333 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3855"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0431373 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3855" result="effect2_innerShadow_20020_3855"/></filter><filter id="icCcVdc" width="5.961" height="9.438" x="24.297" y="16.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".75"/></filter><filter id="iXpPIXn" width="2.219" height="8.845" x="17.359" y="12.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".25"/></filter><filter id="iDuBiIb" width="2.219" height="9.236" x="20.351" y="10.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".25"/></filter><filter id="imqB1xC" width="12.094" height="6.468" x="15.766" y="17.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3855" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palms-up-together-dark" /></template>
<style>
.ab6ade43t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M17.64 21.659c1.115-1.167 4.344-3.313 8.344-2.563");
}

.ac4ct03wb {
  stop-color: var(--svg-color--311c19, #311C19);
}

.amnlcylra {
  stop-color: var(--svg-color--2c1414, #2C1414);
}

.awgt5hbdv {
  stop-color: var(--svg-color--47322e, #47322E);
  stop-opacity: 0;
}

.awp5c0tzb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.156 19.372c1.406-.416 4.92-.783 7.727 1.08");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bc317bc9n {
  stop-color: var(--svg-color--5d4a49, #5D4A49);
}

.bsvlz-bbs {
  d: path("M4.515 10.961c-.96.071-1.68.907-1.61 1.867l.306 4.145c.8.105 1.439.72 1.58 1.508h.002l.785 3.974c.406-.171 1.672-.875 1.263-3.647l-.46-6.237a1.743 1.743 0 0 0-1.866-1.61");
}

.bt5-dxofg {
  stop-color: var(--svg-color--604e4c, #604E4C);
  stop-opacity: 0;
}

.bw_o2dbrt {
  d: path("M20.851 19.565V11.33c.867-.039 1.219.618 1.219 1.22v7.015z");
}

.cf355xb_x {
  stop-color: var(--svg-color--291616, #291616);
}

.d6yo06b5l {
  stop-color: var(--svg-color--654f4b, #654F4B);
  stop-opacity: 0;
}

.d9ca06lui {
  stop-color: var(--svg-color--5b4642, #5B4642);
  stop-opacity: 0;
}

.dbni4sbmg {
  stop-color: var(--svg-color--624f4d, #624F4D);
  stop-opacity: 0;
}

.dbs6_713q {
  d: path("M30.886 18.866v-.056a1.853 1.853 0 0 0-3.677-.33h-.002l-.793 4.03l3.367 1.203c.258-.719 1.03-3.085 1.105-4.847");
}

.djf6kz18d {
  stop-color: var(--svg-color--47322e, #47322E);
}

.e_kfwziyy {
  stop-color: var(--svg-color--5f4744, #5F4744);
  stop-opacity: 0;
}

.edrtumbhu {
  stop-color: var(--svg-color--634f4c, #634F4C);
  stop-opacity: 0;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.eser-fblc {
  stop-color: var(--svg-color--675250, #675250);
}

.f6qwdbcau {
  stop-color: var(--svg-color--351e1d, #351E1D);
  stop-opacity: 0;
}

.fg6ge-bkj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.344 19.096c.27.146 1.078.425 2.14.375");
}

.fkyocdbjm {
  fill: var(--svg-color--523839, #523839);
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739c.259-.566.862-.91 1.565-.91c.94 0 1.7.762 1.7 1.702v.915c.313-.324.776-.51 1.294-.51A1.7 1.7 0 0 1 16 14.556v8.196c0 2.118-.656 3.498-1.021 3.98a6.32 6.32 0 0 1-6.14 3.175c-2.468-.161-3.883-1.396-4.823-2.577c-.86-1.14-1.594-3.011-1.82-3.664l.002-.011c-.276-.782-1.01-3.072-1.084-4.79v-.055a1.853 1.853 0 0 1 2.097-1.837l-.306-4.145a1.743 1.743 0 0 1 3.288-.925z");
}

.ft5dv1b6b {
  fill: none;
}

.g070gfeiw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.875 19.252c.422 0 1.313-.218 1.61-.593");
}

.g16yvvb2b {
  d: path("m5.541 20.752l-.837-8.4a.548.548 0 1 1 1.09-.108l.74 7.607z");
}

.g21mwkboc {
  stop-color: var(--svg-color--503430, #503430);
}

.gdv8uzb_s {
  d: path("M17.86 21.315V13.47c.867-.04 1.218.617 1.218 1.219v5.437z");
}

.grg56zbuu {
  stop-color: var(--svg-color--573f3b, #573F3B);
}

.h2ubgccbo {
  stop-color: var(--svg-color--291616, #291616);
  stop-opacity: 0;
}

.hejq6m4al {
  stop-color: var(--svg-color--604c4a, #604C4A);
}

.hne-y6tnr {
  stop-color: var(--svg-color--5b4642, #5B4642);
}

.hr2caabjb {
  stop-color: var(--svg-color--2c1715, #2C1715);
}

.i1x_wqbtu {
  stop-color: var(--svg-color--4d3537, #4D3537);
}

.i4_jyh5ct {
  stop-color: var(--svg-color--231114, #231114);
  stop-opacity: 0;
}

.i9owjtb5v {
  stop-color: var(--svg-color--604d4b, #604D4B);
}

.iehpltblr {
  stop-color: var(--svg-color--402725, #402725);
}

.ilt-m99sq {
  stop-color: var(--svg-color--573f3b, #573F3B);
  stop-opacity: 0;
}

.is0haqy_b {
  stop-color: var(--svg-color--51393a, #51393A);
}

.iv6sy1bym {
  stop-color: var(--svg-color--65514f, #65514F);
  stop-opacity: 0;
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.jjcq5q_2o {
  stop-color: var(--svg-color--594645, #594645);
  stop-opacity: 0;
}

.jtyu0qbkd {
  stop-color: var(--svg-color--301a1b, #301A1B);
}

.jw00e5bpm {
  d: path("M11.305 10.749c-.94 0-1.7.612-1.7 1.551v6.456a1.7 1.7 0 0 0 2.993 1.105v-5.454c0-.422.154-.778.408-1.042v-.915a1.7 1.7 0 0 0-1.701-1.701");
}

.kmtol5b4v {
  stop-color: var(--svg-color--26100f, #26100F);
  stop-opacity: 0;
}

.kwe384bnh {
  d: path("M12.598 14.407c0-.94.762-1.552 1.701-1.552S16 13.617 16 14.556v4.613a1.7 1.7 0 1 1-3.402 0z");
}

.lfa-6sb1p {
  stop-color: var(--svg-color--361f1d, #361F1D);
}

.lgbd-k7ej {
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739q-.134.286-.136.643v5.492a1.774 1.774 0 0 1-2.789.668l-.434-5.89a1.7 1.7 0 0 0-.188-.668z");
}

.lkfchcb_y {
  stop-color: var(--svg-color--2c1715, #2C1715);
  stop-opacity: 0;
}

.lp4ys8baq {
  stop-color: var(--svg-color--351e1d, #351E1D);
}

.lwjej9mny {
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739c-.259-.566-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.702v.915c-.313-.324-.777-.51-1.294-.51A1.7 1.7 0 0 0 16 14.556v8.196c0 2.118.656 3.498 1.021 3.98a6.32 6.32 0 0 0 6.14 3.175c2.468-.161 3.883-1.396 4.823-2.577c.86-1.14 1.594-3.011 1.82-3.664l-.002-.011c.276-.782 1.01-3.072 1.084-4.79v-.055a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.lwymtn5sn {
  stop-color: var(--svg-color--503737, #503737);
}

.lxab-jhcs {
  stop-color: var(--svg-color--604d4b, #604D4B);
  stop-opacity: 0;
}

.mjqbe5bnr {
  stop-color: var(--svg-color--614e4c, #614E4C);
}

.n92kk_btl {
  stop-color: var(--svg-color--26100f, #26100F);
}

.n9vcambar {
  stop-color: var(--svg-color--5f4744, #5F4744);
}

.nkah9cccq {
  stroke: var(--svg-color--64504e, #64504E);
  stroke-linecap: round;
  d: path("m3.266 18.53l.944 3.997c.145.593.668 1.441 1.793 1.113");
}

.nqfo7ub1d {
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739q.134.286.136.643v5.492a1.774 1.774 0 0 0 2.789.668l.434-5.89c.018-.24.084-.466.188-.668z");
}

.o14407o9p {
  d: path("M20.695 10.749c.94 0 1.7.612 1.7 1.551v6.456a1.7 1.7 0 0 1-2.993 1.105v-5.454c0-.422-.154-.778-.408-1.042v-.915a1.7 1.7 0 0 1 1.701-1.701");
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.opyd820qr {
  stop-color: var(--svg-color--2c1414, #2C1414);
  stop-opacity: 0;
}

.os2jw8bcg {
  stop-color: var(--svg-color--614e4c, #614E4C);
  stop-opacity: 0;
}

.p5tbgbb7d {
  stop-color: var(--svg-color--231114, #231114);
}

.p6wb4qngy {
  stop-color: var(--svg-color--634f4d, #634F4D);
}

.pay8bb9yx {
  stop-color: var(--svg-color--2d1415, #2D1415);
}

.pte74toty {
  stop-color: var(--svg-color--2d1817, #2D1817);
}

.qb4sxkb_y {
  stop-color: var(--svg-color--37201c, #37201C);
  stop-opacity: 0;
}

.qhs9-n4dm {
  d: path("M19.402 14.407c0-.94-.762-1.552-1.701-1.552A1.7 1.7 0 0 0 16 14.556v4.613a1.7 1.7 0 1 0 3.402 0z");
}

.qmpwn-bkt {
  stop-color: var(--svg-color--2d1415, #2D1415);
  stop-opacity: 0;
}

.qytwim12n {
  stop-color: var(--svg-color--2f1516, #2F1516);
}

.r-g3baczj {
  stop-color: var(--svg-color--604c4a, #604C4A);
  stop-opacity: 0;
}

.rylfg0byf {
  fill: var(--svg-color--4d3537, #4D3537);
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739c-.259-.566-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.702v.915c-.313-.324-.777-.51-1.294-.51A1.7 1.7 0 0 0 16 14.556v8.196c0 2.118.656 3.498 1.021 3.98a6.32 6.32 0 0 0 6.14 3.175c2.468-.161 3.883-1.396 4.823-2.577c.86-1.14 1.594-3.011 1.82-3.664l-.002-.011c.276-.782 1.01-3.072 1.084-4.79v-.055a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.sa3_22bqp {
  stop-color: var(--svg-color--63504e, #63504E);
  stop-opacity: 0;
}

.soqxlnoxv {
  d: path("M27.485 10.961c.96.071 1.68.907 1.61 1.867l-.306 4.145c-.8.105-1.439.72-1.58 1.508h-.002l-.785 3.974c-.406-.171-1.672-.875-1.263-3.647l.46-6.237c.071-.96.907-1.68 1.866-1.61");
}

.t053lrn-h {
  stop-color: var(--svg-color--503430, #503430);
  stop-opacity: 0;
}

.tc4b3ybft {
  stop-color: var(--svg-color--51393a, #51393A);
  stop-opacity: 0;
}

.tza9f7w5n {
  stop-color: var(--svg-color--311c19, #311C19);
  stop-opacity: 0;
}

.u786dxbci {
  stroke: var(--svg-color--372223, #372223);
  stroke-linecap: round;
  d: path("M28.258 18.565c-.188.958-1.367 4.312-1.961 5.437");
}

.u9ikxob2z {
  stop-color: var(--svg-color--4d3537, #4D3537);
  stop-opacity: 0;
}

.ub7gi2bmx {
  stop-color: var(--svg-color--2d1817, #2D1817);
  stop-opacity: 0;
}

.ujhqir03i {
  d: path("M1.114 18.866v-.056a1.853 1.853 0 0 1 3.677-.33h.002l.772 4.012l-3.346 1.221c-.258-.719-1.03-3.085-1.105-4.847");
}

.uwnupq6_u {
  stop-color: var(--svg-color--402725, #402725);
  stop-opacity: 0;
}

.uxjoc6-3b {
  stop-color: var(--svg-color--5d4a49, #5D4A49);
  stop-opacity: 0;
}

.v-j7c0b-t {
  stop-color: var(--svg-color--361f1d, #361F1D);
  stop-opacity: 0;
}

.v1py5ilpz {
  stop-color: var(--svg-color--594645, #594645);
}

.v41ltixcj {
  stop-color: var(--svg-color--675250, #675250);
  stop-opacity: 0;
}

.v99wjxblu {
  stop-color: var(--svg-color--63504e, #63504E);
}

.ve-vmqe4t {
  stop-color: var(--svg-color--301a1b, #301A1B);
  stop-opacity: 0;
}

.vs7zzbbji {
  stop-color: var(--svg-color--634f4c, #634F4C);
}

.w4t3qsb6h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.817 18.835c-.065.266-.358.973-1.012 1.673");
}

.wp3fp9bsg {
  width: 1.063px;
  height: 8.793px;
  x: 8.163px;
  y: 10.093px;
  rx: 0.531px;
}

.x_cmizb4i {
  stop-color: var(--svg-color--654f4b, #654F4B);
}

.x73-25biy {
  stop-color: var(--svg-color--2f1516, #2F1516);
  stop-opacity: 0;
}

.xm0z3ccpp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M14.893 14.489v7.862c.011 1.226-.432 4.015-2.295 5.365");
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.ynf5v8bww {
  stop-color: var(--svg-color--624f4d, #624F4D);
}

.zqa8kxb8c {
  stop-color: var(--svg-color--37201c, #37201C);
}

.zxejkjaut {
  stop-color: var(--svg-color--503737, #503737);
  stop-opacity: 0;
}

</style>
