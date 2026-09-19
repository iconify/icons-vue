<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9uUMsb)" transform="rotate(39.16 13.997 8.178)" class="q9lfvvodz"/><path fill="url(#iXglsLd)" transform="rotate(39.16 13.997 8.178)" class="q9lfvvodz"/><path fill="url(#idLUlRy)" class="hwzw3zciy"/><g filter="url(#idSyYBb)"><path fill="url(#i7PqCec)" class="huxgy52dn"/></g><path clip-rule="evenodd" class="sfohnzadd"/><g filter="url(#iXi3ztb)"><path clip-rule="evenodd" class="q7ii74hsz"/></g><g filter="url(#iAsofyc)"><path fill="url(#iV6vu8b)" class="m66qk8fqg"/></g><path fill="url(#iDQjt8P)" class="huthje_2d"/><g filter="url(#in9y0Yd)"><path class="wbqhbnx3h"/><path fill="url(#iBzScEz)" class="i4-a69bia"/></g><path fill="url(#i6ZXxUb)" class="qxclbyb0i"/><path fill="url(#iHRAy1b)" class="mwthr4bcb"/><path fill="url(#iTihAmu)" class="mwthr4bcb"/><path fill="url(#ibXRXTK)" class="mwthr4bcb"/><path fill="url(#ijqWJ4d)" class="mwthr4bcb"/><g filter="url(#imtl7Mc)"><path fill="url(#iPeN8Bc)" class="bsuhdrn-y"/><path fill="url(#ixpcCfb)" class="bsuhdrn-y"/><path fill="url(#iti91we)" class="bsuhdrn-y"/></g><g filter="url(#ioYKYje)"><rect fill="url(#ihh4b9c)" class="id6o8gown"/><rect fill="url(#i9Ds08Z)" class="id6o8gown"/><rect fill="url(#i31Yf1d)" class="id6o8gown"/><rect fill="url(#it06nNW)" class="id6o8gown"/></g><g filter="url(#itRvJle)"><rect transform="rotate(-21.787 18.807 13.536)" class="s60dn4bjo"/></g><path fill="url(#i2xP5tb)" class="xfd7geb6e"/><path fill="url(#i68HH3b)" class="xfd7geb6e"/><path fill="url(#i5HrUZb)" class="xfd7geb6e"/><g filter="url(#idLOU9o)"><path fill="url(#iD5Lhve)" class="b20oxnbwe"/></g><g filter="url(#iW3sTue)"><path fill="url(#itmORpb)" class="tstd-ffbk"/><path fill="url(#ira5Q6c)" class="tstd-ffbk"/><path fill="url(#iJ5Tsad)" class="tstd-ffbk"/></g><g filter="url(#iF7qZbb)"><path class="vrk85rtsc"/></g><g filter="url(#iVoI13G)"><path fill="url(#iOcHhAe)" class="m6itjrmsd"/></g><path class="rwr3k-bxu"/><path fill="url(#isKbdle)" class="b87ywhbww"/><path fill="url(#iRUvWAc)" class="f7dz-ob4n"/><path class="cpdqrjb_c"/><defs><radialGradient id="i9uUMsb" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 4.8 9.653)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="xrxozkb3i"/><stop offset="1" class="qx5zm9big"/></radialGradient><radialGradient id="idLUlRy" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 5.737 10.505)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="q8kvbpx8t"/><stop offset="1" class="ez8jvgb-h"/></radialGradient><radialGradient id="i7PqCec" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 7.777 5.458)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="hj5q0lb4p"/><stop offset="1" class="p0r8r5bwk"/></radialGradient><radialGradient id="iV6vu8b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 1.21872 -1.51845 -5.21735 17.648 6.156)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="lelniimio"/><stop offset="1" class="lfhr9hbju"/></radialGradient><radialGradient id="iDQjt8P" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.14 7.406)" gradientUnits="userSpaceOnUse"><stop class="mx8nfvb1t"/><stop offset="1" class="z0ce-5bzk"/></radialGradient><radialGradient id="iBzScEz" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.729 14.99)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="cpjrx4bdc"/><stop offset="1" class="gezrebbgs"/></radialGradient><radialGradient id="i6ZXxUb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -51.266 46.193)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="ibXRXTK" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 12.429 22.5)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="ijqWJ4d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 10.616 22.405)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iPeN8Bc" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 6.76 15.172)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="ixpcCfb" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.636 10.797)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="iti91we" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 30.835 23.593)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="i9Ds08Z" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 26.835 16.624)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="i31Yf1d" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 3.554 17.095)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="it06nNW" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.241 16.874)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="i2xP5tb" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 7.858 10.86)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iD5Lhve" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 13.924 21.437)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="ira5Q6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 29.46 29.405)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iOcHhAe" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 14.46 10.624)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="r_erdlb4g"/><stop offset="1" class="w1kjbmbah"/></radialGradient><radialGradient id="isKbdle" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 16.827 8.233)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="g3_fttbxk"/><stop offset="1" class="brpcnabhe"/></radialGradient><radialGradient id="iRUvWAc" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 16.774 7.968)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="idSyYBb" width="4.364" height="4.439" x="13.504" y="5.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.52549 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="iXi3ztb" width=".763" height=".367" x="16.529" y="7.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.243137 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="iAsofyc" width="5.022" height="4.224" x="13.126" y="4.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.490196 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="in9y0Yd" width="6.377" height="6.141" x="8.858" y="9.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.466667 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23061" result="effect2_innerShadow_3987_23061"/></filter><filter id="imtl7Mc" width="27.983" height="6.037" x="1.343" y="20.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="ioYKYje" width="24.059" height="2.191" x="3.17" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="itRvJle" width="1.234" height=".876" x="18.902" y="13.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.701961 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="idLOU9o" width="6.802" height="6.803" x="7.621" y="19.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="iW3sTue" width="27.983" height="6.037" x="1.243" y="24.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="iF7qZbb" width="6.678" height="4.108" x="14.069" y="11.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.607843 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><filter id="iVoI13G" width="3.882" height="3.705" x="12.087" y="9.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.25098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23061"/></filter><linearGradient id="iXglsLd" x1="15.872" x2="15.158" y1="9.413" y2="9.39" gradientUnits="userSpaceOnUse"><stop class="ny2hkubeh"/><stop offset="1" class="ro828ibvp"/></linearGradient><linearGradient id="iHRAy1b" x1="24.335" x2="7.085" y1="19.343" y2="24.718" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iTihAmu" x1="26.429" x2="25.726" y1="20.905" y2="20.905" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="ihh4b9c" x1="15.299" x2="15.679" y1="15.749" y2="19.28" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="i68HH3b" x1="16.452" x2="16.866" y1="16.784" y2="17.179" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="i5HrUZb" x1="18.804" x2="18.468" y1="16.468" y2="16.116" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="itmORpb" x1="17.741" x2="12.023" y1="23.874" y2="33.968" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="iJ5Tsad" x1="17.304" x2="17.304" y1="30.437" y2="30.155" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-rowing-boat" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.b20oxnbwe {
  d: path("M10.65 20.8a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 0 1-2.711-2.711z");
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.b87ywhbww {
  d: path("M17.004 8.276c.02-.037.038-.064.052-.113c.047-.177-.022-.354-.17-.394c-.138-.037-.296.08-.343.257a.6.6 0 0 0-.012.123z");
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.brpcnabhe {
  stop-color: var(--svg-color--aa8d86, #AA8D86);
}

.bsuhdrn-y {
  d: path("M2.788 21.421C2.013 20.996 1.534 21 1.343 21v5.938h27.883V21c-1.563 0-2.215 1.157-3.532 1.157c-1.316 0-2.187-1.157-3.546-1.157c-1.118 0-2.243 1.157-3.508 1.157c-.973 0-2.204-1.157-3.391-1.157c-1.258 0-2.262 1.157-3.398 1.157c-.559 0-.836-.102-1.54-.438c-.703-.336-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.03.515-1.656.515s-1.031-.203-2-.734");
}

.cpdqrjb_c {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.83 7.884c.016-.037.069-.049.118-.027s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.106");
}

.cpjrx4bdc {
  stop-color: var(--svg-color--e03932, #E03932);
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.dzuixsuao {
  stop-color: var(--svg-color--55beff, #55BEFF);
  stop-opacity: 0;
}

.e_s-6on8g {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
  stop-opacity: 0;
}

.e21-2rm4b {
  stop-color: var(--svg-color--659941, #659941);
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.ez8jvgb-h {
  stop-color: var(--svg-color--e7a740, #E7A740);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.f7dz-ob4n {
  d: path("M16.925 8.254q.045-.05.061-.11c.027-.098-.018-.205-.097-.226s-.169.039-.198.147a.3.3 0 0 0-.002.126z");
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3_fttbxk {
  stop-color: var(--svg-color--81504c, #81504C);
}

.gezrebbgs {
  stop-color: var(--svg-color--e03932, #E03932);
  stop-opacity: 0;
}

.hj5q0lb4p {
  stop-color: var(--svg-color--ffd43f, #FFD43F);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.huthje_2d {
  d: path("M15.203 7.048a.625.625 0 0 0-.373 1.175z");
}

.huxgy52dn {
  d: path("M15.216 10.14c-.915-.454-1.536-1.235-1.712-1.618l.664-1.593a1.2 1.2 0 0 1 1.033-.738l1.657-.11c.129-.008.262-.002.372.067c.287.183.575.645.368 1.476c-.228 1.08-.5 1.743-.749 2.226c-.177.345-.533.572-.915.506a3.2 3.2 0 0 1-.718-.217");
}

.hwzw3zciy {
  d: path("M17.516 8.534c-.081-.146-.066-.411-.047-.503l-.445 1.019c.14.074.378.14.516-.031c.097-.121.078-.301-.024-.485");
}

.i4-a69bia {
  d: path("M10.452 11.046c-1.006 1.231-1.414 2.668-1.594 3.274l3.993 1.25c.125-1.024.75-2.72 1.172-3.375c.421-.657.488-.872.554-1.348s-.255-1.195-1.336-1.395c-.843-.156-1.854.45-2.789 1.594");
}

.id6o8gown {
  width: 23.859px;
  height: 2.191px;
  x: 3.37px;
  y: 16px;
  rx: 1.095px;
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.lelniimio {
  stop-color: var(--svg-color--ffce38, #FFCE38);
}

.lfhr9hbju {
  stop-color: var(--svg-color--ffa738, #FFA738);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m66qk8fqg {
  d: path("M13.157 8.04c.084-.194.295-.227.39-.219c-.39-.766-.086-2.687.649-3.047a1.77 1.77 0 0 1 1.578.024c.242.132.566.445 1.27.41c.645-.032 1 .332 1.003.691c.004.36-.117.844-.637.961s-.757-.07-1.394-.148c-.492-.06-.866.277-.988.468c-.184.29-.616.915-.75 1.137c-.168.277-.407.402-.73.34c-.325-.062-.497-.375-.392-.617");
}

.m6itjrmsd {
  d: path("M12.288 11.546c.6.719 1.333 1.555 1.625 1.883l1.656-1.484c-.33-.396-1.117-1.304-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.671.687-.195 1.367");
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mwthr4bcb {
  d: path("m4.517 17.458l21.724-.021v6.25L8.233 23.57z");
}

.mx8nfvb1t {
  stop-color: var(--svg-color--ffcc3f, #FFCC3F);
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.ny2hkubeh {
  stop-color: var(--svg-color--d27d3c, #D27D3C);
}

.p0r8r5bwk {
  stop-color: var(--svg-color--ffad2d, #FFAD2D);
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.q7ii74hsz {
  fill: var(--svg-color--bf6559, #BF6559);
  fill-rule: evenodd;
  d: path("M17.15 7.422a.72.72 0 0 0-.488-.027a.1.1 0 0 1-.066-.19a.92.92 0 0 1 .637.035a.1.1 0 0 1-.083.182");
}

.q8kvbpx8t {
  stop-color: var(--svg-color--ffd13f, #FFD13F);
}

.q9lfvvodz {
  d: path("M13.997 8.178h1.744v2h-1.744z");
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.qx5zm9big {
  stop-color: var(--svg-color--ffab2a, #FFAB2A);
}

.qxclbyb0i {
  d: path("M8.882 14.202c-.242.895-.203 1.762-.11 2.024l6.31-.063z");
}

.r_erdlb4g {
  stop-color: var(--svg-color--ff9954, #FF9954);
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.ro828ibvp {
  stop-color: var(--svg-color--d27d3c, #D27D3C);
  stop-opacity: 0;
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.rwr3k-bxu {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.93 8.256c.047.012.098-.027.123-.083l.003-.01c.066-.247-.096-.438-.294-.49c-.19-.052-.435.03-.5.277l-.003.01c-.016.059.008.118.065.133z");
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.s60dn4bjo {
  width: 1.28px;
  height: 0.637px;
  x: 18.807px;
  y: 13.536px;
  fill: var(--svg-color--f4c03b, #F4C03B);
  rx: 0.318px;
}

.sfohnzadd {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M16.264 8.943a.1.1 0 0 1 .132.05a.72.72 0 0 0 .34.325a.1.1 0 1 1-.08.183a.9.9 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.tstd-ffbk {
  d: path("M2.788 24.921c-.775-.425-1.254-.422-1.445-.422v5.938h27.883v-5.938c-1.563 0-2.215 1.157-3.532 1.157c-1.316 0-2.187-1.157-3.546-1.157c-1.118 0-2.243 1.157-3.508 1.157c-.973 0-2.204-1.157-3.391-1.157c-1.258 0-2.262 1.157-3.398 1.157c-.559 0-.836-.102-1.54-.438c-.703-.336-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.03.515-1.656.515s-1.031-.203-2-.734");
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.vrk85rtsc {
  fill: var(--svg-color--ffd839, #FFD839);
  d: path("M15.788 14.257c-.712-.331-1.443-.966-1.719-1.242l1.282-1.192c1.156 1.11 2.374 1.279 2.683 1.352c.395.094 1.538.3 2.168.73c.516.352.38.993.07 1.266c-.253.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.w1kjbmbah {
  stop-color: var(--svg-color--f9663c, #F9663C);
}

.wbqhbnx3h {
  fill: var(--svg-color--fa623e, #FA623E);
  d: path("M10.452 11.046c-1.006 1.231-1.414 2.668-1.594 3.274l3.993 1.25c.125-1.024.75-2.72 1.172-3.375c.421-.657.488-.872.554-1.348s-.255-1.195-1.336-1.395c-.843-.156-1.854.45-2.789 1.594");
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.xfd7geb6e {
  d: path("M20.618 12.752a.59.59 0 0 1 .829.839l-8.439 8.331a.59.59 0 0 1-.828-.839z");
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.xrxozkb3i {
  stop-color: var(--svg-color--fe8a23, #FE8A23);
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.z0ce-5bzk {
  stop-color: var(--svg-color--ffb92f, #FFB92F);
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>
