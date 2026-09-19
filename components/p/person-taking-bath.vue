<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="i6C39Ge" class="ox9mexb7l"/></defs><g class="ft5dv1b6b"><path class="jicduxbrm"/><g filter="url(#ijkBBlp)"><path fill="url(#i4Eh5eb)" class="ihelzqbvc"/><path fill="url(#iOQREjc)" class="ihelzqbvc"/></g><g filter="url(#ipIUjte)"><path class="y_zhlqb_p"/><path fill="url(#iO1e5Lc)" class="y9oy0tbgx"/></g><g filter="url(#iAJyACd)"><path class="ksrblrb2e"/><path fill="url(#iKccX5c)" class="noh05j73r"/><path fill="url(#im9OVLc)" class="noh05j73r"/></g><g filter="url(#ic1qs4z)"><circle fill="url(#iRexAge)" class="yzi2v60pl"/><circle fill="url(#i70jneW)" class="yzi2v60pl"/></g><g filter="url(#iodjwyx)"><path fill="url(#iEVJ3Kd)" clip-rule="evenodd" class="jco-mipgp"/></g><path fill="url(#iLjlsPx)" class="r3ex5mb_t"/><g filter="url(#iXVcXod)"><path fill="url(#i8iWMxb)" class="ro47j5zru"/><path fill="url(#iwDDc2c)" class="ro47j5zru"/></g><g filter="url(#iXun7eX)"><use href="#i6C39Ge"/><path fill="url(#iAoX9Ed)" class="vc_atkxfc"/><path fill="url(#iSexcnc)" class="vc_atkxfc"/><path fill="url(#iF5NeFe)" class="vc_atkxfc"/><path fill="url(#iEWWTUc)" class="vc_atkxfc"/><path fill="url(#iFZE58b)" class="vc_atkxfc"/></g><g filter="url(#iXun7eX)"><use href="#i6C39Ge"/><path fill="url(#iAoX9Ed)" class="vc_atkxfc"/><path fill="url(#iSexcnc)" class="vc_atkxfc"/><path fill="url(#iF5NeFe)" class="vc_atkxfc"/><path fill="url(#iEWWTUc)" class="vc_atkxfc"/><path fill="url(#iFZE58b)" class="vc_atkxfc"/></g><path fill="url(#i9xwyvb)" class="vmccthobf"/><path clip-rule="evenodd" class="eh5_xcb1g"/><g filter="url(#iVSNMLy)"><path clip-rule="evenodd" class="s6jkxbcbk"/></g><path class="d9knv0bfn"/><path fill="url(#ieUFrpd)" class="yur662b8n"/><path fill="url(#iaayQ5b)" class="ihl2lj8hu"/><ellipse fill="url(#ihScDWc)" transform="matrix(-.26584 .96402 .96427 .26493 8.66 11.313)" class="l--rvobkj"/><rect fill="url(#i9HZAie)" transform="scale(-1 1)rotate(45 -41.287 -13.075)" class="hrxlqmt6c"/><rect fill="url(#iwL7NEd)" transform="scale(-1 1)rotate(45 -41.287 -13.075)" class="hrxlqmt6c"/><rect fill="url(#i0csxTc)" transform="scale(-1 1)rotate(45 -41.287 -13.075)" class="hrxlqmt6c"/><rect transform="rotate(45 11.783 25.365)" class="kc2zshepl"/><rect fill="url(#i9Q7TNg)" transform="rotate(45 11.783 25.365)" class="xoxykt52g"/><rect fill="url(#iBlsrEu)" transform="rotate(45 11.783 25.365)" class="xoxykt52g"/><g filter="url(#iu3fKKP)"><path fill="url(#iDU2Kzb)" class="zoyoxvbut"/></g><path fill="url(#ibgQKHl)" class="zoyoxvbut"/><path fill="url(#ipY2Bqc)" class="zoyoxvbut"/><g filter="url(#ig542eA)"><rect fill="url(#i3GpgEb)" class="v6ymu42gc"/><rect fill="url(#iIQ7Due)" class="v6ymu42gc"/></g><rect fill="url(#ihYMqfc)" class="v6ymu42gc"/><g filter="url(#iikHHSY)"><path stroke="url(#iMfo6ub)" class="plgla_1qf"/></g><g filter="url(#iToYCZb)"><path stroke="url(#ilUuA7b)" class="k1dzkgluc"/></g><path fill="url(#iYIHqTd)" class="kf-xy-p4r"/><path fill="url(#iuw6Ucc)" class="kf-xy-p4r"/><defs><radialGradient id="i4Eh5eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.09375 .5802 0 20.803 15.15)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="jsra9fbbr"/><stop offset="1" class="k1itueb8x"/></radialGradient><radialGradient id="iOQREjc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 -3.09376 1.67378 -.81152 23.521 14.713)" gradientUnits="userSpaceOnUse"><stop class="fw2vsuwda"/><stop offset="1" class="hmr093twd"/></radialGradient><radialGradient id="iO1e5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-45.372 16.754 -19.197)scale(6.80605 3.84932)" gradientUnits="userSpaceOnUse"><stop class="xy0op_eyz"/><stop offset="1" class="p53pr-blg"/></radialGradient><radialGradient id="iKccX5c" cx="0" cy="0" r="1" gradientTransform="rotate(-150.994 14.7 4.713)scale(3.60894 4.34333)" gradientUnits="userSpaceOnUse"><stop class="v7qdu5boj"/><stop offset="1" class="kdd3vfboh"/></radialGradient><radialGradient id="im9OVLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 2.625 -1.48498 .60106 19.49 13.838)" gradientUnits="userSpaceOnUse"><stop class="xwt5g5sto"/><stop offset="1" class="x484pmbxx"/></radialGradient><radialGradient id="iRexAge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90038 -2.5625 2.1013 -1.55835 20.752 15.874)" gradientUnits="userSpaceOnUse"><stop class="nmlj7qb8u"/><stop offset="1" class="wijlc3r_o"/></radialGradient><radialGradient id="i70jneW" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -2.34375 2.00586 1.12328 16.846 16.405)" gradientUnits="userSpaceOnUse"><stop class="n35yqc9wi"/><stop offset="1" class="e9nymn0gr"/></radialGradient><radialGradient id="iEVJ3Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-138.668 11.431 4.377)scale(4.20282 3.66642)" gradientUnits="userSpaceOnUse"><stop class="fgfvt8_za"/><stop offset="1" class="kb1q69u9p"/></radialGradient><radialGradient id="iLjlsPx" cx="0" cy="0" r="1" gradientTransform="rotate(67.286 -3.046 13.051)scale(.85525 1.0892)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iwDDc2c" cx="0" cy="0" r="1" gradientTransform="matrix(.63624 -.84974 1.03472 .77475 6.913 13.893)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iAoX9Ed" cx="0" cy="0" r="1" gradientTransform="rotate(175.461 3.644 7.914)scale(3.41731 4.99414)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iSexcnc" cx="0" cy="0" r="1" gradientTransform="matrix(2.57183 -1.32663 3.48588 6.75783 3.247 13.916)" gradientUnits="userSpaceOnUse"><stop class="y125gvbnz"/><stop offset="1" class="ldg9ygbfk"/></radialGradient><radialGradient id="iF5NeFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.76626 -1.4645 .6754 .81457 3.259 11.249)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="iEWWTUc" cx="0" cy="0" r="1" gradientTransform="matrix(.04798 .873 -1.26069 .0693 5.53 8.375)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="iFZE58b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.375 -.76564 .34888 -1.08221 5.584 16.338)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="pw1txj0qv"/><stop offset="1" class="s9yijwaob"/></radialGradient><radialGradient id="i9xwyvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.27066 .32316 -.52553 2.06637 6.495 14.041)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ieUFrpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.22051 .2628 -.51058 -.42843 8.894 11.678)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iaayQ5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.20161 .24027 -.51997 -.4363 9.05 11.534)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iwL7NEd" cx="0" cy="0" r="1" gradientTransform="rotate(79.16 -.565 1.44)scale(1.58615 1.72717)" gradientUnits="userSpaceOnUse"><stop class="lkqdv0bwp"/><stop offset="1" class="vou8iltko"/></radialGradient><radialGradient id="i0csxTc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.442 2.4 1.929)scale(1.40065 .72809)" gradientUnits="userSpaceOnUse"><stop class="go679fbfb"/><stop offset="1" class="jo92-ub-i"/></radialGradient><radialGradient id="iBlsrEu" cx="0" cy="0" r="1" gradientTransform="rotate(-47.663 40.378 1.498)scale(.6726 1.0441)" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></radialGradient><radialGradient id="iDU2Kzb" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56247 -.06247 .03888 -9.68481 25.99 22.307)" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="ibgQKHl" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -39.1562 0 17.115 19.37)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="mh1kw6b0u"/><stop offset="1" class="mg_zulb9j"/></radialGradient><radialGradient id="i3GpgEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -15.4957 0 25.24 16.65)" gradientUnits="userSpaceOnUse"><stop class="ypx_bsb1m"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iMfo6ub" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71874 10.18756 -7.15636 -4.71965 28.771 3.62)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="ilUuA7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -3.53125 2.69792 1.14602 19.539 6.572)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="iYIHqTd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53418 0 0 -3.55867 20.646 8.611)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="yi5996bix"/><stop offset=".717" class="wvcdyrpfm"/></radialGradient><filter id="ijkBBlp" width="7.367" height="4.959" x="17.412" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.635294 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="ipIUjte" width="9.125" height="15.5" x="17.928" y="1.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="iAJyACd" width="14.805" height="6.438" x="11.178" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.678431 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="ic1qs4z" width="5.582" height="5.582" x="16.06" y="13.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24055" stdDeviation=".25"/></filter><filter id="iodjwyx" width="6.341" height="6.485" x="11.287" y="12.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24055" stdDeviation=".25"/></filter><filter id="iXVcXod" width="7.784" height="6.593" x="3.981" y="9.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.533333 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="iXun7eX" width="5.587" height="8.617" x="2.464" y="8.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="iVSNMLy" width=".814" height="1.199" x="7.137" y="10.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="iu3fKKP" width="28.578" height="11" x="3.771" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="3" dy="-1"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="ig542eA" width="28.344" height="2.496" x="2.662" y="15.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.698039 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24055"/></filter><filter id="iikHHSY" width="5.047" height="14.518" x="21.787" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24055" stdDeviation=".25"/></filter><filter id="iToYCZb" width="2.999" height="4.468" x="17.976" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24055" stdDeviation=".25"/></filter><linearGradient id="i8iWMxb" x1="7.879" x2="10.356" y1="14.191" y2="11.575" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="ihScDWc" x1="-.009" x2=".225" y1=".062" y2=".139" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i9HZAie" x1="1.641" x2="-.116" y1="2.961" y2="3.171" gradientUnits="userSpaceOnUse"><stop class="t7wbu9b2k"/><stop offset="1" class="t9935ox4b"/></linearGradient><linearGradient id="i9Q7TNg" x1="11.468" x2="13.015" y1="28.867" y2="28.624" gradientUnits="userSpaceOnUse"><stop class="gbuoa-pfp"/><stop offset="1" class="h8mgf7b3a"/></linearGradient><linearGradient id="ipY2Bqc" x1="16.56" x2="16.56" y1="17.807" y2="19.213" gradientUnits="userSpaceOnUse"><stop class="nihdd8-bi"/><stop offset="1" class="x6h_eubpf"/></linearGradient><linearGradient id="iIQ7Due" x1="2.865" x2="12.115" y1="17.244" y2="17.244" gradientUnits="userSpaceOnUse"><stop class="d673tl90q"/><stop offset="1" class="f-q8xrbdi"/></linearGradient><linearGradient id="ihYMqfc" x1="17.928" x2="17.928" y1="18.154" y2="17.619" gradientUnits="userSpaceOnUse"><stop class="b0b_4h8fx"/><stop offset="1" class="vngbibvro"/></linearGradient><linearGradient id="iuw6Ucc" x1="19.412" x2="19.412" y1="8.611" y2="8.104" gradientUnits="userSpaceOnUse"><stop class="dcrtohb5r"/><stop offset="1" class="k3-gog70w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-taking-bath" /></template>
<style>
.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.b0b_4h8fx {
  stop-color: var(--svg-color--b1a1c2, #B1A1C2);
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.d673tl90q {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.d9knv0bfn {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.138 11.429l-.798.95c-.377-.315-.503-.784-.283-1.046c.22-.263.704-.22 1.08.096");
}

.dcrtohb5r {
  stop-color: var(--svg-color--807f86, #807F86);
}

.e9nymn0gr {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
  stop-opacity: 0;
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.eh5_xcb1g {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M9.606 13.045a.156.156 0 0 0 .171.14c.417-.04.753-.323.852-.42a.157.157 0 1 0-.218-.225c-.085.083-.356.303-.664.333a.157.157 0 0 0-.14.172");
}

.f-q8xrbdi {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
  stop-opacity: 0;
}

.fgfvt8_za {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fw2vsuwda {
  stop-color: var(--svg-color--ffd940, #FFD940);
}

.gbuoa-pfp {
  stop-color: var(--svg-color--807d83, #807D83);
}

.go679fbfb {
  stop-color: var(--svg-color--bebac2, #BEBAC2);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h8mgf7b3a {
  stop-color: var(--svg-color--807d83, #807D83);
  stop-opacity: 0;
}

.hmr093twd {
  stop-color: var(--svg-color--ffd940, #FFD940);
  stop-opacity: 0;
}

.hrxlqmt6c {
  width: 1.608px;
  height: 5.132px;
  rx: 0.804px;
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.ihelzqbvc {
  d: path("M18.502 13.578a2.288 2.288 0 0 1 4.216-.309l1.811 3.6h-7.117z");
}

.ihl2lj8hu {
  d: path("M8.807 11.823a1 1 0 0 1-.072-.055c-.179-.15-.26-.346-.182-.44c.079-.093.287-.047.465.103q.036.03.066.062z");
}

.jco-mipgp {
  fill-rule: evenodd;
  d: path("M17.128 15.157a2.32 2.32 0 0 0-.631 2.789a2.742 2.742 0 1 1 .631-2.789");
}

.jicduxbrm {
  fill: var(--svg-color--d5982d, #D5982D);
  d: path("m8.301 15.657l1.422-1.034l1.332 1.832l-1.422 1.034z");
}

.jo92-ub-i {
  stop-color: var(--svg-color--968da0, #968DA0);
  stop-opacity: 0;
}

.jsra9fbbr {
  stop-color: var(--svg-color--f5b336, #F5B336);
}

.k1dzkgluc {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.226 3.385c-.458.406-1.375 1.612-1.375 3.187");
}

.k1itueb8x {
  stop-color: var(--svg-color--ffc42a, #FFC42A);
}

.k3-gog70w {
  stop-color: var(--svg-color--8f9198, #8F9198);
  stop-opacity: 0;
}

.kb1q69u9p {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
  stop-opacity: 0;
}

.kc2zshepl {
  width: 1.608px;
  height: 5.132px;
  x: 11.783px;
  y: 25.365px;
  fill: var(--svg-color--735f86, #735F86);
  rx: 0.804px;
}

.kdd3vfboh {
  stop-color: var(--svg-color--66ebff, #66EBFF);
  stop-opacity: 0;
}

.kf-xy-p4r {
  d: path("M21.092 8.611c.279 0 .508-.23.456-.504c-.25-1.307-1.37-2.293-2.714-2.293c-1.345 0-2.465.986-2.714 2.293c-.053.274.177.504.456.504z");
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.ksrblrb2e {
  fill: var(--svg-color--4bd1f1, #4BD1F1);
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.658.615a2.5 2.5 0 0 0 1.686-.64c.511.615 1.402 1.023 2.415 1.023c1.586 0 2.871-.998 2.871-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.505.247-2.024.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.928-.902c-.531 0-1.022.159-1.417.428a.107.107 0 0 1-.153-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.l--rvobkj {
  rx: 0.081px;
  ry: 0.11px;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.ldg9ygbfk {
  stop-color: var(--svg-color--fca123, #FCA123);
  stop-opacity: 0;
}

.lkqdv0bwp {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
}

.mg_zulb9j {
  stop-color: var(--svg-color--a887c7, #A887C7);
}

.mh1kw6b0u {
  stop-color: var(--svg-color--bba9cd, #BBA9CD);
  stop-opacity: 0;
}

.n35yqc9wi {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nihdd8-bi {
  stop-color: var(--svg-color--a090b0, #A090B0);
}

.nmlj7qb8u {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
}

.noh05j73r {
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.706-1.475a2.5 2.5 0 0 0 1.658.615a2.5 2.5 0 0 0 1.686-.64c.511.615 1.402 1.023 2.415 1.023c1.586 0 2.871-.998 2.871-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.505.247-2.024.647a.107.107 0 0 1-.15-.019c-.431-.546-1.134-.902-1.928-.902c-.531 0-1.022.159-1.417.428a.107.107 0 0 1-.153-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.ox9mexb7l {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M6.4 8.55a1.29 1.29 0 0 0-1.35.48c-.649.865-.458 1.217-1.24 1.836c-.825.654-1.106 1.083-1.236 1.55l-.003.01c-.128.46-.394 1.412 1.016 2.595c1.299 1.09 2.374 1.202 2.807 1.183l-.021.058c-.107.29.053.58.343.687c.248.09.56-.058.766-.402c.236-.392.402-.686.53-.919a.31.31 0 0 0-.073-.389l-1.07-.897c-.45-.378-.452-.922-.415-1.13c-.453-.405-.547-.727-.464-1.055c.138-.542.33-.585 1.049-1.555c.722-.975.187-1.847-.638-2.053");
}

.p_197nrym {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
  stop-opacity: 0;
}

.p53pr-blg {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
  stop-opacity: 0;
}

.plgla_1qf {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M22.303 2.666c1.218-.052 3.656.94 3.656 3.766v9.375");
}

.pw1txj0qv {
  stop-color: var(--svg-color--e8653b, #E8653B);
}

.r3ex5mb_t {
  d: path("M9.89 10.863a1.26 1.26 0 0 1-.647-.12l-.145.172l1.082.907c.304-.096.531-.409.408-.662c-.106-.216-.364-.337-.698-.297");
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.ro47j5zru {
  d: path("M8.784 10.302c-.801-.61-1.382-.671-1.59-.645L4.182 13.25l2.99 2.611c2.739.878 4.962-1.594 4.543-2.593c-.418-1-2.003-2.26-2.93-2.965");
}

.s6jkxbcbk {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M7.731 11.09a1 1 0 0 1 .16-.222a.188.188 0 1 0-.256-.276a1.3 1.3 0 0 0-.234.317c-.079.143-.15.328-.163.532a.188.188 0 1 0 .375.023a.9.9 0 0 1 .118-.375");
}

.s9yijwaob {
  stop-color: var(--svg-color--faa030, #FAA030);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.t7wbu9b2k {
  stop-color: var(--svg-color--887a96, #887A96);
}

.t9935ox4b {
  stop-color: var(--svg-color--a9a6ac, #A9A6AC);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v6ymu42gc {
  width: 27.844px;
  height: 2.246px;
  x: 2.662px;
  y: 15.908px;
  rx: 1.123px;
}

.v7qdu5boj {
  stop-color: var(--svg-color--66ebff, #66EBFF);
}

.vc_atkxfc {
  d: path("M6.4 8.55a1.29 1.29 0 0 0-1.35.48c-.649.865-.458 1.217-1.24 1.836c-.825.654-1.106 1.083-1.236 1.55l-.003.01c-.128.46-.394 1.412 1.016 2.595c1.299 1.09 2.374 1.202 2.807 1.183l-.021.058c-.107.29.053.58.343.687c.248.09.56-.058.766-.402c.236-.392.402-.686.53-.919a.31.31 0 0 0-.073-.389l-1.07-.897c-.45-.378-.452-.922-.415-1.13c-.453-.405-.547-.727-.464-1.055c.138-.542.33-.585 1.049-1.555c.722-.975.187-1.847-.638-2.053");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmccthobf {
  d: path("m7.944 14.14l-1.545-.968a.912.912 0 0 0 1.545.969");
}

.vn7ncpb8d {
  stop-color: var(--svg-color--e1daea, #E1DAEA);
}

.vngbibvro {
  stop-color: var(--svg-color--bbb2c3, #BBB2C3);
  stop-opacity: 0;
}

.vou8iltko {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
  stop-opacity: 0;
}

.wijlc3r_o {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
  stop-opacity: 0;
}

.wvcdyrpfm {
  stop-color: var(--svg-color--929192, #929192);
}

.x484pmbxx {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
  stop-opacity: 0;
}

.x6h_eubpf {
  stop-color: var(--svg-color--bcb0c8, #BCB0C8);
  stop-opacity: 0;
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xoxykt52g {
  width: 1.608px;
  height: 5.132px;
  x: 11.783px;
  y: 25.365px;
  rx: 0.804px;
}

.xwt5g5sto {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
}

.xy0op_eyz {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
}

.y_zhlqb_p {
  fill: var(--svg-color--adadad, #ADADAD);
  d: path("M24.953 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.y125gvbnz {
  stop-color: var(--svg-color--f69637, #F69637);
}

.y9oy0tbgx {
  d: path("M24.953 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.yur662b8n {
  d: path("m8.65 12.01l-.004-.002c-.308-.259-.447-.6-.31-.763c.136-.163.496-.085.804.173l.004.003z");
}

.yzi2v60pl {
  cx: 18.851px;
  cy: 16.73px;
  r: 2.291px;
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zoyoxvbut {
  d: path("m5.228 22.376l-1.457-4.57H29.35l-1.478 4.59a7.8 7.8 0 0 1-7.425 5.41H12.66a7.8 7.8 0 0 1-7.431-5.43");
}

</style>
