<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="tbdelzhtr"/><path class="y3h-87zzv"/><path fill="url(#im5Jswc)" class="sbdf1bb1g"/><path fill="url(#iRqM5ve)" class="sbdf1bb1g"/><path fill="url(#iobzi2c)" class="sbdf1bb1g"/><path fill="url(#iHOebDe)" class="sbdf1bb1g"/><path fill="url(#ilrgoHt)" class="sbdf1bb1g"/><path fill="url(#iPqOmbd)" class="sbdf1bb1g"/><path fill="url(#iipp5Bc)" class="sbdf1bb1g"/><path fill="url(#izwZa9c)" class="sbdf1bb1g"/><path fill="url(#i8g1YWc)" class="sbdf1bb1g"/><path fill="url(#iIKyhUb)" class="sbdf1bb1g"/><path fill="url(#i98Gukb)" class="sbdf1bb1g"/><path fill="url(#iDE9DQb)" class="sbdf1bb1g"/><path class="xazdjybpl"/><path fill="url(#inN3ebe)" class="chkebcmzu"/><path fill="url(#iEpXMqe)" class="chkebcmzu"/><path fill="url(#ielANRd)" class="chkebcmzu"/><path fill="url(#iKVQgye)" class="chkebcmzu"/><path fill="url(#iU81YRc)" class="chkebcmzu"/><path fill="url(#iVKsIcd)" class="chkebcmzu"/><defs><radialGradient id="im5Jswc" cx="0" cy="0" r="1" gradientTransform="rotate(133.409 11.153 8.269)scale(1.85363 22.4395)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="ycoup5wdj"/><stop offset=".453" class="tpnkh7byy"/><stop offset="1" class="vlztjhb3c"/></radialGradient><radialGradient id="iRqM5ve" cx="0" cy="0" r="1" gradientTransform="rotate(133.781 11.619 7.963)scale(1.51227 24.181)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="wz9b_e0-w"/><stop offset="1" class="vlztjhb3c"/><stop offset="1" class="jedx2ccyq"/></radialGradient><radialGradient id="iobzi2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.12822 1.23743 -20.99307 19.14044 25.261 15.676)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="oir76sqmm"/><stop offset=".528" class="x7eikgb-u"/><stop offset="1" class="ap-i9rbmn"/></radialGradient><radialGradient id="iHOebDe" cx="0" cy="0" r="1" gradientTransform="rotate(75.772 6.887 14)scale(5.14953 2.78677)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="eox53bcjy"/><stop offset=".931" class="fh3236buo"/></radialGradient><radialGradient id="ilrgoHt" cx="0" cy="0" r="1" gradientTransform="rotate(88.66 6.512 13.002)scale(1.3363 1.01632)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="eox53bcjy"/><stop offset=".931" class="ir7445ovy"/></radialGradient><radialGradient id="iPqOmbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29201 0 0 -.62584 18.765 8.36)" gradientUnits="userSpaceOnUse"><stop class="bpg2ifbok"/><stop offset="1" class="nmnhuhcpf"/></radialGradient><radialGradient id="iipp5Bc" cx="0" cy="0" r="1" gradientTransform="rotate(114.267 4.996 13.4)scale(2.19063 1.93598)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="g4bzuacbg"/><stop offset=".555" class="jxjvjbbsc"/><stop offset=".984" class="grm0g-4db"/></radialGradient><radialGradient id="izwZa9c" cx="0" cy="0" r="1" gradientTransform="rotate(92.021 1.487 18.128)scale(5.31581 1.72287)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="e55h6qtxz"/><stop offset="1" class="jg9jk97fk"/></radialGradient><radialGradient id="i8g1YWc" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 2.59375 -1.89724 .02286 19.187 15.547)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="e55h6qtxz"/><stop offset="1" class="jg9jk97fk"/></radialGradient><radialGradient id="iIKyhUb" cx="0" cy="0" r="1" gradientTransform="matrix(.34575 -.76429 .5172 .23397 20.621 18.15)" gradientUnits="userSpaceOnUse"><stop class="z349tsbtk"/><stop offset="1" class="om0q0xbfn"/></radialGradient><radialGradient id="i98Gukb" cx="0" cy="0" r="1" gradientTransform="rotate(168.69 9.513 5.066)scale(1.01582 .66678)" gradientUnits="userSpaceOnUse"><stop class="h-249ac1z"/><stop offset="1" class="agsq3mfqq"/></radialGradient><radialGradient id="iDE9DQb" cx="0" cy="0" r="1" gradientTransform="rotate(94.467 2.958 15.992)scale(1.00305)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="q_ssxwb0p"/><stop offset=".953" class="ru8rgcq0q"/></radialGradient><radialGradient id="inN3ebe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 -1.43751 22.03036 -20.5933 25.629 15.437)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="oir76sqmm"/><stop offset=".586" class="x7eikgb-u"/><stop offset="1" class="ap-i9rbmn"/></radialGradient><radialGradient id="iEpXMqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.25 -12.38957 -11.15053 25.879 6.125)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="ad3ffbcvf"/><stop offset="1" class="yhyazbcky"/></radialGradient><radialGradient id="iKVQgye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.97363 43.6773 0 10.316 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="s1u8bgjjw"/><stop offset=".491" class="h4o422rpj"/><stop offset="1" class="gx0eq4bra"/></radialGradient><radialGradient id="iU81YRc" cx="0" cy="0" r="1" gradientTransform="matrix(.25 .45312 -1.08733 .59992 19.672 6.773)" gradientUnits="userSpaceOnUse"><stop class="eox53bcjy"/><stop offset=".931" class="ir7445ovy"/></radialGradient><radialGradient id="iVKsIcd" cx="0" cy="0" r="1" gradientTransform="rotate(88.975 -3.77 5.485)scale(14.4086 2.56153)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="eox53bcjy"/><stop offset=".931" class="fh3236buo"/></radialGradient><linearGradient id="ielANRd" x1="10.285" x2="10.285" y1="7.094" y2="8.906" gradientUnits="userSpaceOnUse"><stop offset=".122" class="qb9-xmb9c"/><stop offset=".5" class="d2gu7fb7r"/><stop offset=".689" class="ctkqcab7d"/><stop offset="1" class="m57pq8bjw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:soon-arrow" /></template>
<style>
.ad3ffbcvf {
  stop-color: var(--svg-color--483f6e, #483F6E);
}

.agsq3mfqq {
  stop-color: var(--svg-color--8172c3, #8172C3);
  stop-opacity: 0;
}

.ap-i9rbmn {
  stop-color: var(--svg-color--7647cd, #7647CD);
  stop-opacity: 0;
}

.bpg2ifbok {
  stop-color: var(--svg-color--8a7ec6, #8A7EC6);
}

.chkebcmzu {
  d: path("M19.73 14.761c0-.35-.355-.941-.906-.941H3.23c-.66 0-1.19-.53-1.19-1.19V8.42c0-.66.53-1.19 1.19-1.19h15.606c.422 0 .895-.453.895-.957z");
}

.ctkqcab7d {
  stop-color: var(--svg-color--8273c3, #8273C3);
}

.d2gu7fb7r {
  stop-color: var(--svg-color--8172c2, #8172C2);
}

.e55h6qtxz {
  stop-color: var(--svg-color--463385, #463385);
}

.eox53bcjy {
  stop-color: var(--svg-color--46377a, #46377A);
}

.fh3236buo {
  stop-color: var(--svg-color--6d5dad, #6D5DAD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4bzuacbg {
  stop-color: var(--svg-color--5f37ba, #5F37BA);
}

.grm0g-4db {
  stop-color: var(--svg-color--8155d1, #8155D1);
  stop-opacity: 0;
}

.gx0eq4bra {
  stop-color: var(--svg-color--8745e5, #8745E5);
  stop-opacity: 0;
}

.h-249ac1z {
  stop-color: var(--svg-color--8172c3, #8172C3);
}

.h4o422rpj {
  stop-color: var(--svg-color--8745e5, #8745E5);
}

.ir7445ovy {
  stop-color: var(--svg-color--46377a, #46377A);
  stop-opacity: 0;
}

.jedx2ccyq {
  stop-color: var(--svg-color--7062a8, #7062A8);
  stop-opacity: 0;
}

.jg9jk97fk {
  stop-color: var(--svg-color--7e6cc3, #7E6CC3);
  stop-opacity: 0;
}

.jxjvjbbsc {
  stop-color: var(--svg-color--8645e3, #8645E3);
}

.m57pq8bjw {
  stop-color: var(--svg-color--8172c2, #8172C2);
  stop-opacity: 0;
}

.nmnhuhcpf {
  stop-color: var(--svg-color--8a7ec6, #8A7EC6);
  stop-opacity: 0;
}

.oir76sqmm {
  stop-color: var(--svg-color--5836ab, #5836AB);
}

.om0q0xbfn {
  stop-color: var(--svg-color--8e4fec, #8E4FEC);
  stop-opacity: 0;
}

.q_ssxwb0p {
  stop-color: var(--svg-color--5e36ba, #5E36BA);
}

.qb9-xmb9c {
  stop-color: var(--svg-color--635796, #635796);
}

.ru8rgcq0q {
  stop-color: var(--svg-color--5e36ba, #5E36BA);
  stop-opacity: 0;
}

.s1u8bgjjw {
  stop-color: var(--svg-color--5e36b9, #5E36B9);
}

.sbdf1bb1g {
  d: path("m21.327 2.252l8.315 7.57a.947.947 0 0 1 0 1.41l-8.315 7.57c-.617.558-1.607.116-1.607-.711v-3.32a.96.96 0 0 0-.955-.954v-6.58a.96.96 0 0 0 .955-.956V2.962c0-.838.99-1.27 1.607-.71");
}

.tbdelzhtr {
  fill: var(--svg-color--7763bb, #7763BB);
  d: path("M12.03 30c-1.73 0-3.14-1.41-3.14-3.14v-2.88c0-1.73 1.41-3.14 3.14-3.14s3.14 1.41 3.14 3.14v2.88c0 1.73-1.41 3.14-3.14 3.14m0-7.17c-.63 0-1.15.51-1.15 1.15v2.88a1.15 1.15 0 0 0 2.3 0v-2.88c0-.64-.52-1.15-1.15-1.15m3.95 4.03c0 1.73 1.41 3.14 3.14 3.14s3.14-1.41 3.14-3.14v-2.88c0-1.73-1.41-3.14-3.14-3.14s-3.14 1.41-3.14 3.14zm1.99-2.88a1.15 1.15 0 0 1 2.3 0v2.88a1.15 1.15 0 0 1-2.3 0zM5.38 30c-1.12 0-2.2-.41-3.03-1.16a.998.998 0 1 1 1.33-1.49c.47.42 1.07.65 1.7.65h.15c.28-.02.47-.12.59-.3c.14-.22.1-.43.06-.54a.69.69 0 0 0-.42-.43l-1.98-.74c-.76-.29-1.35-.89-1.61-1.67c-.25-.76-.16-1.58.27-2.24c.47-.74 1.23-1.17 2.16-1.23c.09-.01.18-.01.27-.01c1.12 0 2.2.41 3.03 1.16a.998.998 0 1 1-1.33 1.49c-.47-.42-1.07-.65-1.7-.65h-.15c-.28.02-.47.12-.59.3c-.14.22-.1.43-.06.54c.07.2.22.36.42.43l1.98.74c.76.29 1.35.89 1.61 1.67c.25.76.16 1.58-.27 2.24c-.47.74-1.23 1.17-2.16 1.23c-.09.01-.18.01-.27.01m22.73-.45c.18.29.5.45.83.45c.09 0 .19-.01.29-.04c.42-.13.71-.52.71-.96v-7.17c0-.55-.45-1-1-1s-1 .45-1 1v3.83l-2.87-4.38a.99.99 0 0 0-1.12-.41c-.42.13-.71.52-.71.96V29c0 .55.45 1 1 1s1-.45 1-1v-3.83z");
}

.tpnkh7byy {
  stop-color: var(--svg-color--998ed2, #998ED2);
}

.vlztjhb3c {
  stop-color: var(--svg-color--8677c6, #8677C6);
  stop-opacity: 0;
}

.wz9b_e0-w {
  stop-color: var(--svg-color--7062a8, #7062A8);
}

.x7eikgb-u {
  stop-color: var(--svg-color--7647cd, #7647CD);
}

.xazdjybpl {
  fill: var(--svg-color--7969b8, #7969B8);
  d: path("M19.73 14.761c0-.35-.355-.941-.906-.941H3.23c-.66 0-1.19-.53-1.19-1.19V8.42c0-.66.53-1.19 1.19-1.19h15.606c.422 0 .895-.453.895-.957z");
}

.y3h-87zzv {
  fill: var(--svg-color--7969b8, #7969B8);
  d: path("m21.327 2.252l8.315 7.57a.947.947 0 0 1 0 1.41l-8.315 7.57c-.617.558-1.607.116-1.607-.711v-3.32a.96.96 0 0 0-.955-.954v-6.58a.96.96 0 0 0 .955-.956V2.962c0-.838.99-1.27 1.607-.71");
}

.ycoup5wdj {
  stop-color: var(--svg-color--9d92d4, #9D92D4);
}

.yhyazbcky {
  stop-color: var(--svg-color--5f5395, #5F5395);
  stop-opacity: 0;
}

.z349tsbtk {
  stop-color: var(--svg-color--8e4fec, #8E4FEC);
}

</style>
