<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ivPKO2b)" class="hbhmslb5p"/><circle fill="url(#i1jRFvc)" class="sdotsmj7z"/><circle fill="url(#iRiHruP)" class="sdotsmj7z"/><circle fill="url(#ikFGosH)" class="bgfljzbpa"/><circle fill="url(#iB9D18F)" class="x4ree7b7z"/><circle fill="url(#iwnxzzc)" class="x4ree7b7z"/><circle fill="url(#iX2srRc)" class="n0i-k0b1p"/><circle fill="url(#ixkPc4r)" class="aovi0hb2q"/><path fill="url(#iFG4YRb)" class="riyil9b8h"/><path fill="url(#i6XysPd)" class="riyil9b8h"/><path fill="url(#iD9Fzrd)" class="riyil9b8h"/><path fill="url(#isYKuqx)" class="riyil9b8h"/><path fill="url(#iBUKbGe)" class="riyil9b8h"/><path fill="url(#iXmlPue)" class="u_cjtxt1h"/><path fill="url(#iVcZ8ec)" class="u_cjtxt1h"/><path fill="url(#iAIwqcg)" class="u_cjtxt1h"/><path fill="url(#iYlFI6d)" class="u_cjtxt1h"/><g filter="url(#i7yq9nb)"><path fill="url(#ibUx0Xb)" class="qdu-6ebcl"/><path fill="url(#iujTV0d)" class="qdu-6ebcl"/><path fill="url(#is5om5d)" class="qdu-6ebcl"/></g><g filter="url(#iWGGa7c)"><circle class="uhnsqsi9g"/></g><g filter="url(#iHHnXwc)"><path class="zj-fvvinl"/></g><g filter="url(#ikbS7Eb)"><path class="p5um89bez"/></g><path fill="url(#iKngkic)" class="sudh-ybkm"/><path fill="url(#ikVdVHO)" class="sudh-ybkm"/><path fill="url(#iFlbPLU)" class="g1qm7gbdd"/><path fill="url(#iFWkc8b)" class="g1qm7gbdd"/><path fill="url(#iWX8DUC)" class="g1qm7gbdd"/><path fill="url(#iyBp1md)" class="g1qm7gbdd"/><path fill="url(#iEp2sFd)" class="e9_ainbjn"/><path fill="url(#iHfBcNc)" class="f88ivdpya"/><path fill="url(#iofv2hd)" class="k_6wjrbim"/><path fill="url(#iyLWyAM)" class="bk42r554e"/><path fill="url(#iMqbMic)" class="d54rpzv6b"/><path fill="url(#inR8wCd)" class="d54rpzv6b"/><path fill="url(#i7kUQCb)" class="d54rpzv6b"/><path fill="url(#ihCWmsc)" class="n129dgd-i"/><path fill="url(#iYfUu0c)" class="n129dgd-i"/><path fill="url(#iPBtCNb)" class="rzogcloxi"/><path fill="url(#iMmqVgd)" class="rzogcloxi"/><path fill="url(#iEdzOUO)" class="rzogcloxi"/><path fill="url(#iHAjnNe)" class="ar34iccol"/><path fill="url(#iAViMmc)" class="ar34iccol"/><path fill="url(#ieeTl2b)" class="ar34iccol"/><path fill="url(#irAGdCd)" class="ar34iccol"/><path fill="url(#iDWSpde)" class="vbe4h-hnp"/><path fill="url(#iO9ypod)" class="vbe4h-hnp"/><path fill="url(#iCKViOW)" class="vbe4h-hnp"/><g filter="url(#ilidpzc)"><path stroke="url(#iggagsd)" class="iijmqx_as"/></g><g filter="url(#i5Fwy8b)"><path stroke="url(#ij8jwXV)" class="am7r8rl9s"/></g><g filter="url(#iyWkhud)"><circle class="a75dfebtt"/></g><defs><linearGradient id="i6XysPd" x1="26.928" x2="24.116" y1="9.256" y2="11.819" gradientUnits="userSpaceOnUse"><stop offset=".136" class="bvgek25if"/><stop offset=".649" class="ehhy9smdc"/></linearGradient><linearGradient id="isYKuqx" x1="15.991" x2="15.991" y1="28.069" y2="24.319" gradientUnits="userSpaceOnUse"><stop class="wmwhkckqr"/><stop offset="1" class="n8ddt57fq"/></linearGradient><linearGradient id="iBUKbGe" x1="1.991" x2="3.96" y1="13.694" y2="15.596" gradientUnits="userSpaceOnUse"><stop class="ld0cebubi"/><stop offset=".462" class="sv9bqmvzf"/></linearGradient><linearGradient id="iujTV0d" x1="15.991" x2="15.991" y1="25.787" y2="21.537" gradientUnits="userSpaceOnUse"><stop class="xcwmt0d-l"/><stop offset="1" class="xupfqcc4z"/></linearGradient><linearGradient id="iKngkic" x1="20.654" x2="19.828" y1="15.392" y2="15.392" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="ikVdVHO" x1="20.975" x2="20.975" y1="17.417" y2="15.827" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iFlbPLU" x1="17.348" x2="14.255" y1="17.712" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".191" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iFWkc8b" x1="16.39" x2="16.39" y1="18.95" y2="17.254" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="iWX8DUC" x1="17.237" x2="17.237" y1="21.793" y2="19.23" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iEp2sFd" x1="26.928" x2="25.678" y1="23.288" y2="18.663" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mhuc7zb2v"/><stop offset="1" class="b4azweb1r"/></linearGradient><linearGradient id="iHfBcNc" x1="6.993" x2=".116" y1="20.047" y2="20.047" gradientUnits="userSpaceOnUse"><stop offset=".064" class="a5d6diuza"/><stop offset="1" class="ccxl1o-_g"/></linearGradient><linearGradient id="iofv2hd" x1="13.553" x2="17.678" y1="9.975" y2="6.975" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mhuc7zb2v"/><stop offset="1" class="smb3obb5g"/></linearGradient><linearGradient id="iyLWyAM" x1="15.991" x2="15.991" y1="3.725" y2="6.104" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bfdue5bnb"/><stop offset="1" class="mdaobn6dl"/><stop offset="1" class="kuxz5gbch"/></linearGradient><linearGradient id="iMqbMic" x1="10.632" x2="9.913" y1="18.319" y2="19.553" gradientUnits="userSpaceOnUse"><stop class="f_ll_kbji"/><stop offset="1" class="ymbal8b0v"/></linearGradient><linearGradient id="inR8wCd" x1="10.585" x2="10.21" y1="21.506" y2="20.022" gradientUnits="userSpaceOnUse"><stop class="hpjwnrbxv"/><stop offset=".783" class="rbv7ofauz"/></linearGradient><linearGradient id="i7kUQCb" x1="11.553" x2="10.959" y1="18.381" y2="19.881" gradientUnits="userSpaceOnUse"><stop class="prtv3ebme"/><stop offset="1" class="im5lspb_n"/></linearGradient><linearGradient id="ihCWmsc" x1="6.991" x2="8.755" y1="19.913" y2="23.32" gradientUnits="userSpaceOnUse"><stop class="f_ll_kbji"/><stop offset="1" class="ymbal8b0v"/></linearGradient><linearGradient id="iYfUu0c" x1="9.835" x2="8.835" y1="23.725" y2="22.225" gradientUnits="userSpaceOnUse"><stop class="btymebbhi"/><stop offset=".783" class="rbv7ofauz"/></linearGradient><linearGradient id="iPBtCNb" x1="25.678" x2="19.335" y1="17" y2="20.501" gradientUnits="userSpaceOnUse"><stop class="f_ll_kbji"/><stop offset="1" class="ymbal8b0v"/></linearGradient><linearGradient id="iMmqVgd" x1="18.991" x2="21.741" y1="21.506" y2="19.85" gradientUnits="userSpaceOnUse"><stop class="hpjwnrbxv"/><stop offset="1" class="rbv7ofauz"/></linearGradient><linearGradient id="iEdzOUO" x1="25.21" x2="23.975" y1="17.397" y2="18.194" gradientUnits="userSpaceOnUse"><stop class="prtv3ebme"/><stop offset="1" class="im5lspb_n"/></linearGradient><linearGradient id="iHAjnNe" x1="23.366" x2="22.439" y1="22.475" y2="24.1" gradientUnits="userSpaceOnUse"><stop class="f_ll_kbji"/><stop offset="1" class="ymbal8b0v"/></linearGradient><linearGradient id="iAViMmc" x1="21.538" x2="21.913" y1="23.131" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="hpjwnrbxv"/><stop offset=".783" class="rbv7ofauz"/></linearGradient><linearGradient id="ieeTl2b" x1="19.788" x2="22.037" y1="21.503" y2="22.835" gradientUnits="userSpaceOnUse"><stop class="hpjwnrbxv"/><stop offset="1" class="rbv7ofauz"/></linearGradient><linearGradient id="irAGdCd" x1="25.366" x2="23.678" y1="22.6" y2="23.001" gradientUnits="userSpaceOnUse"><stop class="prtv3ebme"/><stop offset="1" class="im5lspb_n"/></linearGradient><linearGradient id="iDWSpde" x1="12.654" x2="11.828" y1="15.392" y2="15.392" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iO9ypod" x1="10.785" x2="11.991" y1="15.392" y2="15.392" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset="1" class="zmzak_sfz"/></linearGradient><linearGradient id="iCKViOW" x1="12.975" x2="12.975" y1="17.417" y2="15.827" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iggagsd" x1="25.053" x2="21.553" y1="17.803" y2="19.928" gradientUnits="userSpaceOnUse"><stop class="prtv3ebme"/><stop offset=".937" class="ru2_kbbzf"/></linearGradient><linearGradient id="ij8jwXV" x1="24.35" x2="21.319" y1="24.006" y2="22.241" gradientUnits="userSpaceOnUse"><stop class="prtv3ebme"/><stop offset=".937" class="ru2_kbbzf"/></linearGradient><radialGradient id="ivPKO2b" cx="0" cy="0" r="1" gradientTransform="rotate(135.385 4.405 4.29)scale(6.58508)" gradientUnits="userSpaceOnUse"><stop class="hxqzeabht"/><stop offset="1" class="j56omibbg"/></radialGradient><radialGradient id="i1jRFvc" cx="0" cy="0" r="1" gradientTransform="rotate(152.526 12.76 5.901)scale(5.28338)" gradientUnits="userSpaceOnUse"><stop class="d364mm6_s"/><stop offset="1" class="wdki8w5df"/></radialGradient><radialGradient id="iRiHruP" cx="0" cy="0" r="1" gradientTransform="matrix(-6.31248 -3.84378 3.48182 -5.71805 26.272 8.569)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="ybz7z7c5a"/><stop offset="1" class="aanocxhpg"/></radialGradient><radialGradient id="ikFGosH" cx="0" cy="0" r="1" gradientTransform="rotate(49.914 6.142 29.275)scale(4.90147 5.73234)" gradientUnits="userSpaceOnUse"><stop offset=".784" class="ybz7z7c5a"/><stop offset="1" class="aanocxhpg"/></radialGradient><radialGradient id="iB9D18F" cx="0" cy="0" r="1" gradientTransform="matrix(2.59374 .76988 -1.46865 4.94795 6.585 6.955)" gradientUnits="userSpaceOnUse"><stop class="m606c1b1a"/><stop offset="1" class="aanocxhpg"/></radialGradient><radialGradient id="iwnxzzc" cx="0" cy="0" r="1" gradientTransform="matrix(2.625 -.58236 .50949 2.29653 5.49 7.537)" gradientUnits="userSpaceOnUse"><stop class="sm-syv1ai"/><stop offset=".876" class="dci1x0bso"/></radialGradient><radialGradient id="iX2srRc" cx="0" cy="0" r="1" gradientTransform="matrix(4.05249 -1.88119 1.03473 2.22903 22.428 7.631)" gradientUnits="userSpaceOnUse"><stop class="qvxetsyer"/><stop offset=".837" class="qo96s4jfk"/></radialGradient><radialGradient id="ixkPc4r" cx="0" cy="0" r="1" gradientTransform="rotate(-139.341 14.409 -.448)scale(5.34783 4.06175)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="ybz7z7c5a"/><stop offset="1" class="aanocxhpg"/></radialGradient><radialGradient id="iFG4YRb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.24985 19.34991 -24.61613 -7.9508 22.24 10.594)" gradientUnits="userSpaceOnUse"><stop class="nmu836btz"/><stop offset=".501" class="vf4b6tbzp"/><stop offset="1" class="v9i4ltcin"/></radialGradient><radialGradient id="iD9Fzrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.625 6.51316 0 15.99 19.912)" gradientUnits="userSpaceOnUse"><stop class="jxw62hr9v"/><stop offset="1" class="lslj-tjmr"/></radialGradient><radialGradient id="iXmlPue" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 8.84989 -8.27269 -.35055 15.99 22.25)" gradientUnits="userSpaceOnUse"><stop class="l7jgs0-oi"/><stop offset=".781" class="u35ucpbhl"/><stop offset="1" class="kii3ahbxo"/></radialGradient><radialGradient id="iVcZ8ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5 -14.5 0 15.99 22.037)" gradientUnits="userSpaceOnUse"><stop offset=".489" class="xupfqcc4z"/><stop offset=".865" class="xcwmt0d-l"/></radialGradient><radialGradient id="iAIwqcg" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.125 -10.25 0 15.99 20.1)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="zozkvbb0u"/><stop offset="1" class="j0w5obbjg"/></radialGradient><radialGradient id="iYlFI6d" cx="0" cy="0" r="1" gradientTransform="matrix(8.1875 4.8125 -3.77327 6.41946 7.24 21.537)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="zozkvbb0u"/><stop offset="1" class="j0w5obbjg"/></radialGradient><radialGradient id="ibUx0Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8 -14.4548 0 19.804 18.35)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="d6cy_itxd"/><stop offset="1" class="xcwmt0d-l"/></radialGradient><radialGradient id="is5om5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2 .9375 -.84515 -1.80297 21.428 20.537)" gradientUnits="userSpaceOnUse"><stop class="mv2_3i2hg"/><stop offset="1" class="q6qrptbzd"/></radialGradient><radialGradient id="iyBp1md" cx="0" cy="0" r="1" gradientTransform="rotate(-161.201 11.231 8.688)scale(6.29662 2.83336)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="lm-pdjb-m"/><stop offset=".935" class="z17z3-a-u"/></radialGradient><filter id="i7yq9nb" width="14" height="6.25" x="8.991" y="17.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.652983 0 0 0 0 0.534201 0 0 0 0 0.754167 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_2236"/></filter><filter id="iWGGa7c" width="2.453" height="2.453" x="19.241" y="19.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2236" stdDeviation=".25"/></filter><filter id="iHHnXwc" width="3.5" height="5" x="17.991" y="13.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2236" stdDeviation=".5"/></filter><filter id="ikbS7Eb" width="3.5" height="5" x="9.991" y="13.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2236" stdDeviation=".5"/></filter><filter id="ilidpzc" width="3.913" height="2.537" x="20.597" y="17.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2236" stdDeviation=".1"/></filter><filter id="i5Fwy8b" width="4.038" height="2.616" x="20.456" y="21.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2236" stdDeviation=".1"/></filter><filter id="iyWkhud" width="1.175" height="1.175" x="10.708" y="21.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2236" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tiger-face" /></template>
<style>
.a5d6diuza {
  stop-color: var(--svg-color--443851, #443851);
}

.a75dfebtt {
  cx: 11.296px;
  cy: 22.03px;
  r: 0.188px;
  fill: var(--svg-color--ccc1d6, #CCC1D6);
}

.aanocxhpg {
  stop-color: var(--svg-color--ca572a, #CA572A);
}

.am7r8rl9s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.757 21.788l3.437 2.015");
}

.aovi0hb2q {
  cx: 24.028px;
  cy: 6.955px;
  r: 2.453px;
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
}

.ar34iccol {
  d: path("m24.42 23.572l-3.46-2a.493.493 0 0 0-.68.18c-.14.24-.06.54.18.68l3.46 2c.24.14.54.06.68-.18s.05-.54-.18-.68");
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b4azweb1r {
  stop-color: var(--svg-color--695c77, #695C77);
}

.bfdue5bnb {
  stop-color: var(--svg-color--635c6c, #635C6C);
}

.bgfljzbpa {
  cx: 24.094px;
  cy: 6.897px;
  r: 3.897px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
}

.bk42r554e {
  d: path("M17.88 4.276a10 10 0 0 0-1.89-.18q-.975 0-1.89.18l1.17 1.52c.39.41 1.04.41 1.42 0z");
}

.btymebbhi {
  stop-color: var(--svg-color--bb99d7, #BB99D7);
}

.bvgek25if {
  stop-color: var(--svg-color--f97420, #F97420);
}

.ccxl1o-_g {
  stop-color: var(--svg-color--5d5863, #5D5863);
}

.d364mm6_s {
  stop-color: var(--svg-color--ffa761, #FFA761);
}

.d54rpzv6b {
  d: path("m11.53 19.572l-3.46-2a.493.493 0 0 0-.68.18c-.14.24-.06.54.18.68l3.46 2c.24.14.54.06.68-.18s.06-.54-.18-.68");
}

.d6cy_itxd {
  stop-color: var(--svg-color--e4d5e8, #E4D5E8);
}

.dci1x0bso {
  stop-color: var(--svg-color--e08353, #E08353);
  stop-opacity: 0;
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e9_ainbjn {
  d: path("M29.62 24.132c.24-.56.37-1.17.37-1.82v-3.85c0-.85-.12-1.69-.34-2.5l-4.36 2.92c-.56.37-.3 1.25.38 1.25h3.75l-4.13 2.75c-.56.37-.3 1.25.38 1.25z");
}

.ehhy9smdc {
  stop-color: var(--svg-color--fc7c2b, #FC7C2B);
  stop-opacity: 0;
}

.f_ll_kbji {
  stop-color: var(--svg-color--e8dfed, #E8DFED);
}

.f88ivdpya {
  d: path("m6.69 22.892l-4.13-2.75h3.75c.67 0 .94-.87.38-1.25l-4.35-2.93c-.23.8-.35 1.65-.35 2.5v3.85c0 .65.13 1.26.37 1.82h3.95c.67 0 .94-.87.38-1.24");
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.g1qm7gbdd {
  d: path("m13.87 19.812l1.38 1.38c.41.41 1.08.41 1.5 0l1.38-1.38c.67-.67.19-1.81-.75-1.81h-2.75c-.96 0-1.43 1.14-.76 1.81");
}

.hbhmslb5p {
  cx: 7.873px;
  cy: 6.897px;
  r: 3.897px;
}

.hpjwnrbxv {
  stop-color: var(--svg-color--beadcc, #BEADCC);
}

.hxqzeabht {
  stop-color: var(--svg-color--ff9e56, #FF9E56);
}

.iijmqx_as {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.897 20.006l3.313-1.937");
}

.im5lspb_n {
  stop-color: var(--svg-color--f6ebf9, #F6EBF9);
  stop-opacity: 0;
}

.j0w5obbjg {
  stop-color: var(--svg-color--a58eb9, #A58EB9);
  stop-opacity: 0;
}

.j56omibbg {
  stop-color: var(--svg-color--d65e27, #D65E27);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jxw62hr9v {
  stop-color: var(--svg-color--e75f09, #E75F09);
}

.k_6wjrbim {
  d: path("M13.14 7.502h5.7c.38 0 .54.47.25.71l-2.7 2.16c-.23.19-.56.19-.8 0l-2.7-2.16c-.29-.24-.13-.71.25-.71");
}

.kii3ahbxo {
  stop-color: var(--svg-color--ab8bca, #AB8BCA);
}

.kuxz5gbch {
  stop-color: var(--svg-color--503f5f, #503F5F);
}

.l7jgs0-oi {
  stop-color: var(--svg-color--e8d0ff, #E8D0FF);
}

.ld0cebubi {
  stop-color: var(--svg-color--bf603d, #BF603D);
}

.lm-pdjb-m {
  stop-color: var(--svg-color--5c5458, #5C5458);
  stop-opacity: 0;
}

.lslj-tjmr {
  stop-color: var(--svg-color--e75f09, #E75F09);
  stop-opacity: 0;
}

.m606c1b1a {
  stop-color: var(--svg-color--e16f15, #E16F15);
}

.mdaobn6dl {
  stop-color: var(--svg-color--4f3e5e, #4F3E5E);
}

.mhuc7zb2v {
  stop-color: var(--svg-color--4e3d5e, #4E3D5E);
}

.mv2_3i2hg {
  stop-color: var(--svg-color--f6e9f9, #F6E9F9);
}

.n0i-k0b1p {
  cx: 24.028px;
  cy: 6.955px;
  r: 2.453px;
}

.n129dgd-i {
  d: path("m7.56 23.572l3.46-2c.24-.14.54-.06.68.18s.06.54-.18.68l-3.46 2c-.24.14-.54.06-.68-.18a.5.5 0 0 1 .18-.68");
}

.n8ddt57fq {
  stop-color: var(--svg-color--c8485b, #C8485B);
  stop-opacity: 0;
}

.nmu836btz {
  stop-color: var(--svg-color--ffa24d, #FFA24D);
}

.p5um89bez {
  fill: var(--svg-color--f86121, #F86121);
  d: path("M11.74 17.096c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.prtv3ebme {
  stop-color: var(--svg-color--f6ebf9, #F6EBF9);
}

.q6qrptbzd {
  stop-color: var(--svg-color--f6e9f9, #F6E9F9);
  stop-opacity: 0;
}

.qdu-6ebcl {
  d: path("M19.99 18.002h-8c-1.66 0-3 1.34-3 3s1.34 3 3 3h1.5a3 3 0 0 0 2.5-1.34a3 3 0 0 0 2.5 1.34h1.5c1.66 0 3-1.34 3-3s-1.34-3-3-3");
}

.qo96s4jfk {
  stop-color: var(--svg-color--ff7612, #FF7612);
}

.qvxetsyer {
  stop-color: var(--svg-color--f88a5d, #F88A5D);
}

.rbv7ofauz {
  stop-color: var(--svg-color--beadcc, #BEADCC);
  stop-opacity: 0;
}

.riyil9b8h {
  d: path("m27.74 12.466l-1.78-2.08c-.97-1.199-3.006-3.935-5.32-5.15a9.96 9.96 0 0 0-4.65-1.14c-1.68 0-3.26.41-4.65 1.14c-1.568.733-4.505 4.201-5.33 5.15l-1.77 2.08a9.4 9.4 0 0 0-2.25 6.09v3.85c0 2.59 2.1 4.69 4.69 4.69H25.3c2.59 0 4.69-2.1 4.69-4.69v-3.85c0-2.23-.8-4.39-2.25-6.09");
}

.ru2_kbbzf {
  stop-color: var(--svg-color--e4d6e8, #E4D6E8);
  stop-opacity: 0;
}

.rzogcloxi {
  d: path("m20.45 19.572l3.46-2c.24-.14.54-.06.68.18s.06.54-.18.68l-3.46 2c-.24.14-.54.06-.68-.18a.493.493 0 0 1 .18-.68");
}

.sdotsmj7z {
  cx: 24.094px;
  cy: 6.897px;
  r: 3.897px;
}

.sm-syv1ai {
  stop-color: var(--svg-color--e08353, #E08353);
}

.smb3obb5g {
  stop-color: var(--svg-color--5a4969, #5A4969);
}

.sudh-ybkm {
  d: path("M19.99 16.892c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.sv9bqmvzf {
  stop-color: var(--svg-color--bf603d, #BF603D);
  stop-opacity: 0;
}

.u_cjtxt1h {
  d: path("M15.99 30.002c-3.87 0-7-3.13-7-7v-2h14v2c0 3.87-3.13 7-7 7");
}

.u35ucpbhl {
  stop-color: var(--svg-color--e1d2ee, #E1D2EE);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.uhnsqsi9g {
  cx: 20.467px;
  cy: 20.383px;
  r: 0.726px;
  fill: var(--svg-color--d6c8d9, #D6C8D9);
}

.v9i4ltcin {
  stop-color: var(--svg-color--ca4835, #CA4835);
}

.vbe4h-hnp {
  d: path("M11.99 16.892c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.vf4b6tbzp {
  stop-color: var(--svg-color--fc7c2b, #FC7C2B);
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.wdki8w5df {
  stop-color: var(--svg-color--fc7520, #FC7520);
}

.wmwhkckqr {
  stop-color: var(--svg-color--c8485b, #C8485B);
}

.x4ree7b7z {
  cx: 7.944px;
  cy: 6.955px;
  r: 2.453px;
}

.xcwmt0d-l {
  stop-color: var(--svg-color--c7a5e6, #C7A5E6);
}

.xupfqcc4z {
  stop-color: var(--svg-color--c7a5e6, #C7A5E6);
  stop-opacity: 0;
}

.ybz7z7c5a {
  stop-color: var(--svg-color--e16f15, #E16F15);
  stop-opacity: 0;
}

.ymbal8b0v {
  stop-color: var(--svg-color--c3b3d2, #C3B3D2);
}

.z17z3-a-u {
  stop-color: var(--svg-color--5c5458, #5C5458);
}

.zj-fvvinl {
  fill: var(--svg-color--f86121, #F86121);
  d: path("M19.74 17.096c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.zozkvbb0u {
  stop-color: var(--svg-color--a58eb9, #A58EB9);
}

</style>
