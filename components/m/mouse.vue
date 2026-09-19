<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDk549b)" class="iy4ebs8oa"/><path fill="url(#if5PWVd)" class="iy4ebs8oa"/><path fill="url(#iy1fjTb)" class="iy4ebs8oa"/><path fill="url(#i4eCU4d)" class="iy4ebs8oa"/><path fill="url(#iLS2Fve)" class="iy4ebs8oa"/><path fill="url(#iBi4G1b)" class="iy4ebs8oa"/><g filter="url(#iE0eJYb)"><ellipse fill="url(#io47WJb)" transform="rotate(-33.14 24.136 13.364)" class="vkpldi54k"/></g><g filter="url(#iUdQzAe)"><path fill="url(#iHVWerd)" class="jrcvkfibo"/><path fill="url(#iKT4lBd)" class="jrcvkfibo"/></g><g filter="url(#imCb1mx)"><path stroke="url(#iN5QC3d)" class="laf_ylbwq"/></g><path fill="url(#i6ohDxe)" class="crpu0z5zb"/><path fill="url(#ifRHJab)" class="crpu0z5zb"/><path fill="url(#iA6rc1d)" class="crpu0z5zb"/><g filter="url(#irWlNlc)"><path class="pic7s2bfn"/><path fill="url(#iA1F4be)" class="uhmvjhbar"/></g><path fill="url(#ihplz5c)" class="memsmgb6n"/><path fill="url(#iCCOEST)" class="memsmgb6n"/><path fill="url(#iplK1oc)" class="tgpq3kpuj"/><path fill="url(#iyu91vi)" class="tgpq3kpuj"/><path fill="url(#iPG1RFd)" class="tgpq3kpuj"/><path fill="url(#ifhZMUd)" class="tgpq3kpuj"/><path fill="url(#iXe0dUb)" class="tgpq3kpuj"/><path fill="url(#i0iRVBb)" class="alypnq26e"/><path fill="url(#iyrWq2b)" class="alypnq26e"/><path fill="url(#iQ0Nyme)" class="alypnq26e"/><path fill="url(#inXGZXc)" class="alypnq26e"/><path fill="url(#ij300Hc)" class="alypnq26e"/><path fill="url(#iDljnvb)" class="w04ibmnvo"/><path fill="url(#i9ZNV1b)" class="w04ibmnvo"/><path fill="url(#iCWXbwb)" class="w04ibmnvo"/><path class="boqxnmbgc"/><path fill="url(#itp2CCG)" class="b4cq3zidg"/><path fill="url(#ivHEJnd)" class="b4cq3zidg"/><path fill="url(#ixLCR0c)" class="b4cq3zidg"/><g filter="url(#iRkdWBd)"><circle fill="url(#iXnduVd)" transform="rotate(7.647 26.928 18.906)" class="g_384yb1t"/></g><path fill="url(#ix6YOld)" class="t6ffrtbga"/><path fill="url(#iV7ICMe)" class="t6ffrtbga"/><g filter="url(#iatM9Yb)"><path stroke="url(#idac7de)" class="i3p53832p"/></g><circle class="jfgx_h2ed"/><circle fill="url(#ic6HfPg)" class="p3dvkib9e"/><circle fill="url(#iTHSDub)" class="p3dvkib9e"/><circle fill="url(#iVUXeid)" class="p3dvkib9e"/><path fill="url(#iwsogTd)" class="f3k7yab7k"/><path fill="url(#iGISoAd)" class="f3k7yab7k"/><g filter="url(#iwd8vod)"><path stroke="url(#ij26cRd)" class="q5nsz2bsi"/></g><g filter="url(#ipzYrKe)"><path stroke="url(#iNN8vwc)" class="ffo83cbwn"/></g><g filter="url(#igtnklc)"><path stroke="url(#i1IF60c)" class="b8xdgebdz"/></g><g filter="url(#i4SfqMe)"><path stroke="url(#ipYRfpc)" class="ybplgobos"/></g><g filter="url(#ihH8Hyo)"><circle class="gzh4cme-e"/></g><defs><radialGradient id="if5PWVd" cx="0" cy="0" r="1" gradientTransform="rotate(-126.469 17.717 3.05)scale(7.15017 6.67845)" gradientUnits="userSpaceOnUse"><stop class="hb6-pyb3x"/><stop offset="1" class="imwagl-re"/></radialGradient><radialGradient id="iy1fjTb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 -.21876 .2243 -4.7424 21.983 18.518)" gradientUnits="userSpaceOnUse"><stop class="hb6-pyb3x"/><stop offset="1" class="imwagl-re"/></radialGradient><radialGradient id="i4eCU4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -3.84375 4.08343 1.89232 15.295 22.8)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="y4cw-z58u"/><stop offset="1" class="oogipjboh"/></radialGradient><radialGradient id="iLS2Fve" cx="0" cy="0" r="1" gradientTransform="rotate(150.068 7.347 13.566)scale(4.75986 5.37614)" gradientUnits="userSpaceOnUse"><stop class="rniijqc1k"/><stop offset="1" class="tr7f7jpbv"/></radialGradient><radialGradient id="iBi4G1b" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 4.25 -4.80027 2.61191 10.67 10.406)" gradientUnits="userSpaceOnUse"><stop class="rniijqc1k"/><stop offset="1" class="tr7f7jpbv"/></radialGradient><radialGradient id="io47WJb" cx="0" cy="0" r="1" gradientTransform="matrix(11.4522 3.22232 -2.6244 9.32714 17.567 10.842)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="gra6njb5l"/><stop offset="1" class="bm6l38bkm"/></radialGradient><radialGradient id="iHVWerd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.90624 -2.03127 2.6545 -3.79793 8.326 7.531)" gradientUnits="userSpaceOnUse"><stop class="qzooa0bqp"/><stop offset="1" class="fq5-3e7tq"/></radialGradient><radialGradient id="iKT4lBd" cx="0" cy="0" r="1" gradientTransform="rotate(116.86 5.256 4.457)scale(4.13343)" gradientUnits="userSpaceOnUse"><stop class="ujiekdg8z"/><stop offset="1" class="r7kipibvh"/></radialGradient><radialGradient id="iA6rc1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.29688 -.70313 .72263 1.33285 15.467 23.063)" gradientUnits="userSpaceOnUse"><stop class="sryaymbnx"/><stop offset=".546" class="ta_4xe4xs"/></radialGradient><radialGradient id="ihplz5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.4093 .5667 -.50524 -.3649 6.49 11.893)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iCCOEST" cx="0" cy="0" r="1" gradientTransform="rotate(126.384 .234 7.618)scale(.37152 .31318)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iPG1RFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8679 -3.84524 3.70693 1.8007 15.546 27.859)" gradientUnits="userSpaceOnUse"><stop class="sryaymbnx"/><stop offset=".546" class="ta_4xe4xs"/></radialGradient><radialGradient id="ifhZMUd" cx="0" cy="0" r="1" gradientTransform="rotate(-180 15.757 11.687)scale(4.375)" gradientUnits="userSpaceOnUse"><stop class="sryaymbnx"/><stop offset="1" class="ta_4xe4xs"/></radialGradient><radialGradient id="iXe0dUb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.15625 0 0 -6.11111 29.764 23.031)" gradientUnits="userSpaceOnUse"><stop class="lb3ea50oq"/><stop offset="1" class="k3f8__b4i"/></radialGradient><radialGradient id="iyrWq2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.84375 12.2175 0 24.576 25.063)" gradientUnits="userSpaceOnUse"><stop class="j9yb5ob9l"/><stop offset="1" class="cywz_abal"/></radialGradient><radialGradient id="inXGZXc" cx="0" cy="0" r="1" gradientTransform="matrix(5.21877 3.62498 -4.33468 6.2405 18.138 17.312)" gradientUnits="userSpaceOnUse"><stop class="qzgv15btg"/><stop offset="1" class="n3ectvb5f"/></radialGradient><radialGradient id="iDljnvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20313 .25782 -.67959 -3.17134 2.623 13.695)" gradientUnits="userSpaceOnUse"><stop class="o7gke2fob"/><stop offset="1" class="cmdn_ebqz"/></radialGradient><radialGradient id="iCWXbwb" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 1.01562 -.55519 .10677 2.201 12.844)" gradientUnits="userSpaceOnUse"><stop class="auwd3ybho"/><stop offset=".877" class="m3thdbckt"/></radialGradient><radialGradient id="iXnduVd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0625 2.75 -1.875 -1.40625 27.49 18.375)" gradientUnits="userSpaceOnUse"><stop class="jn6j15btn"/><stop offset=".809" class="kggki2l5x"/></radialGradient><radialGradient id="ic6HfPg" cx="0" cy="0" r="1" gradientTransform="matrix(4.79224 4.76133 -5.27221 5.30644 12.042 5.347)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="oogipjboh"/><stop offset="1" class="y4cw-z58u"/></radialGradient><radialGradient id="iTHSDub" cx="0" cy="0" r="1" gradientTransform="matrix(-5.37969 4.32847 -10.21312 -12.69349 15.907 4.265)" gradientUnits="userSpaceOnUse"><stop class="mq90jhxmi"/><stop offset="1" class="yc5c4mbum"/></radialGradient><radialGradient id="iVUXeid" cx="0" cy="0" r="1" gradientTransform="matrix(-4.56438 -2.00001 1.97787 -4.51385 13 7.11)" gradientUnits="userSpaceOnUse"><stop offset=".873" class="gbavcwj5v"/><stop offset="1" class="tzzsr-bgm"/></radialGradient><radialGradient id="iwsogTd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90622 4.34378 -5.58397 -5.02148 14.389 5.25)" gradientUnits="userSpaceOnUse"><stop class="crjn0dlmu"/><stop offset="1" class="y61u5n5lx"/></radialGradient><radialGradient id="iGISoAd" cx="0" cy="0" r="1" gradientTransform="rotate(-40.426 16.81 -10.843)scale(3.32515)" gradientUnits="userSpaceOnUse"><stop class="blb-ce2fw"/><stop offset="1" class="h_pdb65ej"/></radialGradient><linearGradient id="iDk549b" x1="18.483" x2="18.483" y1="8.344" y2="23.549" gradientUnits="userSpaceOnUse"><stop class="t6_wltsvl"/><stop offset="1" class="zlupwijhs"/></linearGradient><linearGradient id="iN5QC3d" x1="10.545" x2="7.248" y1="3.692" y2="7.25" gradientUnits="userSpaceOnUse"><stop class="ujiekdg8z"/><stop offset="1" class="r7kipibvh"/></linearGradient><linearGradient id="i6ohDxe" x1="17.233" x2="25.1" y1="22.471" y2="22.471" gradientUnits="userSpaceOnUse"><stop class="dhx5eh5qi"/><stop offset="1" class="f0_0334-m"/></linearGradient><linearGradient id="ifRHJab" x1="20.24" x2="20.24" y1="23.734" y2="22.828" gradientUnits="userSpaceOnUse"><stop class="zfy8ajb0h"/><stop offset="1" class="xn9t58zsj"/></linearGradient><linearGradient id="iA1F4be" x1="8.767" x2="8.767" y1="16.719" y2="13.719" gradientUnits="userSpaceOnUse"><stop class="y4cw-z58u"/><stop offset=".843" class="oogipjboh"/></linearGradient><linearGradient id="iplK1oc" x1="18.088" x2="29.42" y1="24.625" y2="24.625" gradientUnits="userSpaceOnUse"><stop class="dhx5eh5qi"/><stop offset="1" class="f0_0334-m"/></linearGradient><linearGradient id="iyu91vi" x1="22.42" x2="22.42" y1="31.533" y2="29.844" gradientUnits="userSpaceOnUse"><stop class="zfy8ajb0h"/><stop offset="1" class="xn9t58zsj"/></linearGradient><linearGradient id="i0iRVBb" x1="21.045" x2="21.045" y1="23.553" y2="15.281" gradientUnits="userSpaceOnUse"><stop class="w0v7721za"/><stop offset="1" class="nn6vx1ivg"/></linearGradient><linearGradient id="iQ0Nyme" x1="24.576" x2="24.576" y1="23.969" y2="20.281" gradientUnits="userSpaceOnUse"><stop offset=".016" class="j9yb5ob9l"/><stop offset=".376" class="cywz_abal"/></linearGradient><linearGradient id="ij300Hc" x1="22.889" x2="23.014" y1="13.656" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="qzgv15btg"/><stop offset="1" class="n3ectvb5f"/></linearGradient><linearGradient id="i9ZNV1b" x1="2.311" x2="2.084" y1="15.227" y2="14.242" gradientUnits="userSpaceOnUse"><stop class="kyfajn71c"/><stop offset="1" class="gwoid0g3c"/></linearGradient><linearGradient id="itp2CCG" x1="9.733" x2="9.858" y1="24.563" y2="22.688" gradientUnits="userSpaceOnUse"><stop offset=".216" class="y4cw-z58u"/><stop offset="1" class="oogipjboh"/></linearGradient><linearGradient id="ivHEJnd" x1="11.795" x2="10.795" y1="23.031" y2="22.813" gradientUnits="userSpaceOnUse"><stop class="ijz8atb3s"/><stop offset="1" class="wpyh5vbyl"/></linearGradient><linearGradient id="ixLCR0c" x1="12.857" x2="12.412" y1="17.602" y2="18.992" gradientUnits="userSpaceOnUse"><stop class="ex98i55iy"/><stop offset="1" class="xm25k-b7f"/></linearGradient><linearGradient id="ix6YOld" x1="9.654" x2="9.029" y1="17.688" y2="17.344" gradientUnits="userSpaceOnUse"><stop class="l_nupdb1h"/><stop offset="1" class="q63b76bcm"/></linearGradient><linearGradient id="iV7ICMe" x1="8.232" x2="9.264" y1="17.797" y2="16.875" gradientUnits="userSpaceOnUse"><stop class="l_nupdb1h"/><stop offset="1" class="q63b76bcm"/></linearGradient><linearGradient id="idac7de" x1="11.826" x2="9.404" y1="12.797" y2="16.578" gradientUnits="userSpaceOnUse"><stop class="yq_gzpbvu"/><stop offset="1" class="kanx0bbso"/></linearGradient><linearGradient id="ij26cRd" x1="11.295" x2="7.764" y1="10.031" y2="8.702" gradientUnits="userSpaceOnUse"><stop class="veq76oryw"/><stop offset=".333" class="a0z7iyxvk"/><stop offset=".651" class="a0z7iyxvk"/><stop offset="1" class="veq76oryw"/></linearGradient><linearGradient id="iNN8vwc" x1="13.597" x2="17.351" y1="3.164" y2="3.534" gradientUnits="userSpaceOnUse"><stop class="veq76oryw"/><stop offset=".333" class="a0z7iyxvk"/><stop offset=".651" class="a0z7iyxvk"/><stop offset="1" class="veq76oryw"/></linearGradient><linearGradient id="i1IF60c" x1="17.045" x2="21.116" y1="26.469" y2="19.373" gradientUnits="userSpaceOnUse"><stop class="lb3ea50oq"/><stop offset="1" class="k3f8__b4i"/></linearGradient><linearGradient id="ipYRfpc" x1="17.108" x2="21.179" y1="28.229" y2="35.324" gradientUnits="userSpaceOnUse"><stop class="qgyngge4k"/><stop offset="1" class="k3f8__b4i"/></linearGradient><filter id="iE0eJYb" width="12.729" height="14.447" x="17.771" y="6.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".75"/></filter><filter id="iUdQzAe" width="8.79" height="8.74" x="5.42" y="2.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.796078 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3693"/></filter><filter id="imCb1mx" width="6.4" height="5.964" x="5.833" y="2.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".5"/></filter><filter id="irWlNlc" width="15.67" height="13.75" x="1.42" y="2.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.682353 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3693"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.809819 0 0 0 0 0.780799 0 0 0 0 0.829167 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_3693" result="effect2_innerShadow_28327_3693"/></filter><filter id="iRkdWBd" width="5.875" height="5.875" x="23.99" y="15.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".5"/></filter><filter id="iatM9Yb" width="3.608" height="6.061" x="9.893" y="9.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".5"/></filter><filter id="iwd8vod" width="2.42" height="4.794" x="8.788" y="5.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".15"/></filter><filter id="ipzYrKe" width="3.329" height="4.234" x="13.669" y="2.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".15"/></filter><filter id="igtnklc" width="12.813" height="4.781" x="15.686" y="22.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".375"/></filter><filter id="i4SfqMe" width="7.297" height="3.938" x="15.686" y="26.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".375"/></filter><filter id="ihH8Hyo" width="1.781" height="1.781" x="21.771" y="28.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3693" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mouse" /></template>
<style>
.a0z7iyxvk {
  stop-color: var(--svg-color--ded8de, #DED8DE);
}

.alypnq26e {
  d: path("M18.834 19.724a3.83 3.83 0 0 1 3.83-3.83h3.506a3.25 3.25 0 0 1 3.25 3.25v1.16a3.25 3.25 0 0 1-3.25 3.25h-3.506a3.83 3.83 0 0 1-3.83-3.83");
}

.auwd3ybho {
  stop-color: var(--svg-color--e58e94, #E58E94);
}

.b4cq3zidg {
  d: path("m8.952 19.254l.218-.853l-.005-.005L9.76 16l3.05 1.203l-.9 3.243l-.01-.005l-.159.613l-.024.087v.002l-.427 1.648c-.14.54-.45.74-.87.74H8.26c-.2 0-.35-.2-.3-.4l.938-3.667l.002-.003z");
}

.b8xdgebdz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.686 26.75c0-.385.33-1.156 1.656-1.156h6.203c.672.031 2.066-.4 2.953-1.625");
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.blb-ce2fw {
  stop-color: var(--svg-color--d27a7b, #D27A7B);
}

.bm6l38bkm {
  stop-color: var(--svg-color--e3e1e6, #E3E1E6);
}

.boqxnmbgc {
  fill: var(--svg-color--baafc2, #BAAFC2);
  d: path("m8.952 19.254l.218-.853l-.005-.005L9.76 16l3.05 1.203l-.9 3.243l-.01-.005l-.159.613l-.024.087v.002l-.427 1.648c-.14.54-.45.74-.87.74H8.26c-.2 0-.35-.2-.3-.4l.938-3.667l.002-.003z");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cmdn_ebqz {
  stop-color: var(--svg-color--d56b77, #D56B77);
}

.crjn0dlmu {
  stop-color: var(--svg-color--d06b6e, #D06B6E);
}

.crpu0z5zb {
  d: path("M24.02 21.391h-7.56c-.6 0-1.08.48-1.08 1.08s.48 1.08 1.08 1.08h7.56c.6 0 1.08-.48 1.08-1.08s-.48-1.08-1.08-1.08");
}

.cywz_abal {
  stop-color: var(--svg-color--a980b5, #A980B5);
  stop-opacity: 0;
}

.dhx5eh5qi {
  stop-color: var(--svg-color--cd717c, #CD717C);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ex98i55iy {
  stop-color: var(--svg-color--baafc2, #BAAFC2);
}

.f0_0334-m {
  stop-color: var(--svg-color--c14b76, #C14B76);
}

.f3k7yab7k {
  d: path("M12.75 10.111a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.ffo83cbwn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.649 6.584c.009-.81-.504-2.653-2.63-3.533");
}

.fq5-3e7tq {
  stop-color: var(--svg-color--b0adb1, #B0ADB1);
}

.ft5dv1b6b {
  fill: none;
}

.g_384yb1t {
  cx: 26.928px;
  cy: 18.906px;
  r: 1.938px;
}

.gbavcwj5v {
  stop-color: var(--svg-color--cec2d1, #CEC2D1);
  stop-opacity: 0;
}

.gra6njb5l {
  stop-color: var(--svg-color--e3e1e6, #E3E1E6);
  stop-opacity: 0;
}

.gwoid0g3c {
  stop-color: var(--svg-color--d26483, #D26483);
  stop-opacity: 0;
}

.gzh4cme-e {
  cx: 22.662px;
  cy: 29.229px;
  r: 0.391px;
  fill: var(--svg-color--fdb1bb, #FDB1BB);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
}

.h_pdb65ej {
  stop-color: var(--svg-color--d27a7b, #D27A7B);
  stop-opacity: 0;
}

.hb6-pyb3x {
  stop-color: var(--svg-color--b3abb8, #B3ABB8);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i3p53832p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M12.201 10.418v1.723a2 2 0 0 1-.936 1.694l-.072.044");
}

.ijz8atb3s {
  stop-color: var(--svg-color--c9bad7, #C9BAD7);
}

.imwagl-re {
  stop-color: var(--svg-color--b3abb8, #B3ABB8);
  stop-opacity: 0;
}

.iy4ebs8oa {
  d: path("m6.18 9.99l12.56-3.23c5.59-1.21 10.68 3.24 10.68 8.96q0 .096-.004.193h.004v4.915l-5.293.878v-.174a6 6 0 0 1-.567.027h-7.73c-1.4 0-2.73-.52-3.93-1.1l-.61 2.35c-.14.54-.45.74-.87.74H8.26c-.2 0-.35-.2-.3-.4l1.21-4.73a9.07 9.07 0 0 1-2.22-4.41z");
}

.j9yb5ob9l {
  stop-color: var(--svg-color--a980b5, #A980B5);
}

.jfgx_h2ed {
  cx: 12.797px;
  cy: 6.798px;
  r: 4.361px;
  fill: var(--svg-color--baafc6, #BAAFC6);
}

.jn6j15btn {
  stop-color: var(--svg-color--e2dfe6, #E2DFE6);
}

.jrcvkfibo {
  d: path("M9.74 11.171a4.32 4.32 0 1 0 0-8.64a4.32 4.32 0 0 0 0 8.64");
}

.k3f8__b4i {
  stop-color: var(--svg-color--e88e9a, #E88E9A);
  stop-opacity: 0;
}

.kanx0bbso {
  stop-color: var(--svg-color--d3cbd9, #D3CBD9);
  stop-opacity: 0;
}

.kggki2l5x {
  stop-color: var(--svg-color--e2dfe6, #E2DFE6);
  stop-opacity: 0;
}

.kyfajn71c {
  stop-color: var(--svg-color--d26483, #D26483);
}

.l_nupdb1h {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
}

.laf_ylbwq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.108 7.156c-.084-.541-.007-1.843.968-2.718s2.344-.803 2.906-.657");
}

.lb3ea50oq {
  stop-color: var(--svg-color--e88e9a, #E88E9A);
}

.m3thdbckt {
  stop-color: var(--svg-color--e58e94, #E58E94);
  stop-opacity: 0;
}

.memsmgb6n {
  d: path("M6.34 12.559a.504.504 0 1 0 0-1.008a.504.504 0 0 0 0 1.008");
}

.mq90jhxmi {
  stop-color: var(--svg-color--b0a4b3, #B0A4B3);
}

.n3ectvb5f {
  stop-color: var(--svg-color--9e96a4, #9E96A4);
  stop-opacity: 0;
}

.nn6vx1ivg {
  stop-color: var(--svg-color--c4c0c8, #C4C0C8);
}

.o7gke2fob {
  stop-color: var(--svg-color--de7d8b, #DE7D8B);
}

.oogipjboh {
  stop-color: var(--svg-color--a47ec2, #A47EC2);
  stop-opacity: 0;
}

.p3dvkib9e {
  cx: 12.797px;
  cy: 6.798px;
  r: 4.361px;
}

.pic7s2bfn {
  fill: var(--svg-color--baafc6, #BAAFC6);
  d: path("M17.09 6.861c0-2.39-1.94-4.33-4.33-4.33a4.34 4.34 0 0 0-4.34 4.33c0 .17.01.33.03.49l-6.12 4.29c-.57.4-.91 1.05-.91 1.75c0 1.18.96 2.14 2.14 2.14h6.55c1.78 0 3.23-1.45 3.23-3.23v-.922a.26.26 0 0 1 .215-.253a4.35 4.35 0 0 0 3.535-4.265");
}

.q5nsz2bsi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M9.232 5.938c-.218.78-.2 2.693 1.626 4.093");
}

.q63b76bcm {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
  stop-opacity: 0;
}

.qgyngge4k {
  stop-color: var(--svg-color--fdb1bb, #FDB1BB);
}

.qzgv15btg {
  stop-color: var(--svg-color--9e96a4, #9E96A4);
}

.qzooa0bqp {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
}

.r7kipibvh {
  stop-color: var(--svg-color--c0bbbd, #C0BBBD);
  stop-opacity: 0;
}

.rniijqc1k {
  stop-color: var(--svg-color--907c9d, #907C9D);
}

.sryaymbnx {
  stop-color: var(--svg-color--d18496, #D18496);
}

.t6_wltsvl {
  stop-color: var(--svg-color--c7c3c9, #C7C3C9);
}

.t6ffrtbga {
  d: path("M9.166 18.41c-.512-.492-1.426-1.793-1.77-2.879h1.711l.688.469z");
}

.ta_4xe4xs {
  stop-color: var(--svg-color--d18496, #D18496);
  stop-opacity: 0;
}

.tgpq3kpuj {
  d: path("m22.42 30.531l-4.02-.01a2.99 2.99 0 0 1 .01-5.98l5.64.01c1.86 0 3.37-1.51 3.37-3.37V19.72c0-.55.45-1 1-1s1 .45 1 1v1.462c0 2.96-2.41 5.37-5.37 5.37l-5.64-.01c-.55 0-.99.44-.99.99s.44.99.99.99l4.02.01c.55 0 1 .45 1 1c-.01.56-.46 1-1.01 1");
}

.tr7f7jpbv {
  stop-color: var(--svg-color--907c9d, #907C9D);
  stop-opacity: 0;
}

.tzzsr-bgm {
  stop-color: var(--svg-color--cec2d1, #CEC2D1);
}

.uhmvjhbar {
  d: path("M17.09 6.861c0-2.39-1.94-4.33-4.33-4.33a4.34 4.34 0 0 0-4.34 4.33c0 .17.01.33.03.49l-6.12 4.29c-.57.4-.91 1.05-.91 1.75c0 1.18.96 2.14 2.14 2.14h6.55c1.78 0 3.23-1.45 3.23-3.23v-.922a.26.26 0 0 1 .215-.253a4.35 4.35 0 0 0 3.535-4.265");
}

.ujiekdg8z {
  stop-color: var(--svg-color--c0bbbd, #C0BBBD);
}

.veq76oryw {
  stop-color: var(--svg-color--ded8de, #DED8DE);
  stop-opacity: 0;
}

.vkpldi54k {
  cx: 24.136px;
  cy: 13.364px;
  rx: 4.113px;
  ry: 6.284px;
}

.w04ibmnvo {
  d: path("M1.776 14.787a2.1 2.1 0 0 1-.264-2.14a.39.39 0 0 1 .283-.22a.44.44 0 0 1 .523.348l.306 1.576a.51.51 0 0 1-.295.562a.456.456 0 0 1-.553-.126");
}

.w0v7721za {
  stop-color: var(--svg-color--bbb7be, #BBB7BE);
}

.wpyh5vbyl {
  stop-color: var(--svg-color--c9bad7, #C9BAD7);
  stop-opacity: 0;
}

.xm25k-b7f {
  stop-color: var(--svg-color--baafc2, #BAAFC2);
  stop-opacity: 0;
}

.xn9t58zsj {
  stop-color: var(--svg-color--c35385, #C35385);
  stop-opacity: 0;
}

.y4cw-z58u {
  stop-color: var(--svg-color--a47ec2, #A47EC2);
}

.y61u5n5lx {
  stop-color: var(--svg-color--b7454b, #B7454B);
}

.ybplgobos {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.686 27.166c0 1.047.393 1.938 1.718 1.938h3.579");
}

.yc5c4mbum {
  stop-color: var(--svg-color--b0a4b3, #B0A4B3);
  stop-opacity: 0;
}

.yq_gzpbvu {
  stop-color: var(--svg-color--d3cbd9, #D3CBD9);
}

.zfy8ajb0h {
  stop-color: var(--svg-color--c35385, #C35385);
}

.zlupwijhs {
  stop-color: var(--svg-color--ac9bbb, #AC9BBB);
}

</style>
