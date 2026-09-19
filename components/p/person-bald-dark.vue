<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i0pDHFc)"><path fill="url(#imWbyDc)" class="ro66myb7q"/></g><g filter="url(#ixEaMTM)"><path fill="url(#iG5X2eS)" class="vpyif3nsj"/></g><g filter="url(#i6iqqtc)"><path fill="url(#ibefzMd)" class="t0nbapbwj"/><path fill="url(#i3OH9jc)" class="t0nbapbwj"/></g><g filter="url(#iBTmYnb)"><path fill="url(#iyxSOFc)" class="drpjhzb9n"/></g><g filter="url(#i9nEnLb)"><path fill="url(#i1RDYAb)" class="cm6pjudsx"/><path fill="url(#inValFc)" class="cm6pjudsx"/><path fill="url(#ivICzbe)" class="cm6pjudsx"/><path fill="url(#iJYbnbA)" class="cm6pjudsx"/><path fill="url(#iR9QUlG)" class="cm6pjudsx"/><path fill="url(#i9SYdcv)" class="cm6pjudsx"/><path fill="url(#i1SExrd)" class="cm6pjudsx"/></g><g filter="url(#iCDLYgU)"><path fill="url(#i36v3Kc)" class="uv_00xk-b"/></g><g filter="url(#ig2TFLb)"><path class="pcq33-kar"/><path fill="url(#iyebmZd)" class="r1h9icb_r"/><path fill="url(#iOuvHae)" class="r1h9icb_r"/><path fill="url(#iwN3Byb)" class="r1h9icb_r"/><path fill="url(#iylgPme)" class="r1h9icb_r"/></g><g filter="url(#iJlT6me)"><path stroke="url(#i5FOJJe)" class="chhx72eea"/></g><path class="w3-ce0cvh"/><g filter="url(#i7bAkJc)"><path class="lwcj6hefi"/></g><g filter="url(#isu8DNb)"><path class="i0hksu3rj"/></g><path class="a_tkzvqzp"/><path fill="url(#iyfEjNe)" class="u9nzd2b_b"/><path class="p8saj6ajn"/><g filter="url(#ixcKVbd)"><path fill="url(#iZKEk3d)" class="xydyzk29w"/></g><g filter="url(#ijDN4ma)"><ellipse transform="rotate(-27.914 11.424 16.7)" class="egf6137gg"/><ellipse fill="url(#iWgAVOc)" transform="rotate(-27.914 11.424 16.7)" class="v6ymvabml"/></g><path class="mvb9yehmr"/><path fill="url(#i0c06Ib)" class="grfpa4b6s"/><path class="iz-zoxb_e"/><g filter="url(#iamUHJb)"><path class="l81j9lqcs"/><path fill="url(#iYA7Ige)" class="zxkz1hb_v"/></g><g filter="url(#i5Lj90c)"><path fill="url(#iSGsdhb)" class="dsd1-bbef"/></g><g filter="url(#iA8yVyb)"><path class="tmseji7rn"/></g><g filter="url(#iKa0TVd)"><path class="hfbmxsbun"/></g><g filter="url(#iMST4Bc)"><path fill="url(#iS5UerO)" class="f1cbh6beq"/></g><defs><radialGradient id="imWbyDc" cx="0" cy="0" r="1" gradientTransform="matrix(3.15625 0 0 5.09375 3.59 18.306)" gradientUnits="userSpaceOnUse"><stop class="id4--kb6v"/><stop offset="1" class="yx827m61z"/></radialGradient><radialGradient id="iG5X2eS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48723 .21943 -.29636 -2.00865 6.797 18.218)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="ia3l26u7t"/><stop offset="1" class="k-f7fichd"/></radialGradient><radialGradient id="i3OH9jc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.244 31.396 -18.037)scale(2.29666 2.22246)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="xuyenabum"/><stop offset="1" class="rmmi4abgs"/></radialGradient><radialGradient id="i1RDYAb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.13152 18.00003 -16.21274 -4.622 20.605 10.22)" gradientUnits="userSpaceOnUse"><stop class="ozcj-6bqn"/><stop offset="1" class="oyw7l4bwq"/></radialGradient><radialGradient id="inValFc" cx="0" cy="0" r="1" gradientTransform="scale(8.57064 8.17105)rotate(90 .1 2.47)" gradientUnits="userSpaceOnUse"><stop class="y14k4lb6j"/><stop offset="1" class="jtx2new2j"/></radialGradient><radialGradient id="ivICzbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.36514 10.5925 0 9.56 29.95)" gradientUnits="userSpaceOnUse"><stop class="utn1fco5u"/><stop offset="1" class="vgicvsb4x"/></radialGradient><radialGradient id="iJYbnbA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05461 19.43755 -18.9858 -2.98362 19.06 10.838)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="pih3_bc_p"/><stop offset="1" class="utkir-utb"/></radialGradient><radialGradient id="iR9QUlG" cx="0" cy="0" r="1" gradientTransform="matrix(.56137 -2.91744 3.26223 .62772 11.967 15.505)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="w8z128b_w"/><stop offset="1" class="y9j9od0au"/></radialGradient><radialGradient id="i9SYdcv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.91744 3.21246 0 20.434 15.599)" gradientUnits="userSpaceOnUse"><stop offset=".025" class="ky2i9gfwu"/><stop offset="1" class="rjxs4hg5m"/></radialGradient><radialGradient id="i1SExrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75 -4.02907 0 17.78 4.755)" gradientUnits="userSpaceOnUse"><stop class="b-c_m8lqv"/><stop offset="1" class="n7n-7s7mu"/></radialGradient><radialGradient id="iOuvHae" cx="0" cy="0" r="1" gradientTransform="matrix(-.93748 -4.46875 1.47905 -.31028 17.498 20.692)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></radialGradient><radialGradient id="iylgPme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 0 0 -.28125 17.217 20.911)" gradientUnits="userSpaceOnUse"><stop class="cn3fn4-mf"/><stop offset="1" class="dzll2bclm"/></radialGradient><radialGradient id="iyfEjNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53876 -2.44757 0 11.938 16.88)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="iWgAVOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01467 -.93704 1.12636 -.01764 11.395 17.296)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0c06Ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.068 16.874)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="iYA7Ige" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.992 3.705)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iS5UerO" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 4.71875 -11.46927 12.00094 17.154 8.286)" gradientUnits="userSpaceOnUse"><stop class="edfo-zbik"/><stop offset="1" class="xs1c20bnv"/></radialGradient><filter id="i0pDHFc" width="6" height="6.2" x="4" y="14.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.262745 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2068"/></filter><filter id="ixEaMTM" width="4.132" height="4.132" x="4.934" y="16.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".125"/></filter><filter id="i6iqqtc" width="6.2" height="6.2" x="22" y="14.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.14902 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2068"/></filter><filter id="iBTmYnb" width="4.632" height="4.632" x="22.887" y="15.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".25"/></filter><filter id="i9nEnLb" width="20.485" height="26.25" x="6.262" y="4.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.416667 0 0 0 0 0.331439 0 0 0 0 0.3125 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2068"/></filter><filter id="iCDLYgU" width="4.5" height="5.836" x="13.512" y="17.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".25"/></filter><filter id="ig2TFLb" width="3.7" height="5.2" x="14.15" y="16.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".05"/></filter><filter id="iJlT6me" width="6.619" height="2.54" x="12.691" y="23.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".075"/></filter><filter id="i7bAkJc" width="4.424" height="2.097" x="18.963" y="11.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0313726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2068"/></filter><filter id="isu8DNb" width="4.424" height="2.069" x="9.163" y="11.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0313726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2068"/></filter><filter id="ixcKVbd" width="1.512" height="1.614" x="12.169" y="16.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".1"/></filter><filter id="ijDN4ma" width="1.552" height="1.157" x="10.648" y="16.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".05"/></filter><filter id="iamUHJb" width="1.294" height="1.125" x="18.786" y="16.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".05"/></filter><filter id="i5Lj90c" width="1.316" height="1.357" x="20.438" y="16.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".1"/></filter><filter id="iA8yVyb" width="4.076" height="1.651" x="9.303" y="12.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".175"/></filter><filter id="iKa0TVd" width="3.97" height="1.737" x="19.241" y="12.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation=".175"/></filter><filter id="iMST4Bc" width="12.281" height="10.228" x="14.154" y="5.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2068" stdDeviation="1"/></filter><linearGradient id="ibefzMd" x1="27.09" x2="25" y1="15.619" y2="20.681" gradientUnits="userSpaceOnUse"><stop class="cyvijd74w"/><stop offset="1" class="esglvkblo"/></linearGradient><linearGradient id="iyxSOFc" x1="25.029" x2="25.717" y1="19.63" y2="17.317" gradientUnits="userSpaceOnUse"><stop class="x7wxsdz-p"/><stop offset="1" class="ysbscbc_r"/></linearGradient><linearGradient id="i36v3Kc" x1="14.765" x2="15.762" y1="20.323" y2="22.36" gradientUnits="userSpaceOnUse"><stop class="jf6cdtbcs"/><stop offset="1" class="ov28l_fpn"/></linearGradient><linearGradient id="iyebmZd" x1="13.809" x2="15.591" y1="20.65" y2="20.963" gradientUnits="userSpaceOnUse"><stop class="x6u8q5ddp"/><stop offset="1" class="jw_nm1tig"/></linearGradient><linearGradient id="iwN3Byb" x1="16" x2="16" y1="22.275" y2="20.806" gradientUnits="userSpaceOnUse"><stop class="lqhlhqbaf"/><stop offset="1" class="itvl883av"/></linearGradient><linearGradient id="i5FOJJe" x1="14.762" x2="15.294" y1="25.357" y2="24.009" gradientUnits="userSpaceOnUse"><stop class="zp5hfibqu"/><stop offset="1" class="c_abhxr9g"/></linearGradient><linearGradient id="iZKEk3d" x1="13.349" x2="12.754" y1="16.983" y2="17.349" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSGsdhb" x1="21.519" x2="20.934" y1="16.975" y2="17.335" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bald-dark" /></template>
<style>
.a_tkzvqzp {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.542 15.46a2.65 2.65 0 0 0-2.57 2.008a.52.52 0 0 0 .508.647h4.232a.436.436 0 0 0 .43-.516a2.66 2.66 0 0 0-2.6-2.139");
}

.b-c_m8lqv {
  stop-color: var(--svg-color--5b4947, #5B4947);
}

.c_abhxr9g {
  stop-color: var(--svg-color--574748, #574748);
  stop-opacity: 0;
}

.chhx72eea {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.39 23.307h-.001a.34.34 0 0 0-.407.07a.31.31 0 0 0-.034.4A3.65 3.65 0 0 0 16 25.407a3.65 3.65 0 0 0 3.052-1.63a.314.314 0 0 0-.035-.403a.34.34 0 0 0-.406-.067a5.6 5.6 0 0 1-2.611.619a5.66 5.66 0 0 1-2.61-.619Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm6pjudsx {
  d: path("M18.066 4.2h-4.147c-5.57 0-8.018 3.75-7.614 8.71l.7 10.69a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35l.67-10.69c.53-4.704-2.115-8.71-7.615-8.71");
}

.cn3fn4-mf {
  stop-color: var(--svg-color--685655, #685655);
}

.cyvijd74w {
  stop-color: var(--svg-color--675654, #675654);
}

.drpjhzb9n {
  d: path("M25.203 19.903a1.816 1.816 0 1 0 0-3.631a1.816 1.816 0 0 0 0 3.631");
}

.dsd1-bbef {
  d: path("M21.554 17.43a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.dzll2bclm {
  stop-color: var(--svg-color--685655, #685655);
  stop-opacity: 0;
}

.edfo-zbik {
  stop-color: var(--svg-color--6b5857, #6B5857);
}

.egf6137gg {
  cx: 11.424px;
  cy: 16.699px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.739px;
  ry: 0.374px;
}

.esglvkblo {
  stop-color: var(--svg-color--442a30, #442A30);
}

.f1cbh6beq {
  d: path("M22.967 7.536L17.699 8.77a2 2 0 0 0-1.545 1.947v1.747a1 1 0 0 0 .495.863l.572.335a.745.745 0 0 0 1.12-.642c0-.354.25-.659.595-.73l5.5-1.128c0-1.5-1.042-3.208-1.47-3.625");
}

.ft5dv1b6b {
  fill: none;
}

.grfpa4b6s {
  d: path("M20.072 15.985a1.664 1.664 0 0 1 1.604 2.102H18.46a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.671-1.664");
}

.hfbmxsbun {
  stroke: var(--svg-color--313131, #313131);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.736 13.33c-.5-.483-1.695-.917-3.02-.75");
}

.i0hksu3rj {
  fill: var(--svg-color--151414, #151414);
  d: path("M9.64 12.824a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.026a4.14 4.14 0 0 0-2.585.531q-.095.059-.14.09l-.031.022l-.005.004a.517.517 0 0 1-.633-.818z");
}

.ia3l26u7t {
  stop-color: var(--svg-color--2b1c20, #2B1C20);
}

.id4--kb6v {
  stop-color: var(--svg-color--382526, #382526);
}

.itvl883av {
  stop-color: var(--svg-color--391e2c, #391E2C);
  stop-opacity: 0;
}

.iz-zoxb_e {
  fill: var(--svg-color--000, #000);
  d: path("M19.12 17.649c0-.53.423-.953.952-.953c.53 0 .953.423.953.953c0 .159-.038.31-.106.438h-1.686a.86.86 0 0 1-.114-.438");
}

.izaac2bev {
  stop-color: var(--svg-color--6a5654, #6A5654);
  stop-opacity: 0;
}

.jf6cdtbcs {
  stop-color: var(--svg-color--321f22, #321F22);
}

.jtx2new2j {
  stop-color: var(--svg-color--523330, #523330);
  stop-opacity: 0;
}

.jw_nm1tig {
  stop-color: var(--svg-color--3e2928, #3E2928);
  stop-opacity: 0;
}

.k-f7fichd {
  stop-color: var(--svg-color--281315, #281315);
}

.kibsqob-j {
  stop-color: var(--svg-color--6a5654, #6A5654);
}

.ky2i9gfwu {
  stop-color: var(--svg-color--422628, #422628);
}

.l81j9lqcs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.95 16.337c.118.158-.13.352-.411.562c-.282.21-.491.36-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqhlhqbaf {
  stop-color: var(--svg-color--391e2c, #391E2C);
}

.lwcj6hefi {
  fill: var(--svg-color--151414, #151414);
  d: path("M22.96 13.027c-.327-.284-.707-.586-1.282-.767c-.567-.178-1.278-.226-2.26-.106a.517.517 0 0 0 .125 1.026c.897-.11 1.446-.053 1.824.066c.37.117.62.305.913.56a.517.517 0 1 0 .68-.779");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mvb9yehmr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.458 15.478c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.159a.43.43 0 0 1-.424-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.n7n-7s7mu {
  stop-color: var(--svg-color--4e3534, #4E3534);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ov28l_fpn {
  stop-color: var(--svg-color--341928, #341928);
}

.oyw7l4bwq {
  stop-color: var(--svg-color--3b262c, #3B262C);
}

.ozcj-6bqn {
  stop-color: var(--svg-color--543a36, #543A36);
}

.p8saj6ajn {
  fill: var(--svg-color--000, #000);
  d: path("M12.904 17.669c0-.54-.431-.97-.97-.97s-.969.43-.969.97a.96.96 0 0 0 .108.446h1.715a.96.96 0 0 0 .116-.446");
}

.pcq33-kar {
  fill: var(--svg-color--472f2d, #472F2D);
  d: path("m15.287 17.614l-.99 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.97-1.303l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.pih3_bc_p {
  stop-color: var(--svg-color--472e48, #472E48);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1h9icb_r {
  d: path("m15.287 17.614l-.99 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.97-1.303l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.rjxs4hg5m {
  stop-color: var(--svg-color--422628, #422628);
  stop-opacity: 0;
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.ro66myb7q {
  d: path("M7 21.088a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.s-ceiepmf {
  stop-color: var(--svg-color--654843, #654843);
}

.t0nbapbwj {
  d: path("M25 21.088a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.tmseji7rn {
  stroke: var(--svg-color--313131, #313131);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.778 13.245c.408-.303 1.689-.807 3.126-.681");
}

.u9nzd2b_b {
  d: path("M11.934 15.976a1.693 1.693 0 0 0-1.63 2.139h3.27q.059-.218.06-.446a1.704 1.704 0 0 0-1.7-1.693");
}

.utkir-utb {
  stop-color: var(--svg-color--472e48, #472E48);
}

.utn1fco5u {
  stop-color: var(--svg-color--39202d, #39202D);
}

.uv_00xk-b {
  d: path("m15.262 18.05l-1.204 3.006a1.005 1.005 0 0 0 .97 1.304h1.467c.687 0 1.173-.662.97-1.304l-1.125-3.005c-.213-.702-.855-.702-1.078 0");
}

.v6ymvabml {
  cx: 11.424px;
  cy: 16.699px;
  rx: 0.739px;
  ry: 0.374px;
}

.vgicvsb4x {
  stop-color: var(--svg-color--39202d, #39202D);
  stop-opacity: 0;
}

.vpyif3nsj {
  d: path("M7 19.903a1.816 1.816 0 1 0 0-3.631a1.816 1.816 0 0 0 0 3.631");
}

.w3-ce0cvh {
  fill: var(--svg-color--290118, #290118);
  d: path("M16 23.976a5.7 5.7 0 0 1-2.634-.624c-.26-.133-.54.16-.376.397A3.6 3.6 0 0 0 16 25.357a3.6 3.6 0 0 0 3.01-1.608c.164-.246-.116-.53-.376-.397a5.7 5.7 0 0 1-2.634.624");
}

.w8z128b_w {
  stop-color: var(--svg-color--381f28, #381F28);
}

.x6u8q5ddp {
  stop-color: var(--svg-color--3e2928, #3E2928);
}

.x7wxsdz-p {
  stop-color: var(--svg-color--422b2e, #422B2E);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xs1c20bnv {
  stop-color: var(--svg-color--6b5857, #6B5857);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xydyzk29w {
  d: path("M13.48 17.47c0-.547-.444-.912-.564-1.022l-.547.529l.336.685z");
}

.y14k4lb6j {
  stop-color: var(--svg-color--523330, #523330);
}

.y9j9od0au {
  stop-color: var(--svg-color--381f28, #381F28);
  stop-opacity: 0;
}

.ysbscbc_r {
  stop-color: var(--svg-color--4b3637, #4B3637);
}

.yx827m61z {
  stop-color: var(--svg-color--38282d, #38282D);
}

.zp5hfibqu {
  stop-color: var(--svg-color--574748, #574748);
}

.zxkz1hb_v {
  d: path("M19.95 16.337c.118.158-.13.352-.411.562c-.282.21-.491.36-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

</style>
