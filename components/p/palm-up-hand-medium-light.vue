<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSolsdc)"><path fill="url(#ieQiPVb)" class="roljhwbbd"/><path fill="url(#iCmcdQJ)" class="roljhwbbd"/></g><g filter="url(#i6GipGp)"><path fill="url(#i3bSzUH)" class="x_69e-bqm"/><path fill="url(#is3qqUA)" class="x_69e-bqm"/><path fill="url(#itOVPLc)" class="x_69e-bqm"/><path fill="url(#i0pf24d)" class="x_69e-bqm"/></g><g filter="url(#iCajLqp)"><path fill="url(#idmbsLc)" class="uo8li37ja"/><path fill="url(#i6e0zDj)" class="uo8li37ja"/></g><g filter="url(#iLEgcid)"><path fill="url(#iGWp4uv)" class="cscrl4biv"/><path fill="url(#iOaJ1Le)" class="cscrl4biv"/></g><path fill="url(#ivZowse)" class="cscrl4biv"/><path fill="url(#iAdoulP)" class="cscrl4biv"/><path fill="url(#ic6qssk)" class="cscrl4biv"/><path fill="url(#iHMgvvc)" class="cscrl4biv"/><g filter="url(#i9zJEMc)"><path fill="url(#i2iDZmj)" class="cvcxohbwr"/></g><defs><radialGradient id="ieQiPVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.28127 3.34374 -2.19036 .83931 16.123 16.297)" gradientUnits="userSpaceOnUse"><stop class="oly_gj2se"/><stop offset="1" class="ns7iltdhf"/></radialGradient><radialGradient id="iCmcdQJ" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1875 -2.46874 1.58642 -2.0483 19.53 17.672)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="ucx13bciu"/><stop offset="1" class="thhk33e1m"/></radialGradient><radialGradient id="i3bSzUH" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 7.375 -2.08313 .30894 19.561 13.735)" gradientUnits="userSpaceOnUse"><stop class="wqvrrnbbr"/><stop offset="1" class="fyhn7dm9e"/></radialGradient><radialGradient id="is3qqUA" cx="0" cy="0" r="1" gradientTransform="matrix(.08771 .87001 -.91542 .0923 19.608 14.259)" gradientUnits="userSpaceOnUse"><stop class="zd9l0ob6k"/><stop offset="1" class="deuby4yyb"/></radialGradient><radialGradient id="i0pf24d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32591 -4.64081 1.47334 -.42094 21.912 16.94)" gradientUnits="userSpaceOnUse"><stop class="y6-_6yb-i"/><stop offset="1" class="zw7b9epki"/></radialGradient><radialGradient id="idmbsLc" cx="0" cy="0" r="1" gradientTransform="rotate(105.081 8.122 14.903)scale(6.69949 .94855)" gradientUnits="userSpaceOnUse"><stop class="qosvp2mik"/><stop offset="1" class="s73s8zbcz"/></radialGradient><radialGradient id="i6e0zDj" cx="0" cy="0" r="1" gradientTransform="rotate(108.54 7.811 14.85)scale(1.86736 1.95209)" gradientUnits="userSpaceOnUse"><stop class="w8wpswfby"/><stop offset="1" class="el5-3ftcb"/></radialGradient><radialGradient id="iGWp4uv" cx="0" cy="0" r="1" gradientTransform="matrix(-18.51782 11.00907 -16.0961 -27.07447 22.33 13.288)" gradientUnits="userSpaceOnUse"><stop class="qz359cc6l"/><stop offset="1" class="h2pc7_5up"/></radialGradient><radialGradient id="iOaJ1Le" cx="0" cy="0" r="1" gradientTransform="matrix(-11.23244 14.54514 -13.35042 -10.30982 16.995 10.838)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="oej45l0lo"/><stop offset="1" class="jmzgnm3db"/></radialGradient><radialGradient id="ivZowse" cx="0" cy="0" r="1" gradientTransform="rotate(-26.978 46.31 6.737)scale(5.55795 8.81918)" gradientUnits="userSpaceOnUse"><stop class="n_wk7ebjp"/><stop offset="1" class="h55_s7b2z"/></radialGradient><radialGradient id="ic6qssk" cx="0" cy="0" r="1" gradientTransform="rotate(132.138 3.85 10.456)scale(5.30993 5.06495)" gradientUnits="userSpaceOnUse"><stop class="mkhyqvb0e"/><stop offset="1" class="ez4vjpb8w"/></radialGradient><radialGradient id="iHMgvvc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21251 -.79386 .29472 -2.30642 17.173 13.249)" gradientUnits="userSpaceOnUse"><stop class="g0heng09l"/><stop offset="1" class="ae-v61d_p"/></radialGradient><radialGradient id="i2iDZmj" cx="0" cy="0" r="1" gradientTransform="rotate(-17.266 63.687 -1.335)scale(12.541 9.77596)" gradientUnits="userSpaceOnUse"><stop class="wh0vrhbzi"/><stop offset="0" class="tuszae70f"/><stop offset=".79" class="s098dxbaz"/></radialGradient><filter id="iSolsdc" width="5.726" height="7.719" x="14.088" y="14.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.54902 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6690"/></filter><filter id="i6GipGp" width="4.609" height="7.162" x="17.507" y="13.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.552941 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6690"/></filter><filter id="iCajLqp" width="5.64" height="7.217" x="20.062" y="12.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.552941 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6690"/></filter><filter id="iLEgcid" width="29.181" height="19.707" x="1.983" y="6.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.533333 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6690"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.65098 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6690" result="effect2_innerShadow_20020_6690"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.615686 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_6690" result="effect3_innerShadow_20020_6690"/></filter><filter id="i9zJEMc" width="25.417" height="16.219" x="4.035" y="7.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6690" stdDeviation=".75"/></filter><linearGradient id="itOVPLc" x1="17.311" x2="18.749" y1="17.836" y2="17.711" gradientUnits="userSpaceOnUse"><stop class="twhzyhb9m"/><stop offset="1" class="jicepgben"/></linearGradient><linearGradient id="iAdoulP" x1="14.416" x2="14.416" y1="25.383" y2="23.706" gradientUnits="userSpaceOnUse"><stop class="tjd3vpbzb"/><stop offset="1" class="g8u5fhbzd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-up-hand-medium-light" /></template>
<style>
.ae-v61d_p {
  stop-color: var(--svg-color--db9b8f, #DB9B8F);
  stop-opacity: 0;
}

.cscrl4biv {
  d: path("M12.562 16.111c0 1.702 1.671 2.882 3.484 2.882h3.656c.8 0 1.175-.138 1.656-.621l4.03-3.455c1.063-.986 2.603-1.354 3.773-.25c1.243 1.173.812 2.76-.312 3.772l-5.866 5.1c-1.407 1.315-2.26 1.815-4.01 1.815l-8.715.029c-4.826.029-8.275-2.46-8.275-6.851c0-2.125 1.594-4.367 3-5.782l2.063-2C8.538 9.352 9.71 8.711 11.14 8.336s3.304-.14 3.304-.14c.591 0 1.056-.078 1.563-.383c.905-.546 2.197-.545 2.945.203c.64.555 1 1.5.719 2.477c-.247.615-.51.903-1.04 1.328c-1.077.866-2.66 1.216-3.966 1.32c-1.447.25-2.103 1.285-2.103 2.97");
}

.cvcxohbwr {
  d: path("m22.446 21.177l5.254-4.435a.71.71 0 1 0-.925-1.078l-4.914 4.291a2 2 0 0 1-1.374.493l-6.3-.185a4 4 0 0 1-3.632-2.605l-.318-.854a4 4 0 0 1 .345-3.492l.33-.535a3 3 0 0 1 2.554-1.426h1.74a3 3 0 0 0 1.872-.655l1.049-.837a.537.537 0 0 0-.638-.863l-1.012.691a3 3 0 0 1-1.692.523h-2.209a4 4 0 0 0-2.683 1.033l-3.041 2.751a4 4 0 0 0-.722 5.065l.233.378a5 5 0 0 0 4.091 2.375l9.28.307a4 4 0 0 0 2.712-.942");
}

.deuby4yyb {
  stop-color: var(--svg-color--deaf8d, #DEAF8D);
  stop-opacity: 0;
}

.el5-3ftcb {
  stop-color: var(--svg-color--f3c39e, #F3C39E);
  stop-opacity: 0;
}

.ez4vjpb8w {
  stop-color: var(--svg-color--cf9082, #CF9082);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyhn7dm9e {
  stop-color: var(--svg-color--d09873, #D09873);
}

.g0heng09l {
  stop-color: var(--svg-color--be7a70, #BE7A70);
}

.g8u5fhbzd {
  stop-color: var(--svg-color--c37f8d, #C37F8D);
  stop-opacity: 0;
}

.h2pc7_5up {
  stop-color: var(--svg-color--e4af88, #E4AF88);
}

.h55_s7b2z {
  stop-color: var(--svg-color--d89f87, #D89F87);
  stop-opacity: 0;
}

.jicepgben {
  stop-color: var(--svg-color--c98f6a, #C98F6A);
  stop-opacity: 0;
}

.jmzgnm3db {
  stop-color: var(--svg-color--e3a49a, #E3A49A);
}

.mkhyqvb0e {
  stop-color: var(--svg-color--cf9082, #CF9082);
}

.n_wk7ebjp {
  stop-color: var(--svg-color--d89f87, #D89F87);
}

.ns7iltdhf {
  stop-color: var(--svg-color--c3875e, #C3875E);
}

.oej45l0lo {
  stop-color: var(--svg-color--e3a49a, #E3A49A);
  stop-opacity: 0;
}

.oly_gj2se {
  stop-color: var(--svg-color--c99676, #C99676);
}

.qosvp2mik {
  stop-color: var(--svg-color--f2bf9b, #F2BF9B);
}

.qz359cc6l {
  stop-color: var(--svg-color--f5c299, #F5C299);
}

.roljhwbbd {
  d: path("M15.437 15.024c-1.097.393-1.61 1.624-1.22 2.766l1.97 4.836l3.626-1.316l-1.682-4.923c-.39-1.145-1.596-1.753-2.694-1.363");
}

.s098dxbaz {
  stop-color: var(--svg-color--ffcca9, #FFCCA9);
}

.s73s8zbcz {
  stop-color: var(--svg-color--d8a07c, #D8A07C);
}

.thhk33e1m {
  stop-color: var(--svg-color--aa7049, #AA7049);
  stop-opacity: 0;
}

.tjd3vpbzb {
  stop-color: var(--svg-color--ae6a93, #AE6A93);
}

.tuszae70f {
  stop-color: var(--svg-color--ffcca9, #FFCCA9);
  stop-opacity: 0;
}

.twhzyhb9m {
  stop-color: var(--svg-color--c98f6a, #C98F6A);
}

.ucx13bciu {
  stop-color: var(--svg-color--aa7049, #AA7049);
}

.uo8li37ja {
  d: path("M24.027 12.202a2.05 2.05 0 0 0-2.389 1.64l-.62 4.098a2 2 0 0 1-.738 1.271l-.218.173h4.716l.89-4.793a2.05 2.05 0 0 0-1.64-2.389");
}

.w8wpswfby {
  stop-color: var(--svg-color--f3c39e, #F3C39E);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wqvrrnbbr {
  stop-color: var(--svg-color--ddaa89, #DDAA89);
}

.x_69e-bqm {
  d: path("M19.367 13.088a2.07 2.07 0 0 0-1.85 2.262l.49 4.89l4.11-.412l-.488-4.893a2.064 2.064 0 0 0-2.262-1.847");
}

.y6-_6yb-i {
  stop-color: var(--svg-color--ab704b, #AB704B);
}

.zd9l0ob6k {
  stop-color: var(--svg-color--deaf8d, #DEAF8D);
}

.zw7b9epki {
  stop-color: var(--svg-color--ab704b, #AB704B);
  stop-opacity: 0;
}

</style>
