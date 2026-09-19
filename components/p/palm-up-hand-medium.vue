<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#idqfcpe)"><path fill="url(#iJY95bd)" class="px2__kdru"/><path fill="url(#iM7Y6rb)" class="px2__kdru"/></g><g filter="url(#ipRr8Je)"><path fill="url(#iZAzlle)" class="wp-j-j_cp"/><path fill="url(#iwwoKxd)" class="wp-j-j_cp"/><path fill="url(#i7H0byb)" class="wp-j-j_cp"/><path fill="url(#iU0dg2c)" class="wp-j-j_cp"/></g><g filter="url(#iewDdMe)"><path fill="url(#ixK3mvb)" class="tf0j0sbus"/><path fill="url(#ium9VHB)" class="tf0j0sbus"/></g><g filter="url(#iGU2sGe)"><path fill="url(#itSdKie)" class="sndz-fggw"/><path fill="url(#iIntgid)" class="sndz-fggw"/></g><path fill="url(#iZXd2Gc)" class="sndz-fggw"/><path fill="url(#ifUcHcb)" class="sndz-fggw"/><path fill="url(#iyQ4Joc)" class="sndz-fggw"/><path fill="url(#iF4tohd)" class="sndz-fggw"/><g filter="url(#iPCG1pd)"><path fill="url(#iTZKmze)" class="ki3wki6xv"/></g><defs><radialGradient id="iJY95bd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28127 3.34374 -2.19036 .83931 16.189 15.68)" gradientUnits="userSpaceOnUse"><stop class="bnmuy5bpy"/><stop offset="1" class="secms-wsu"/></radialGradient><radialGradient id="iM7Y6rb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1875 -2.46874 1.58642 -2.0483 19.594 17.055)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="gzgsgfbdw"/><stop offset="1" class="nsd-sibzr"/></radialGradient><radialGradient id="iZAzlle" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 7.375 -2.08313 .30894 19.625 13.118)" gradientUnits="userSpaceOnUse"><stop class="f20drf08u"/><stop offset="1" class="f_7s_8aug"/></radialGradient><radialGradient id="iwwoKxd" cx="0" cy="0" r="1" gradientTransform="matrix(.08771 .87001 -.91542 .0923 19.672 13.642)" gradientUnits="userSpaceOnUse"><stop class="f20drf08u"/><stop offset="1" class="qn4l9jbwi"/></radialGradient><radialGradient id="iU0dg2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32591 -4.64081 1.47334 -.42094 21.975 16.322)" gradientUnits="userSpaceOnUse"><stop class="t44216b3i"/><stop offset="1" class="zr5ctvb1v"/></radialGradient><radialGradient id="ixK3mvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71742 7.7931 -1.1034 -.24316 24.34 11.55)" gradientUnits="userSpaceOnUse"><stop class="yc6wjgb_s"/><stop offset="1" class="qsj9bgb6g"/></radialGradient><radialGradient id="ium9VHB" cx="0" cy="0" r="1" gradientTransform="rotate(100.443 6.617 16.488)scale(.99637 1.04158)" gradientUnits="userSpaceOnUse"><stop class="xnj_sbcnr"/><stop offset="1" class="e1009nb_g"/></radialGradient><radialGradient id="itSdKie" cx="0" cy="0" r="1" gradientTransform="matrix(-18.51782 11.00907 -16.0961 -27.07447 22.393 12.671)" gradientUnits="userSpaceOnUse"><stop class="g8y54dbuj"/><stop offset="1" class="oqco35mal"/></radialGradient><radialGradient id="iIntgid" cx="0" cy="0" r="1" gradientTransform="matrix(-11.23244 14.54514 -13.35042 -10.30982 17.058 10.22)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="orw6sfg1p"/><stop offset="1" class="atyc7gb-y"/></radialGradient><radialGradient id="iZXd2Gc" cx="0" cy="0" r="1" gradientTransform="rotate(-26.978 45.056 6.296)scale(5.55795 8.81918)" gradientUnits="userSpaceOnUse"><stop class="n304-r4kd"/><stop offset="1" class="s2tgxfp2p"/></radialGradient><radialGradient id="iyQ4Joc" cx="0" cy="0" r="1" gradientTransform="rotate(132.138 4.018 10.162)scale(5.30993 5.06495)" gradientUnits="userSpaceOnUse"><stop class="y_jvmku-h"/><stop offset="1" class="s7eucq45i"/></radialGradient><radialGradient id="iF4tohd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21251 -.79386 .29472 -2.30642 17.236 12.632)" gradientUnits="userSpaceOnUse"><stop class="cni4z17gm"/><stop offset="1" class="rq8cglbaf"/></radialGradient><radialGradient id="iTZKmze" cx="0" cy="0" r="1" gradientTransform="rotate(-17.266 61.687 -1.852)scale(12.541 9.77596)" gradientUnits="userSpaceOnUse"><stop class="wh0vrhbzi"/><stop offset=".79" class="hjp773b9j"/></radialGradient><filter id="idqfcpe" width="5.726" height="7.719" x="14.151" y="14.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.341176 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6683"/></filter><filter id="ipRr8Je" width="4.609" height="7.162" x="17.57" y="12.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.384314 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6683"/></filter><filter id="iewDdMe" width="5.64" height="7.217" x="20.125" y="11.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6683"/></filter><filter id="iGU2sGe" width="29.181" height="19.707" x="2.047" y="5.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.45098 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.454902 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6683" result="effect2_innerShadow_20020_6683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.462745 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_6683" result="effect3_innerShadow_20020_6683"/></filter><filter id="iPCG1pd" width="25.417" height="16.219" x="4.099" y="6.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6683" stdDeviation=".75"/></filter><linearGradient id="i7H0byb" x1="17.375" x2="18.813" y1="17.219" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="qytvn-bic"/><stop offset="1" class="cw72qachh"/></linearGradient><linearGradient id="ifUcHcb" x1="14.479" x2="14.479" y1="24.766" y2="23.089" gradientUnits="userSpaceOnUse"><stop class="p61ey2b8q"/><stop offset="1" class="ozqnkmbkl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-up-hand-medium" /></template>
<style>
.atyc7gb-y {
  stop-color: var(--svg-color--bb8685, #BB8685);
}

.bnmuy5bpy {
  stop-color: var(--svg-color--9f7e68, #9F7E68);
}

.cni4z17gm {
  stop-color: var(--svg-color--8c575e, #8C575E);
}

.cw72qachh {
  stop-color: var(--svg-color--7b5740, #7B5740);
  stop-opacity: 0;
}

.e1009nb_g {
  stop-color: var(--svg-color--c49d84, #C49D84);
  stop-opacity: 0;
}

.f_7s_8aug {
  stop-color: var(--svg-color--8e6852, #8E6852);
}

.f20drf08u {
  stop-color: var(--svg-color--b6917a, #B6917A);
}

.ft5dv1b6b {
  fill: none;
}

.g8y54dbuj {
  stop-color: var(--svg-color--c29a7c, #C29A7C);
}

.gzgsgfbdw {
  stop-color: var(--svg-color--62422f, #62422F);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.ki3wki6xv {
  d: path("m22.51 20.56l5.253-4.435a.71.71 0 1 0-.925-1.078l-4.914 4.291a2 2 0 0 1-1.374.493l-6.3-.185a4 4 0 0 1-3.632-2.605l-.317-.854a4 4 0 0 1 .345-3.492l.33-.535a3 3 0 0 1 2.553-1.426h1.741a3 3 0 0 0 1.872-.655l1.048-.837a.537.537 0 0 0-.638-.863l-1.012.691a3 3 0 0 1-1.692.523H12.64a4 4 0 0 0-2.684 1.033l-3.04 2.751a4 4 0 0 0-.723 5.065l.233.378a5 5 0 0 0 4.092 2.375l9.279.307a4 4 0 0 0 2.712-.942");
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.nsd-sibzr {
  stop-color: var(--svg-color--62422f, #62422F);
  stop-opacity: 0;
}

.oqco35mal {
  stop-color: var(--svg-color--a57b6d, #A57B6D);
}

.orw6sfg1p {
  stop-color: var(--svg-color--bb8685, #BB8685);
  stop-opacity: 0;
}

.ozqnkmbkl {
  stop-color: var(--svg-color--a3677d, #A3677D);
  stop-opacity: 0;
}

.p61ey2b8q {
  stop-color: var(--svg-color--97578e, #97578E);
}

.px2__kdru {
  d: path("M15.5 14.407c-1.097.393-1.61 1.624-1.219 2.765l1.969 4.836l3.627-1.315l-1.683-4.923c-.389-1.145-1.596-1.753-2.693-1.363");
}

.qn4l9jbwi {
  stop-color: var(--svg-color--b6917a, #B6917A);
  stop-opacity: 0;
}

.qsj9bgb6g {
  stop-color: var(--svg-color--a17a62, #A17A62);
}

.qytvn-bic {
  stop-color: var(--svg-color--7b5740, #7B5740);
}

.rq8cglbaf {
  stop-color: var(--svg-color--ae797c, #AE797C);
  stop-opacity: 0;
}

.s2tgxfp2p {
  stop-color: var(--svg-color--9e746b, #9E746B);
  stop-opacity: 0;
}

.s7eucq45i {
  stop-color: var(--svg-color--ae797a, #AE797A);
  stop-opacity: 0;
}

.secms-wsu {
  stop-color: var(--svg-color--88644b, #88644B);
}

.sndz-fggw {
  d: path("M12.625 15.494c0 1.702 1.672 2.882 3.484 2.882h3.657c.8 0 1.174-.138 1.656-.622l4.03-3.454c1.062-.986 2.602-1.354 3.772-.25c1.243 1.173.813 2.76-.311 3.772l-5.867 5.1c-1.406 1.315-2.26 1.815-4.01 1.815l-8.715.029c-4.825.029-8.274-2.46-8.274-6.851c0-2.125 1.594-4.368 3-5.782l2.062-2c1.493-1.398 2.664-2.039 4.094-2.414s3.305-.14 3.305-.14c.59 0 1.055-.078 1.562-.383c.906-.546 2.197-.545 2.946.203c.64.555 1 1.5.718 2.477c-.247.615-.51.903-1.039 1.328c-1.077.866-2.66 1.216-3.966 1.32c-1.448.25-2.104 1.285-2.104 2.97");
}

.t44216b3i {
  stop-color: var(--svg-color--684837, #684837);
}

.tf0j0sbus {
  d: path("M24.09 11.585a2.05 2.05 0 0 0-2.388 1.64l-.62 4.098a2 2 0 0 1-.738 1.271l-.219.173h4.717l.89-4.793a2.05 2.05 0 0 0-1.641-2.389");
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wp-j-j_cp {
  d: path("M19.43 12.471a2.07 2.07 0 0 0-1.85 2.262l.491 4.89l4.109-.412l-.488-4.893a2.064 2.064 0 0 0-2.262-1.847");
}

.xnj_sbcnr {
  stop-color: var(--svg-color--c49d84, #C49D84);
}

.y_jvmku-h {
  stop-color: var(--svg-color--ae797a, #AE797A);
}

.yc6wjgb_s {
  stop-color: var(--svg-color--bb927c, #BB927C);
}

.zr5ctvb1v {
  stop-color: var(--svg-color--81604c, #81604C);
  stop-opacity: 0;
}

</style>
