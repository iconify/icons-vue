<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iefAtFb)"><path fill="url(#iQX3Bvd)" class="zv5_5cbmi"/><path fill="url(#iuhycod)" class="zv5_5cbmi"/><path fill="url(#ioXvfye)" class="zv5_5cbmi"/><path fill="url(#iV2sVzd)" class="zv5_5cbmi"/></g><path class="hllc66bdl"/><path fill="url(#iMvif2n)" class="b_fztfwog"/><path fill="url(#iNvKSyb)" class="b_fztfwog"/><path fill="url(#iBjdhDc)" class="b_fztfwog"/><path fill="url(#ilfxXQb)" class="b_fztfwog"/><path fill="url(#igymkiP)" class="b_fztfwog"/><path class="abpxb5b_v"/><path fill="url(#invxWzc)" class="lsrdapbwa"/><path fill="url(#iXvt1md)" class="lsrdapbwa"/><path fill="url(#iMHNUyX)" class="lsrdapbwa"/><path fill="url(#isMDWLd)" class="lsrdapbwa"/><path fill="url(#i66eXQd)" class="yn91fpbaj"/><path fill="url(#iIe0uSq)" class="yn91fpbaj"/><path fill="url(#iMymaXd)" class="yn91fpbaj"/><g filter="url(#iz2GaLd)"><path fill="url(#iIGZ69c)" class="yn91fpbaj"/></g><defs><radialGradient id="iQX3Bvd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.3738 0 0 -17.5807 24.634 24.07)" gradientUnits="userSpaceOnUse"><stop class="rwoqivb2l"/><stop offset="1" class="z0fk3vowp"/></radialGradient><radialGradient id="ioXvfye" cx="0" cy="0" r="1" gradientTransform="matrix(1.90694 6.402 -9.89573 2.9476 10.264 22.33)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="cj0yxbbci"/><stop offset="1" class="lzoj_bb-v"/></radialGradient><radialGradient id="iV2sVzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.76433 -.82347 0 24.513 24.76)" gradientUnits="userSpaceOnUse"><stop class="ual0ijb5y"/><stop offset="1" class="l_qf2nbgc"/></radialGradient><radialGradient id="iMvif2n" cx="0" cy="0" r="1" gradientTransform="rotate(111.194 1.954 14.484)scale(6.56934 6.56696)" gradientUnits="userSpaceOnUse"><stop class="uijot-uby"/><stop offset="1" class="chet01bgr"/></radialGradient><radialGradient id="iNvKSyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.94531 9.1875 0 12.478 25.719)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="h_frev0og"/><stop offset="1" class="sc6jbbc9e"/></radialGradient><radialGradient id="iBjdhDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.8125 -10.9 0 22.478 15.273)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="h11s0qbld"/><stop offset="1" class="tchvl7btb"/></radialGradient><radialGradient id="ilfxXQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.4375 -7.62422 0 4.978 15.398)" gradientUnits="userSpaceOnUse"><stop class="obe_avubp"/><stop offset="1" class="ubrmkkbdh"/></radialGradient><radialGradient id="igymkiP" cx="0" cy="0" r="1" gradientTransform="rotate(163.654 6.61 10.083)scale(13.1026 16.1336)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="j-yvvz_nd"/><stop offset="1" class="gc649hati"/></radialGradient><radialGradient id="invxWzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.59375 11.0436 0 17.166 17.242)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="qgm1kbbfi"/><stop offset="1" class="f-h4m_dro"/></radialGradient><radialGradient id="iXvt1md" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 0 0 3.15652 3.353 15.273)" gradientUnits="userSpaceOnUse"><stop class="qgm1kbbfi"/><stop offset="1" class="f-h4m_dro"/></radialGradient><radialGradient id="isMDWLd" cx="0" cy="0" r="1" gradientTransform="rotate(131.1 6.668 11.697)scale(4.24778 16.1579)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="aj77jnblg"/><stop offset="1" class="r2u0w7bxi"/></radialGradient><radialGradient id="iIe0uSq" cx="0" cy="0" r="1" gradientTransform="rotate(146.976 13.82 5.52)scale(1.49086 .44608)" gradientUnits="userSpaceOnUse"><stop class="iipqj-bzm"/><stop offset="1" class="swd-v0fmj"/></radialGradient><linearGradient id="iuhycod" x1="24.906" x2="22.318" y1="16.745" y2="25.19" gradientUnits="userSpaceOnUse"><stop class="yyugmoy8i"/><stop offset="1" class="zsoc8r32k"/></linearGradient><linearGradient id="iMHNUyX" x1="15.303" x2="15.303" y1="17.242" y2="16.779" gradientUnits="userSpaceOnUse"><stop class="w6io43him"/><stop offset="1" class="wehvcjx6e"/></linearGradient><linearGradient id="i66eXQd" x1="24.197" x2="24.197" y1="2.117" y2="3.523" gradientUnits="userSpaceOnUse"><stop class="wls1ypbcc"/><stop offset="1" class="m-pyldb9i"/></linearGradient><linearGradient id="iMymaXd" x1="26.197" x2="26.197" y1="18.023" y2="16.68" gradientUnits="userSpaceOnUse"><stop class="as_grs-oc"/><stop offset="1" class="ynfn-u7_g"/></linearGradient><linearGradient id="iIGZ69c" x1="24.197" x2="24.197" y1="2.352" y2="17.742" gradientUnits="userSpaceOnUse"><stop class="b0_d0nbkq"/><stop offset="1" class="bgwswgrbe"/></linearGradient><filter id="iefAtFb" width="20.149" height="13.306" x="6.622" y="17.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.662745 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25789"/></filter><filter id="iz2GaLd" width="10.938" height="16.141" x="18.978" y="1.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.721569 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25789"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.615686 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25789" result="effect2_innerShadow_18_25789"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.882353 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_25789" result="effect3_innerShadow_18_25789"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:toilet" /></template>
<style>
.abpxb5b_v {
  fill: var(--svg-color--beb0cd, #BEB0CD);
  d: path("M2.947 15.758a1 1 0 0 1 1-1h19.61v2.484H3.296a.35.35 0 0 1-.35-.35z");
}

.aj77jnblg {
  stop-color: var(--svg-color--a89eb5, #A89EB5);
}

.as_grs-oc {
  stop-color: var(--svg-color--b99fd5, #B99FD5);
}

.b_fztfwog {
  d: path("M3.218 16.805c.512 5.007 4.742 8.914 9.885 8.914s9.373-3.907 9.886-8.914z");
}

.b0_d0nbkq {
  stop-color: var(--svg-color--d8cfe5, #D8CFE5);
}

.bgwswgrbe {
  stop-color: var(--svg-color--d2c4e4, #D2C4E4);
}

.chet01bgr {
  stop-color: var(--svg-color--ccbae0, #CCBAE0);
  stop-opacity: 0;
}

.cj0yxbbci {
  stop-color: var(--svg-color--baa2d5, #BAA2D5);
}

.f-h4m_dro {
  stop-color: var(--svg-color--d0c4de, #D0C4DE);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gc649hati {
  stop-color: var(--svg-color--d0cbd8, #D0CBD8);
}

.h_frev0og {
  stop-color: var(--svg-color--b492d6, #B492D6);
}

.h11s0qbld {
  stop-color: var(--svg-color--9f8cb4, #9F8CB4);
}

.hllc66bdl {
  fill: var(--svg-color--bba8d2, #BBA8D2);
  d: path("M3.218 16.805c.512 5.007 4.742 8.914 9.885 8.914s9.373-3.907 9.886-8.914z");
}

.iipqj-bzm {
  stop-color: var(--svg-color--f2eff7, #F2EFF7);
}

.j-yvvz_nd {
  stop-color: var(--svg-color--d0cbd8, #D0CBD8);
  stop-opacity: 0;
}

.l_qf2nbgc {
  stop-color: var(--svg-color--ebe0f8, #EBE0F8);
  stop-opacity: 0;
}

.lsrdapbwa {
  d: path("M2.947 15.758a1 1 0 0 1 1-1h19.61v2.484H3.296a.35.35 0 0 1-.35-.35z");
}

.lzoj_bb-v {
  stop-color: var(--svg-color--baa2d5, #BAA2D5);
  stop-opacity: 0;
}

.m-pyldb9i {
  stop-color: var(--svg-color--d7d5db, #D7D5DB);
  stop-opacity: 0;
}

.obe_avubp {
  stop-color: var(--svg-color--a79bb6, #A79BB6);
}

.qgm1kbbfi {
  stop-color: var(--svg-color--d0c4de, #D0C4DE);
}

.r2u0w7bxi {
  stop-color: var(--svg-color--a89eb5, #A89EB5);
  stop-opacity: 0;
}

.rwoqivb2l {
  stop-color: var(--svg-color--decff0, #DECFF0);
}

.sc6jbbc9e {
  stop-color: var(--svg-color--b494d5, #B494D5);
  stop-opacity: 0;
}

.swd-v0fmj {
  stop-color: var(--svg-color--ebe2f7, #EBE2F7);
  stop-opacity: 0;
}

.tchvl7btb {
  stop-color: var(--svg-color--cab8df, #CAB8DF);
  stop-opacity: 0;
}

.ual0ijb5y {
  stop-color: var(--svg-color--ebe0f8, #EBE0F8);
}

.ubrmkkbdh {
  stop-color: var(--svg-color--a79bb6, #A79BB6);
  stop-opacity: 0;
}

.uijot-uby {
  stop-color: var(--svg-color--ccbae0, #CCBAE0);
}

.w6io43him {
  stop-color: var(--svg-color--b5adc0, #B5ADC0);
}

.wehvcjx6e {
  stop-color: var(--svg-color--b5adc0, #B5ADC0);
  stop-opacity: 0;
}

.wls1ypbcc {
  stop-color: var(--svg-color--d7d5db, #D7D5DB);
}

.yn91fpbaj {
  d: path("M19.978 3.002a.65.65 0 0 1 .65-.65h7.138a.65.65 0 0 1 .65.65v12.24a2.5 2.5 0 0 1-2.5 2.5h-3.438a2.5 2.5 0 0 1-2.5-2.5z");
}

.ynfn-u7_g {
  stop-color: var(--svg-color--b99fd5, #B99FD5);
  stop-opacity: 0;
}

.yyugmoy8i {
  stop-color: var(--svg-color--baa6d0, #BAA6D0);
}

.z0fk3vowp {
  stop-color: var(--svg-color--cdbae4, #CDBAE4);
}

.zsoc8r32k {
  stop-color: var(--svg-color--baa6d0, #BAA6D0);
  stop-opacity: 0;
}

.zv5_5cbmi {
  d: path("M24.306 21.273c0-2.765 1.453-3.5 2.266-3.656H13.04L6.748 29.041a1 1 0 0 0 .876 1.482h14.682a2 2 0 0 0 2-1.999z");
}

</style>
