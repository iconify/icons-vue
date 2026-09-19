<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixTnbdb)"><path fill="url(#iXgkyYc)" class="tou0_8b9a"/><path fill="url(#iOBLwDc)" class="tou0_8b9a"/></g><g filter="url(#iH0juBd)"><path fill="url(#iYKv14d)" class="r7uo3d6bt"/><path fill="url(#iFShXFc)" class="r7uo3d6bt"/><path fill="url(#igi1r5b)" class="r7uo3d6bt"/><path fill="url(#iubmhRb)" class="r7uo3d6bt"/></g><g filter="url(#ioIGWKe)"><path fill="url(#iLJbQtb)" class="sldolhwet"/><path fill="url(#ivVLhSc)" class="sldolhwet"/></g><g filter="url(#icWZDjb)"><path fill="url(#i005Nwb)" class="kr53agcoz"/><path fill="url(#izI6nxe)" class="kr53agcoz"/></g><path fill="url(#iPOZVUd)" class="kr53agcoz"/><path fill="url(#iaSNFcc)" class="kr53agcoz"/><path fill="url(#iWlXaUc)" class="kr53agcoz"/><g filter="url(#iltsTxb)"><path fill="url(#itTl0ZM)" class="dnmrr8bwi"/></g><defs><radialGradient id="iXgkyYc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28127 3.34374 -2.19036 .83931 16.187 16.389)" gradientUnits="userSpaceOnUse"><stop class="df7vpfiis"/><stop offset="1" class="wn9v_w92o"/></radialGradient><radialGradient id="iOBLwDc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1875 -2.46874 1.58642 -2.0483 19.594 17.764)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="agm1x0bgr"/><stop offset="1" class="tml2omi_y"/></radialGradient><radialGradient id="iYKv14d" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 7.375 -2.08313 .30894 19.625 13.827)" gradientUnits="userSpaceOnUse"><stop class="aqrvmac3i"/><stop offset="1" class="ipaxjmbts"/></radialGradient><radialGradient id="iFShXFc" cx="0" cy="0" r="1" gradientTransform="rotate(87.785 2.378 17.399)scale(1.41512 1.2626)" gradientUnits="userSpaceOnUse"><stop class="sgw5tp4to"/><stop offset="1" class="ac2on18go"/></radialGradient><radialGradient id="iubmhRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32591 -4.64081 1.47334 -.42094 21.975 17.03)" gradientUnits="userSpaceOnUse"><stop class="i5wfvcbqc"/><stop offset="1" class="c1p3-_bke"/></radialGradient><radialGradient id="iLJbQtb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71742 7.7931 -1.1034 -.24316 24.34 12.259)" gradientUnits="userSpaceOnUse"><stop class="jvyjspbmg"/><stop offset="1" class="nphtzgbdo"/></radialGradient><radialGradient id="ivVLhSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.12215 .94667 -.98963 -.1277 23.973 13.71)" gradientUnits="userSpaceOnUse"><stop class="usjw7xgvm"/><stop offset="1" class="y-1whhbdf"/></radialGradient><radialGradient id="i005Nwb" cx="0" cy="0" r="1" gradientTransform="matrix(-18.51782 11.00907 -16.0961 -27.07447 22.393 13.38)" gradientUnits="userSpaceOnUse"><stop class="b7w-zrbjb"/><stop offset="1" class="c98jobcfk"/></radialGradient><radialGradient id="izI6nxe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43758 9.62494 -8.83433 -7.7445 15.25 15)" gradientUnits="userSpaceOnUse"><stop offset=".338" class="lunti6bkv"/><stop offset="1" class="j16_pxuig"/></radialGradient><radialGradient id="iPOZVUd" cx="0" cy="0" r="1" gradientTransform="matrix(4.375 -2.1875 4.2 8.4 2.625 21.5)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="r383hkblm"/><stop offset="1" class="qim86cbtc"/></radialGradient><radialGradient id="iaSNFcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.794 2.97758 -3.76522 -1.00403 13.542 14.768)" gradientUnits="userSpaceOnUse"><stop class="m39qw9y0a"/><stop offset="1" class="x2qg28bmm"/></radialGradient><radialGradient id="itTl0ZM" cx="0" cy="0" r="1" gradientTransform="rotate(-17.266 64.022 -1.498)scale(12.541 9.77596)" gradientUnits="userSpaceOnUse"><stop class="elmf08bps"/><stop offset=".79" class="lfg6v7b4l"/></radialGradient><filter id="ixTnbdb" width="5.726" height="7.719" x="14.151" y="14.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.32549 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6676"/></filter><filter id="iH0juBd" width="4.609" height="7.162" x="17.57" y="13.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6676"/></filter><filter id="ioIGWKe" width="5.64" height="7.217" x="20.125" y="12.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.219608 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6676"/></filter><filter id="icWZDjb" width="29.181" height="19.707" x="2.047" y="6.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.258824 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6676"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.392157 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6676" result="effect2_innerShadow_20020_6676"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.364706 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_6676" result="effect3_innerShadow_20020_6676"/></filter><filter id="iltsTxb" width="25.417" height="16.219" x="4.099" y="7.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6676" stdDeviation=".75"/></filter><linearGradient id="igi1r5b" x1="17.57" x2="18.859" y1="17.858" y2="17.76" gradientUnits="userSpaceOnUse"><stop class="yinxe5ijd"/><stop offset="1" class="bpl0utb6y"/></linearGradient><linearGradient id="iWlXaUc" x1="14.479" x2="14.479" y1="25.475" y2="24.402" gradientUnits="userSpaceOnUse"><stop class="whd-56bdr"/><stop offset="1" class="e43k3kbgd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-up-hand-medium-dark" /></template>
<style>
.ac2on18go {
  stop-color: var(--svg-color--8a6e63, #8A6E63);
  stop-opacity: 0;
}

.agm1x0bgr {
  stop-color: var(--svg-color--4f2d21, #4F2D21);
}

.aqrvmac3i {
  stop-color: var(--svg-color--806258, #806258);
}

.b7w-zrbjb {
  stop-color: var(--svg-color--946b5b, #946B5B);
}

.bpl0utb6y {
  stop-color: var(--svg-color--56352b, #56352B);
  stop-opacity: 0;
}

.c1p3-_bke {
  stop-color: var(--svg-color--56372c, #56372C);
  stop-opacity: 0;
}

.c98jobcfk {
  stop-color: var(--svg-color--81594f, #81594F);
}

.df7vpfiis {
  stop-color: var(--svg-color--73564a, #73564A);
}

.dnmrr8bwi {
  d: path("m22.51 21.27l5.253-4.436a.71.71 0 1 0-.925-1.078l-4.914 4.291a2 2 0 0 1-1.374.493l-6.3-.185a4 4 0 0 1-3.632-2.605l-.317-.854a4 4 0 0 1 .345-3.492l.33-.535a3 3 0 0 1 2.553-1.426h1.741a3 3 0 0 0 1.872-.655l1.048-.837a.537.537 0 0 0-.638-.863l-1.012.691a3 3 0 0 1-1.692.523H12.64a4 4 0 0 0-2.684 1.033l-3.04 2.751a4 4 0 0 0-.723 5.065l.233.378a5 5 0 0 0 4.092 2.375l9.279.307a4 4 0 0 0 2.712-.942");
}

.e43k3kbgd {
  stop-color: var(--svg-color--804862, #804862);
  stop-opacity: 0;
}

.elmf08bps {
  stop-color: var(--svg-color--a07970, #A07970);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.i5wfvcbqc {
  stop-color: var(--svg-color--56372c, #56372C);
}

.ipaxjmbts {
  stop-color: var(--svg-color--6d493c, #6D493C);
}

.j16_pxuig {
  stop-color: var(--svg-color--946267, #946267);
}

.jvyjspbmg {
  stop-color: var(--svg-color--947065, #947065);
}

.kr53agcoz {
  d: path("M12.625 16.203c0 1.702 1.672 2.881 3.484 2.881h3.657c.8 0 1.174-.137 1.656-.62l4.03-3.455c1.062-.986 2.602-1.354 3.772-.25c1.243 1.173.813 2.76-.311 3.771l-5.867 5.102c-1.406 1.314-2.26 1.814-4.01 1.814l-8.715.028c-4.825.03-8.274-2.46-8.274-6.85c0-2.125 1.594-4.368 3-5.782l2.062-2c1.493-1.398 2.664-2.039 4.094-2.414s3.305-.14 3.305-.14c.59 0 1.055-.078 1.562-.383c.906-.546 2.197-.545 2.946.203c.64.555 1 1.5.718 2.476c-.247.616-.51.904-1.039 1.329c-1.077.866-2.66 1.216-3.966 1.32c-1.448.25-2.104 1.285-2.104 2.97");
}

.lfg6v7b4l {
  stop-color: var(--svg-color--a07970, #A07970);
}

.lunti6bkv {
  stop-color: var(--svg-color--946267, #946267);
  stop-opacity: 0;
}

.m39qw9y0a {
  stop-color: var(--svg-color--814f59, #814F59);
}

.nphtzgbdo {
  stop-color: var(--svg-color--795447, #795447);
}

.qim86cbtc {
  stop-color: var(--svg-color--7d5351, #7D5351);
  stop-opacity: 0;
}

.r383hkblm {
  stop-color: var(--svg-color--7d5351, #7D5351);
}

.r7uo3d6bt {
  d: path("M19.43 13.18a2.07 2.07 0 0 0-1.85 2.262l.491 4.89l4.109-.412l-.488-4.893a2.064 2.064 0 0 0-2.262-1.847");
}

.sgw5tp4to {
  stop-color: var(--svg-color--8a6e63, #8A6E63);
}

.sldolhwet {
  d: path("M24.09 12.294a2.05 2.05 0 0 0-2.388 1.64l-.62 4.098a2 2 0 0 1-.738 1.271l-.219.172h4.717l.89-4.792a2.05 2.05 0 0 0-1.641-2.39");
}

.tml2omi_y {
  stop-color: var(--svg-color--4f2d21, #4F2D21);
  stop-opacity: 0;
}

.tou0_8b9a {
  d: path("M15.5 15.116c-1.097.393-1.61 1.624-1.219 2.765l1.969 4.836l3.627-1.316l-1.683-4.922c-.389-1.146-1.596-1.753-2.693-1.363");
}

.usjw7xgvm {
  stop-color: var(--svg-color--99776a, #99776A);
}

.whd-56bdr {
  stop-color: var(--svg-color--7e4278, #7E4278);
}

.wn9v_w92o {
  stop-color: var(--svg-color--6b4a3d, #6B4A3D);
}

.x2qg28bmm {
  stop-color: var(--svg-color--814f59, #814F59);
  stop-opacity: 0;
}

.y-1whhbdf {
  stop-color: var(--svg-color--99776a, #99776A);
  stop-opacity: 0;
}

.yinxe5ijd {
  stop-color: var(--svg-color--56352b, #56352B);
}

</style>
