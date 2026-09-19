<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRD9ROc)" class="sbbmh2b2h"/><path fill="url(#izAjoyc)" class="sbbmh2b2h"/><path fill="url(#ia9BSyb)" class="sbbmh2b2h"/><path fill="url(#igeIdxc)" class="sbbmh2b2h"/><path fill="url(#iImuruV)" class="sbbmh2b2h"/><rect fill="url(#iHxWTYb)" class="h1wxsxb6x"/><circle fill="url(#iIorTEb)" class="b8w_2bbqp"/><g filter="url(#iM3JvFe)"><circle fill="url(#i9HB1Bd)" class="ytg6rzbly"/></g><g filter="url(#iQfRDnb)"><circle fill="url(#iEbiMoc)" class="mzsr1mb4b"/><circle fill="url(#i932eye)" class="mzsr1mb4b"/></g><g filter="url(#in2Pr8c)"><circle class="xmz8fub2y"/><circle fill="url(#izGtBjc)" class="hl_z2c08y"/><circle fill="url(#iCZQG0b)" class="hl_z2c08y"/></g><path fill="url(#iRXaRec)" class="lyyw2vblo"/><path fill="url(#i0k24Sc)" class="lyyw2vblo"/><path fill="url(#ig1roEe)" class="lyyw2vblo"/><path fill="url(#iaGxVZb)" class="lyyw2vblo"/><path fill="url(#if6w3td)" class="lyyw2vblo"/><path fill="url(#iAaePYd)" class="lyyw2vblo"/><g filter="url(#iyJC8qa)"><path class="e9kj58b0j"/><path fill="url(#iWubJZb)" class="ma3thok6g"/><path fill="url(#iTdK7wb)" class="ma3thok6g"/><path fill="url(#iC9bb3b)" class="ma3thok6g"/><path fill="url(#ijjr5pb)" class="ma3thok6g"/><path fill="url(#iGZWG5b)" class="ma3thok6g"/><path fill="url(#inzysPc)" class="ma3thok6g"/></g><path fill="url(#iMkmdcp)" class="ma3thok6g"/><path fill="url(#iLKdU2d)" class="ma3thok6g"/><g filter="url(#iFYhaZd)"><path class="zlgnerbae"/></g><g filter="url(#i77GW2c)"><path class="yg2bh1jpv"/><path fill="url(#iFE4NGd)" class="odk-36b1y"/><path fill="url(#iABfh2b)" class="odk-36b1y"/><path fill="url(#iw5gaBv)" class="odk-36b1y"/></g><path fill="url(#isXcsgb)" class="odk-36b1y"/><path class="yqlrfbb9w"/><path fill="url(#ij7EZ3c)" class="bo7dqkbgb"/><path class="vz5_l1b8e"/><g filter="url(#iOZHNHe)"><path class="vtk1kbbxc"/><path fill="url(#iERH8jd)" class="lleyhibrw"/></g><g filter="url(#iQc1xkb)"><path fill="url(#i0CQQIc)" class="d7irl7bkq"/></g><path class="ymjdgzbgl"/><path fill="url(#iSugmCd)" class="f-gz9ubtq"/><path class="zja-p0uib"/><g filter="url(#iEb5FLc)"><path fill="url(#iVdTUac)" class="byldv1b5l"/></g><g filter="url(#ivv7vHe)"><ellipse transform="rotate(-27.914 12.806 12.277)" class="sw0a0bmid"/><ellipse fill="url(#iaU72re)" transform="rotate(-27.914 12.806 12.277)" class="wfig-1ofx"/></g><path clip-rule="evenodd" class="fgawj49vy"/><g filter="url(#iOPkFjb)"><path clip-rule="evenodd" class="un04mqedo"/></g><g filter="url(#ikpi0ke)"><path clip-rule="evenodd" class="fin6cxb3q"/></g><g filter="url(#ip1dd2b)"><path class="g5of2sb1y"/></g><g filter="url(#iJHY1cf)"><path class="nx9pcsf1i"/></g><defs><radialGradient id="iRD9ROc" cx="0" cy="0" r="1" gradientTransform="rotate(160.481 9.323 14.107)scale(12.5328 12.8728)" gradientUnits="userSpaceOnUse"><stop class="v-2sss5_q"/><stop offset=".578" class="rl_l27czx"/></radialGradient><radialGradient id="izAjoyc" cx="0" cy="0" r="1" gradientTransform="matrix(-20.8125 0 0 -13.0625 25.199 29.164)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zx529yrpf"/><stop offset="1" class="vith88blc"/></radialGradient><radialGradient id="igeIdxc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25498 0 0 -2.00346 15.703 21.178)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="kwfxid2mc"/><stop offset="1" class="axqjsnbkb"/></radialGradient><radialGradient id="iImuruV" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.77741 5.6184 0 12.446 30.213)" gradientUnits="userSpaceOnUse"><stop class="ylk4vpbqv"/><stop offset="1" class="cac2is6pz"/></radialGradient><radialGradient id="iHxWTYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 2.96875 -4.68169 4.04104 15.23 20.758)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="u53k9jqlc"/><stop offset=".963" class="pqj3bj9eb"/></radialGradient><radialGradient id="iIorTEb" cx="0" cy="0" r="1" gradientTransform="matrix(2.28243 0 0 3.99428 7.653 13.289)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="i932eye" cx="0" cy="0" r="1" gradientTransform="matrix(1.07524 -.78294 .89362 1.22724 22.682 12.944)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="izGtBjc" cx="0" cy="0" r="1" gradientTransform="matrix(1.06818 -1.96464 1.1499 .6252 22.144 14.357)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iCZQG0b" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -5.059 33.634)scale(.47451 .61172)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="ig1roEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.2929 -15.3295 0 15.608 11.414)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="vy2q3-0fc"/><stop offset="1" class="fblnsmbke"/></radialGradient><radialGradient id="iaGxVZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.70003 2.09234 0 19.051 11.635)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="if6w3td" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.80901 2.24966 0 13.123 11.591)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iWubJZb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.603 6.723)scale(7.29158 12.4)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iC9bb3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.08692 -2.4211 1.18905 -.04269 10.546 8.794)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="ijjr5pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.11742 -2.55768 2.08598 .91134 21.497 11.03)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iGZWG5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.29125 1.6022 -1.41464 1.14008 14.992 2.101)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="inzysPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.88721 -3.94825 1.36417 .65206 21.448 7.801)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iMkmdcp" cx="0" cy="0" r="1" gradientTransform="matrix(.2359 1.01866 -1.67468 .38782 16.904 2.102)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="r29nd_sam"/><stop offset="1" class="p8ymub_2v"/></radialGradient><radialGradient id="iLKdU2d" cx="0" cy="0" r="1" gradientTransform="rotate(51.044 .62 13.011)scale(1.50083 3.36281)" gradientUnits="userSpaceOnUse"><stop class="pb3_oi83v"/><stop offset="1" class="mmcwxbbos"/></radialGradient><radialGradient id="ij7EZ3c" cx="0" cy="0" r="1" gradientTransform="rotate(90 3 15.835)scale(1.17467 1.38994)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iERH8jd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30133 -.3883 .5346 -.41486 18.537 12.51)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSugmCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.17473 -1.39001 0 13.16 12.835)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iaU72re" cx="0" cy="0" r="1" gradientTransform="matrix(-.01005 -.64196 .77166 -.01208 12.786 12.686)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iM3JvFe" width="3.588" height="3.588" x="8.031" y="11.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".25"/></filter><filter id="iQfRDnb" width="4.593" height="4.593" x="20.027" y="10.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21950"/></filter><filter id="in2Pr8c" width="3.588" height="3.588" x="20.404" y="11.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".25"/></filter><filter id="iyJC8qa" width="16.39" height="10.962" x="7.805" y="1.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21950"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_21950" result="effect2_innerShadow_3987_21950"/></filter><filter id="iFYhaZd" width="3.789" height="4.987" x="13.795" y="12.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".375"/></filter><filter id="i77GW2c" width="2.941" height="3.987" x="14.529" y="12.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".125"/></filter><filter id="iOZHNHe" width=".962" height=".845" x="17.909" y="11.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".05"/></filter><filter id="iQc1xkb" width="1.038" height="1.067" x="19.031" y="11.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".1"/></filter><filter id="iEb5FLc" width="1.162" height="1.232" x="13.255" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".1"/></filter><filter id="ivv7vHe" width="1.127" height=".855" x="12.243" y="11.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".05"/></filter><filter id="iOPkFjb" width="3.582" height="2.502" x="10.965" y="8.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21950"/></filter><filter id="ikpi0ke" width="3.582" height="2.502" x="17.754" y="8.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21950"/></filter><filter id="ip1dd2b" width="2.982" height="1.752" x="11.14" y="9.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".15"/></filter><filter id="iJHY1cf" width="2.982" height="1.752" x="18.01" y="9.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21950" stdDeviation=".15"/></filter><linearGradient id="ia9BSyb" x1="16" x2="16" y1="29.984" y2="29.398" gradientUnits="userSpaceOnUse"><stop class="mbdrodj7c"/><stop offset="1" class="twkbxyfkj"/></linearGradient><linearGradient id="i9HB1Bd" x1="9.825" x2="8.992" y1="13.651" y2="13.651" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iEbiMoc" x1="23.611" x2="22.546" y1="11.869" y2="15.168" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iRXaRec" x1="21.249" x2="11.316" y1="13.795" y2="15.275" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="x2e45tbep"/></linearGradient><linearGradient id="i0k24Sc" x1="8.982" x2="11.99" y1="17.302" y2="16.909" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iAaePYd" x1="16.037" x2="16.037" y1="21.695" y2="20.523" gradientUnits="userSpaceOnUse"><stop class="r1hjethph"/><stop offset="1" class="q82a7wbbc"/></linearGradient><linearGradient id="iTdK7wb" x1="9.386" x2="13.452" y1="11.852" y2="6.237" gradientUnits="userSpaceOnUse"><stop offset=".035" class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iFE4NGd" x1="14.876" x2="16.096" y1="14.653" y2="14.653" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iABfh2b" x1="17.221" x2="15.886" y1="15.072" y2="15.053" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iw5gaBv" x1="16.253" x2="16.253" y1="16.038" y2="15.292" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="isXcsgb" x1="16.163" x2="16.163" y1="16.092" y2="15.874" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="i0CQQIc" x1="19.845" x2="19.437" y1="12.472" y2="12.723" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVdTUac" x1="14.126" x2="13.718" y1="12.471" y2="12.723" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-frowning" /></template>
<style>
.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.axqjsnbkb {
  stop-color: var(--svg-color--176bb1, #176BB1);
  stop-opacity: 0;
}

.b8w_2bbqp {
  cx: 9.825px;
  cy: 13.289px;
  r: 2.171px;
}

.bo7dqkbgb {
  d: path("M18.837 11.781a1.16 1.16 0 0 1 1.118 1.467h-2.242q-.04-.149-.042-.306c0-.638.522-1.16 1.166-1.16");
}

.byldv1b5l {
  d: path("M14.216 12.805c0-.375-.304-.625-.387-.7l-.375.362l.231.47z");
}

.cac2is6pz {
  stop-color: var(--svg-color--2888f9, #2888F9);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d7irl7bkq {
  d: path("M19.87 12.789a1.1 1.1 0 0 0-.3-.602l-.339.371l.153.297z");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.e9kj58b0j {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m22.268 4.863l.558.278c.976.485 1.534 1.595 1.325 2.775l-.767 3.954c-.069.408-.339.683-.744.693h-.024s.07-1.179.14-1.873c.057-.563-.042-.735-.558-1.248c-.28-.278-.489-.694-.489-1.11v-1.11c0-.347-.279-.624-.558-.694c-.837-.208-2.581-.555-5.093-.555s-4.255.347-5.092.555c-.35.07-.558.347-.558.694v1.11c0 .416-.14.832-.489 1.11l-.21.208c-.278.208-.418.624-.418.971c.07.763.14 1.873.14 1.873q-.033 0-.064-.002a.824.824 0 0 1-.773-.692l-.768-3.954c-.14-1.11.419-2.22 1.395-2.705l.559-.278c.348-.208.697-.485 1.046-.763l1.256-1.318c.767-.693 1.883-.901 2.86-.416a3.8 3.8 0 0 0 2.163 0c1.046-.347 2.232-.07 3.07.694L21.22 4.1c.28.347.628.555 1.047.763");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f-gz9ubtq {
  d: path("M13.157 11.781a1.16 1.16 0 0 0-1.119 1.467h2.242q.042-.149.043-.306a1.17 1.17 0 0 0-1.166-1.16");
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fblnsmbke {
  stop-color: var(--svg-color--d87753, #D87753);
}

.fgawj49vy {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M17.087 17.766c-.918-.628-1.93-.26-2.34.004a.275.275 0 0 1-.298-.462c.495-.319 1.765-.805 2.948.004a.275.275 0 1 1-.31.454");
}

.fin6cxb3q {
  fill: var(--svg-color--c85c2f, #C85C2F);
  fill-rule: evenodd;
  d: path("M17.927 9.466a.625.625 0 0 0 .02.884a3.66 3.66 0 0 0 2.514 1.025a.625.625 0 1 0 0-1.25a2.4 2.4 0 0 1-1.65-.678a.625.625 0 0 0-.884.02");
}

.ft5dv1b6b {
  fill: none;
}

.g5of2sb1y {
  stroke: var(--svg-color--d5715e, #D5715E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.59 10.594c.656 0 1.441-.239 2.082-.852");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.h1wxsxb6x {
  width: 5.188px;
  height: 6.789px;
  x: 13.432px;
  y: 17.141px;
  rx: 2.594px;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hl_z2c08y {
  cx: 22.198px;
  cy: 13.289px;
  r: 1.294px;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kwfxid2mc {
  stop-color: var(--svg-color--176bb1, #176BB1);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lleyhibrw {
  d: path("M18.75 12.027c.083.11-.09.245-.286.392s-.342.25-.424.14c-.083-.111.01-.32.205-.466c.197-.147.423-.177.505-.066");
}

.lyyw2vblo {
  d: path("m9.367 12.492l.064.002s-.07-1.11-.14-1.873c0-.347.14-.763.419-.971l.21-.208c.348-.278.488-.694.488-1.11v-1.11c0-.347.209-.624.558-.694c.837-.208 2.58-.555 5.092-.555s4.256.347 5.093.555c.28.07.558.347.558.694v1.11c0 .416.21.832.489 1.11c.653.457.612.709.558 1.248c-.07.694-.14 1.873-.14 1.873h.024l-.346 5.148c-.209 2.302-2.018 3.906-4.175 3.906h-4.176c-2.227 0-3.967-1.604-4.175-3.906z");
}

.ma3thok6g {
  d: path("m22.268 4.863l.558.278c.976.485 1.534 1.595 1.325 2.775l-.767 3.954c-.069.408-.339.683-.744.693h-.024s.07-1.179.14-1.873c.057-.563-.042-.735-.558-1.248c-.28-.278-.489-.694-.489-1.11v-1.11c0-.347-.279-.624-.558-.694c-.837-.208-2.581-.555-5.093-.555s-4.255.347-5.092.555c-.35.07-.558.347-.558.694v1.11c0 .416-.14.832-.489 1.11l-.21.208c-.278.208-.418.624-.418.971c.07.763.14 1.873.14 1.873q-.033 0-.064-.002a.824.824 0 0 1-.773-.692l-.768-3.954c-.14-1.11.419-2.22 1.395-2.705l.559-.278c.348-.208.697-.485 1.046-.763l1.256-1.318c.767-.693 1.883-.901 2.86-.416a3.8 3.8 0 0 0 2.163 0c1.046-.347 2.232-.07 3.07.694L21.22 4.1c.28.347.628.555 1.047.763");
}

.mbdrodj7c {
  stop-color: var(--svg-color--2771fc, #2771FC);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mmcwxbbos {
  stop-color: var(--svg-color--c9993e, #C9993E);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mzsr1mb4b {
  cx: 22.198px;
  cy: 13.289px;
  r: 2.171px;
}

.nx9pcsf1i {
  stroke: var(--svg-color--d5715e, #D5715E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.542 10.508a3.03 3.03 0 0 1-2.082-.852");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odk-36b1y {
  d: path("m15.503 12.918l-.691 2.21a.7.7 0 0 0 .677.91h1.022c.48 0 .818-.462.677-.91l-.69-2.21c-.149-.49-.84-.49-.995 0");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p8ymub_2v {
  stop-color: var(--svg-color--dcb85c, #DCB85C);
  stop-opacity: 0;
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqj3bj9eb {
  stop-color: var(--svg-color--ffd041, #FFD041);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q82a7wbbc {
  stop-color: var(--svg-color--eb8c43, #EB8C43);
  stop-opacity: 0;
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1hjethph {
  stop-color: var(--svg-color--c97c37, #C97C37);
}

.r29nd_sam {
  stop-color: var(--svg-color--dcb85c, #DCB85C);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rl_l27czx {
  stop-color: var(--svg-color--2e96ff, #2E96FF);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sbbmh2b2h {
  d: path("M16 19.727c-5.502 0-9.963 4.46-9.963 9.962v.21h19.926v-.21c0-5.502-4.46-9.962-9.963-9.962");
}

.sw0a0bmid {
  cx: 12.806px;
  cy: 12.277px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.twkbxyfkj {
  stop-color: var(--svg-color--2771fc, #2771FC);
  stop-opacity: 0;
}

.u53k9jqlc {
  stop-color: var(--svg-color--da7e0b, #DA7E0B);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.un04mqedo {
  fill: var(--svg-color--c85c2f, #C85C2F);
  fill-rule: evenodd;
  d: path("M14.123 9.466c.239.25.23.645-.019.884a3.66 3.66 0 0 1-2.514 1.025a.625.625 0 0 1 0-1.25a2.4 2.4 0 0 0 1.65-.678a.625.625 0 0 1 .883.02");
}

.v-2sss5_q {
  stop-color: var(--svg-color--4ab3ff, #4AB3FF);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vith88blc {
  stop-color: var(--svg-color--3a8fc0, #3A8FC0);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vtk1kbbxc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.75 12.027c.083.11-.09.245-.286.392s-.342.25-.424.14c-.083-.111.01-.32.205-.466c.197-.147.423-.177.505-.066");
}

.vy2q3-0fc {
  stop-color: var(--svg-color--f5943f, #F5943F);
  stop-opacity: 0;
}

.vz5_l1b8e {
  fill: var(--svg-color--000, #000);
  d: path("M18.172 12.942c0-.37.295-.665.665-.665a.662.662 0 0 1 .59.97h-1.176a.6.6 0 0 1-.079-.305");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wfig-1ofx {
  cx: 12.806px;
  cy: 12.277px;
  rx: 0.506px;
  ry: 0.256px;
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x2e45tbep {
  stop-color: var(--svg-color--ffac1b, #FFAC1B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xmz8fub2y {
  cx: 22.198px;
  cy: 13.289px;
  r: 1.294px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.yg2bh1jpv {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.503 12.918l-.691 2.21a.7.7 0 0 0 .677.91h1.022c.48 0 .818-.462.677-.91l-.69-2.21c-.149-.49-.84-.49-.995 0");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ylk4vpbqv {
  stop-color: var(--svg-color--2888f9, #2888F9);
}

.ymjdgzbgl {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.888 11.428c-.85 0-1.567.585-1.762 1.377a.357.357 0 0 0 .348.443h2.901a.3.3 0 0 0 .296-.354a1.82 1.82 0 0 0-1.783-1.466");
}

.yqlrfbb9w {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.106 11.428c.849 0 1.566.585 1.761 1.377a.357.357 0 0 1-.348.443h-2.9a.3.3 0 0 1-.296-.354a1.82 1.82 0 0 1 1.783-1.466");
}

.ytg6rzbly {
  cx: 9.825px;
  cy: 13.289px;
  r: 1.294px;
}

.zja-p0uib {
  fill: var(--svg-color--000, #000);
  d: path("M13.821 12.942a.66.66 0 0 0-.664-.665a.662.662 0 0 0-.591.97h1.176a.66.66 0 0 0 .08-.305");
}

.zlgnerbae {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.642 13.13l-1.067 2.21c-.132.455.185.91.635.91h.959c.45 0 .767-.462.634-.91l-.648-2.21c-.139-.49-.368-.49-.513 0");
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zx529yrpf {
  stop-color: var(--svg-color--3a8fc0, #3A8FC0);
  stop-opacity: 0;
}

</style>
