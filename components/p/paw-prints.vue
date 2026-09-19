<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ch5-yqoet"/><path fill="url(#i0Nqcxd)" class="dc5xaugie"/><path fill="url(#iG5ZbWb)" class="dc5xaugie"/><path class="vl7o1ks0a"/><path fill="url(#i2OlfAd)" class="wp43jv__l"/><path fill="url(#iAMNJKc)" class="wp43jv__l"/><path class="ysasgyq0i"/><path fill="url(#iYgLYJc)" class="pcdw3ybal"/><path fill="url(#idewird)" class="pcdw3ybal"/><path class="m04twabyt"/><path fill="url(#iHPYise)" class="h22vub0_j"/><path fill="url(#iRkqXFt)" class="h22vub0_j"/><g filter="url(#i4AwJVd)"><path class="u7ahyhbeg"/><path fill="url(#ivzv0Gd)" class="y7da9jbrp"/><path fill="url(#i0l2JBd)" class="y7da9jbrp"/><path fill="url(#i0pnoYd)" class="y7da9jbrp"/></g><path class="c0abt0b2x"/><path fill="url(#i6l3usb)" class="p8wyudtzv"/><path fill="url(#ip34fab)" class="p8wyudtzv"/><path class="psu12rb3g"/><path fill="url(#iSRUdCc)" class="tlwmhub_e"/><path fill="url(#ii35KEb)" class="tlwmhub_e"/><path class="l2z25pb6o"/><path fill="url(#ij2X6fb)" class="e-iip8bpv"/><path fill="url(#i1n2pub)" class="e-iip8bpv"/><path class="g023g8bmt"/><path fill="url(#iKjdWmb)" class="xpdzx-tvd"/><path fill="url(#igOVqPd)" class="xpdzx-tvd"/><g filter="url(#iFG7eUd)"><path class="thx8d3lki"/><path fill="url(#i7lsRqd)" class="lb34tz4km"/><path fill="url(#iPDGOab)" class="lb34tz4km"/><path fill="url(#ilC7wLb)" class="lb34tz4km"/></g><g filter="url(#iZvU4NK)"><path fill="url(#idYgiuc)" class="n-77ixbbd"/></g><g filter="url(#iqfStqb)"><path fill="url(#i2F0oEe)" class="q7qqmcbvi"/></g><g filter="url(#ijW10HG)"><ellipse fill="url(#ijkT0Zb)" transform="rotate(-30 16.515 21.11)" class="kac_eew3q"/></g><g filter="url(#iu0crZB)"><ellipse fill="url(#i0tCIxd)" transform="rotate(-30 19.929 19.07)" class="vbevfzuws"/></g><g filter="url(#iCk9wwT)"><ellipse fill="url(#ii2jFMc)" transform="rotate(-30 16 9.146)" class="ma43f0l2u"/></g><g filter="url(#iEhtBcd)"><ellipse fill="url(#iq2hNLU)" transform="rotate(-30 12.437 6.94)" class="c8_cepfpn"/></g><g filter="url(#ib6zw1d)"><ellipse fill="url(#izVYrKI)" transform="rotate(-30 8.078 7.023)" class="zfq50-vwi"/></g><g filter="url(#iSZVMxb)"><ellipse fill="url(#ilJv6ce)" transform="rotate(-30 4.437 8.981)" class="zsyjtzwgm"/></g><g filter="url(#iQSceDc)"><ellipse fill="url(#iua2Y2b)" transform="rotate(-30 24.437 18.986)" class="s02g6xbbz"/></g><g filter="url(#igm0rZl)"><ellipse fill="url(#iBjCJGb)" transform="rotate(-30 27.928 21.193)" class="ek0ucnhum"/></g><defs><radialGradient id="i0Nqcxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60192 -1.9571 1.53562 -1.25693 4.825 10.15)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="i2OlfAd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60192 -1.9571 1.53562 -1.25693 8.45 8.112)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="iYgLYJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60192 -1.9571 1.53562 -1.25693 12.825 8.112)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="iHPYise" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60192 -1.9571 1.53562 -1.25693 16.372 10.15)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="i0l2JBd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43886 2.45787 -3.5941 -6.49087 14.127 13.587)" gradientUnits="userSpaceOnUse"><stop class="bhwsbqbgx"/><stop offset="1" class="njy2r5bhu"/></radialGradient><radialGradient id="i0pnoYd" cx="0" cy="0" r="1" gradientTransform="rotate(-140.741 8.398 5.876)scale(6.4487 5.98399)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="i6l3usb" cx="0" cy="0" r="1" gradientTransform="matrix(.79078 -1.88745 1.74073 .7293 15.827 21.887)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="iSRUdCc" cx="0" cy="0" r="1" gradientTransform="matrix(.79078 -1.88745 1.74073 .7293 19.452 19.848)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="ij2X6fb" cx="0" cy="0" r="1" gradientTransform="matrix(.79078 -1.88745 1.74073 .7293 23.827 19.848)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="iKjdWmb" cx="0" cy="0" r="1" gradientTransform="matrix(.79078 -1.88745 1.74073 .7293 27.373 21.887)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="iPDGOab" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43886 2.45787 -3.5941 -6.49087 26.127 25.634)" gradientUnits="userSpaceOnUse"><stop class="bhwsbqbgx"/><stop offset="1" class="njy2r5bhu"/></radialGradient><radialGradient id="ilC7wLb" cx="0" cy="0" r="1" gradientTransform="rotate(-140.741 16.547 9.76)scale(6.4487 5.98399)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n9awq_knc"/><stop offset="1" class="t89zyxbqc"/></radialGradient><radialGradient id="ijkT0Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 17.08 21.156)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><radialGradient id="i0tCIxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 20.494 19.117)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><radialGradient id="ii2jFMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 16.565 9.193)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><radialGradient id="iq2hNLU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 13.002 6.986)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><radialGradient id="izVYrKI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 8.644 7.07)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><radialGradient id="ilJv6ce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 5.002 9.028)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><radialGradient id="iua2Y2b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 25.002 19.033)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><radialGradient id="iBjCJGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56306 .13112 -.14489 -1.7272 28.494 21.24)" gradientUnits="userSpaceOnUse"><stop class="cp4s5wb4q"/><stop offset="1" class="c8x737bdp"/></radialGradient><linearGradient id="iG5ZbWb" x1="4.171" x2="4.171" y1="12.067" y2="9.523" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="iAMNJKc" x1="7.796" x2="7.796" y1="10.028" y2="7.484" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="idewird" x1="12.171" x2="12.171" y1="10.028" y2="7.484" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="iRkqXFt" x1="15.718" x2="15.718" y1="12.067" y2="9.523" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="ivzv0Gd" x1="9.96" x2="9.96" y1="18.706" y2="13.969" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="ip34fab" x1="16.171" x2="16.171" y1="24.114" y2="21.57" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="ii35KEb" x1="19.796" x2="19.796" y1="22.075" y2="19.531" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="i1n2pub" x1="24.171" x2="24.171" y1="22.075" y2="19.531" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="igOVqPd" x1="27.718" x2="27.718" y1="24.114" y2="21.57" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="i7lsRqd" x1="21.96" x2="21.96" y1="30.753" y2="26.016" gradientUnits="userSpaceOnUse"><stop class="dqtg8z-zv"/><stop offset="1" class="hioljcp6l"/></linearGradient><linearGradient id="idYgiuc" x1="26.086" x2="23.476" y1="24.384" y2="25.829" gradientUnits="userSpaceOnUse"><stop class="c-c0qfkek"/><stop offset="1" class="ujtpm2dyq"/></linearGradient><linearGradient id="i2F0oEe" x1="13.912" x2="11.302" y1="12.345" y2="13.789" gradientUnits="userSpaceOnUse"><stop class="c-c0qfkek"/><stop offset="1" class="ujtpm2dyq"/></linearGradient><filter id="i4AwJVd" width="10.037" height="8.037" x="4.991" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.364706 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4554"/></filter><filter id="iFG7eUd" width="10.037" height="8.037" x="16.991" y="22.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.364706 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4554"/></filter><filter id="iZvU4NK" width="6.744" height="7.697" x="20.569" y="21.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="iqfStqb" width="6.744" height="7.697" x="8.395" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="ijW10HG" width="4.169" height="4.362" x="14.43" y="18.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="iu0crZB" width="4.169" height="4.362" x="17.844" y="16.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="iCk9wwT" width="4.169" height="4.362" x="13.915" y="6.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="iEhtBcd" width="4.169" height="4.362" x="10.352" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="ib6zw1d" width="4.169" height="4.362" x="5.993" y="4.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="iSZVMxb" width="4.169" height="4.362" x="2.352" y="6.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="iQSceDc" width="4.169" height="4.362" x="22.352" y="16.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter><filter id="igm0rZl" width="4.169" height="4.362" x="25.844" y="19.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4554" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:paw-prints" /></template>
<style>
.bhwsbqbgx {
  stop-color: var(--svg-color--534763, #534763);
}

.c-c0qfkek {
  stop-color: var(--svg-color--777081, #777081);
}

.c0abt0b2x {
  fill: var(--svg-color--453559, #453559);
  d: path("M17.945 21.36c0-1.626-1.184-1.829-1.844-1.829c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.c8_cepfpn {
  cx: 12.437px;
  cy: 6.939px;
  rx: 1.033px;
  ry: 1.226px;
}

.c8x737bdp {
  stop-color: var(--svg-color--5d5566, #5D5566);
  stop-opacity: 0;
}

.ch5-yqoet {
  fill: var(--svg-color--453559, #453559);
  d: path("M5.945 9.312c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.cp4s5wb4q {
  stop-color: var(--svg-color--80768b, #80768B);
}

.dc5xaugie {
  d: path("M5.945 9.312c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.dqtg8z-zv {
  stop-color: var(--svg-color--4c276c, #4C276C);
}

.e-iip8bpv {
  d: path("M25.945 19.32c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.ek0ucnhum {
  cx: 27.928px;
  cy: 21.193px;
  rx: 1.033px;
  ry: 1.226px;
}

.ft5dv1b6b {
  fill: none;
}

.g023g8bmt {
  fill: var(--svg-color--453559, #453559);
  d: path("M29.492 21.36c0-1.626-1.184-1.829-1.844-1.829c-.57 0-1.703.216-1.703 1.828s1.03 2.25 1.703 2.25c.672 0 1.843-.625 1.843-2.25");
}

.h22vub0_j {
  d: path("M17.492 9.312c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.03 2.25 1.703 2.25c.672 0 1.843-.625 1.843-2.25");
}

.hioljcp6l {
  stop-color: var(--svg-color--4c276c, #4C276C);
  stop-opacity: 0;
}

.kac_eew3q {
  cx: 16.515px;
  cy: 21.109px;
  rx: 1.033px;
  ry: 1.226px;
}

.l2z25pb6o {
  fill: var(--svg-color--453559, #453559);
  d: path("M25.945 19.32c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.lb34tz4km {
  d: path("M26.929 27.5c0-2.922-1.89-5.453-4.984-5.453S16.99 24.516 16.99 27.5c0 2.484 2.962 2.484 4.946 2.484h.008c2.203 0 4.984-.078 4.984-2.484");
}

.m04twabyt {
  fill: var(--svg-color--453559, #453559);
  d: path("M17.492 9.312c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.03 2.25 1.703 2.25c.672 0 1.843-.625 1.843-2.25");
}

.ma43f0l2u {
  cx: 16px;
  cy: 9.146px;
  rx: 1.033px;
  ry: 1.226px;
}

.n-77ixbbd {
  d: path("M24.235 27.23c-.265-3.102-1.95-4.584-2.666-4.63c3.759 0 4.58 2.992 4.74 4.702a.91.91 0 0 1-.481.87c-.683.378-1.526-.165-1.593-.942");
}

.n9awq_knc {
  stop-color: var(--svg-color--312c39, #312C39);
  stop-opacity: 0;
}

.njy2r5bhu {
  stop-color: var(--svg-color--534763, #534763);
  stop-opacity: 0;
}

.p8wyudtzv {
  d: path("M17.945 21.36c0-1.626-1.184-1.829-1.844-1.829c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.pcdw3ybal {
  d: path("M13.945 7.273c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.psu12rb3g {
  fill: var(--svg-color--453559, #453559);
  d: path("M21.57 19.32c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.q7qqmcbvi {
  d: path("M12.061 15.19c-.265-3.101-1.95-4.584-2.666-4.63c3.759 0 4.58 2.992 4.74 4.702a.91.91 0 0 1-.481.871c-.682.378-1.526-.165-1.593-.942");
}

.s02g6xbbz {
  cx: 24.437px;
  cy: 18.986px;
  rx: 1.033px;
  ry: 1.226px;
}

.t89zyxbqc {
  stop-color: var(--svg-color--312c39, #312C39);
}

.thx8d3lki {
  fill: var(--svg-color--453559, #453559);
  d: path("M26.929 27.5c0-2.922-1.89-5.453-4.984-5.453S16.99 24.516 16.99 27.5c0 2.484 2.962 2.484 4.946 2.484h.008c2.203 0 4.984-.078 4.984-2.484");
}

.tlwmhub_e {
  d: path("M21.57 19.32c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.u7ahyhbeg {
  fill: var(--svg-color--453559, #453559);
  d: path("M14.929 15.453c0-2.922-1.89-5.453-4.984-5.453S4.99 12.469 4.99 15.453c0 2.485 2.962 2.485 4.946 2.485h.008c2.203 0 4.984-.079 4.984-2.485");
}

.ujtpm2dyq {
  stop-color: var(--svg-color--6a6373, #6A6373);
  stop-opacity: 0;
}

.vbevfzuws {
  cx: 19.929px;
  cy: 19.07px;
  rx: 1.033px;
  ry: 1.226px;
}

.vl7o1ks0a {
  fill: var(--svg-color--453559, #453559);
  d: path("M9.57 7.273c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.wp43jv__l {
  d: path("M9.57 7.273c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.xpdzx-tvd {
  d: path("M29.492 21.36c0-1.626-1.184-1.829-1.844-1.829c-.57 0-1.703.216-1.703 1.828s1.03 2.25 1.703 2.25c.672 0 1.843-.625 1.843-2.25");
}

.y7da9jbrp {
  d: path("M14.929 15.453c0-2.922-1.89-5.453-4.984-5.453S4.99 12.469 4.99 15.453c0 2.485 2.962 2.485 4.946 2.485h.008c2.203 0 4.984-.079 4.984-2.485");
}

.ysasgyq0i {
  fill: var(--svg-color--453559, #453559);
  d: path("M13.945 7.273c0-1.625-1.184-1.828-1.844-1.828c-.57 0-1.703.216-1.703 1.828s1.031 2.25 1.703 2.25s1.844-.625 1.844-2.25");
}

.zfq50-vwi {
  cx: 8.078px;
  cy: 7.023px;
  rx: 1.033px;
  ry: 1.226px;
}

.zsyjtzwgm {
  cx: 4.437px;
  cy: 8.981px;
  rx: 1.033px;
  ry: 1.226px;
}

</style>
