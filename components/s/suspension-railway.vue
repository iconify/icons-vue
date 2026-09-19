<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#il8AXtd)" class="vt206obwd"/><g filter="url(#iWy2b2d)"><path fill="url(#ia7fz6d)" class="vt206obwd"/></g><path fill="url(#iDLTdje)" class="vt206obwd"/><path fill="url(#iQsR7bb)" class="cp-8_o_vi"/><path fill="url(#ihWlKqe)" class="cp-8_o_vi"/><path fill="url(#idQP9le)" class="pv9rmh2eg"/><path fill="url(#iXw4ieL)" class="pv9rmh2eg"/><path fill="url(#irWMgsd)" class="vbo5qbcfz"/><g filter="url(#iwUqKve)"><path class="zokric68q"/></g><path fill="url(#iglST4d)" class="qfllb7hun"/><path fill="url(#iJq8ZPb)" class="u8in69b8w"/><path fill="url(#iQPqHee)" class="u8in69b8w"/><path fill="url(#iXBVgUc)" class="u8in69b8w"/><g filter="url(#iq1p5Oc)"><path fill="url(#ilm8tZb)" class="jlajlkb6g"/></g><path fill="url(#i63ywbb)" class="ge-asxv_k"/><path fill="url(#iVu6Jkc)" class="tzjyfabxq"/><g filter="url(#il1dFIc)"><path fill="url(#iOZQSpb)" class="ge-asxv_k"/></g><g filter="url(#ipaDoye)"><path fill="url(#iDPZgob)" class="tzjyfabxq"/></g><path fill="url(#iRwXzze)" class="v2ysev_pr"/><path fill="url(#iFnquOF)" class="v2ysev_pr"/><path fill="url(#ioA4Xqb)" class="clvaovrzg"/><path fill="url(#imWhIPb)" class="clvaovrzg"/><path fill="url(#iKrmRGd)" class="clvaovrzg"/><path fill="url(#if8Z7mb)" class="bek4ghb0w"/><path fill="url(#ixTOAke)" class="bek4ghb0w"/><path fill="url(#iw7PUsb)" class="fg1-dxbrx"/><defs><linearGradient id="il8AXtd" x1="17.577" x2="17.516" y1="21.003" y2="35.5" gradientUnits="userSpaceOnUse"><stop offset=".519" class="vc--wpv5i"/><stop offset=".642" class="ykq--y_8h"/><stop offset=".754" class="sm1teyw2a"/></linearGradient><linearGradient id="ia7fz6d" x1="2.02" x2="30.02" y1="24.678" y2="24.678" gradientUnits="userSpaceOnUse"><stop class="taue81kbj"/><stop offset="1" class="hfv13198d"/></linearGradient><linearGradient id="iDLTdje" x1="30.02" x2="28.507" y1="22.004" y2="22.004" gradientUnits="userSpaceOnUse"><stop class="ovs_5abkg"/><stop offset="1" class="as-ub2bld"/></linearGradient><linearGradient id="iQsR7bb" x1="2.02" x2="30.322" y1="6" y2="6" gradientUnits="userSpaceOnUse"><stop class="hghvyqyng"/><stop offset="1" class="ihg21322o"/></linearGradient><linearGradient id="idQP9le" x1="30.582" x2="2.708" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="p2bz6xaok"/><stop offset="1" class="awehjacnx"/></linearGradient><linearGradient id="irWMgsd" x1="30.582" x2="2.708" y1="7" y2="7" gradientUnits="userSpaceOnUse"><stop class="p2bz6xaok"/><stop offset="1" class="awehjacnx"/></linearGradient><linearGradient id="iglST4d" x1="2.02" x2="3.921" y1="14.361" y2="14.361" gradientUnits="userSpaceOnUse"><stop offset=".255" class="di0pbrc_x"/><stop offset="1" class="pumcc_aja"/></linearGradient><linearGradient id="iJq8ZPb" x1="2.411" x2="23.236" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="ciz7q9d2j"/><stop offset="1" class="v3jx2d1bw"/></linearGradient><linearGradient id="iXBVgUc" x1="30.04" x2="28.858" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="gkaxbebhv"/><stop offset="1" class="z_3m-0bbd"/></linearGradient><linearGradient id="ilm8tZb" x1="3.02" x2="12.02" y1="23.25" y2="13.625" gradientUnits="userSpaceOnUse"><stop class="m4vxu3qez"/><stop offset="1" class="t77dcut_r"/></linearGradient><linearGradient id="i63ywbb" x1="12.518" x2="20.627" y1="18.002" y2="18.002" gradientUnits="userSpaceOnUse"><stop class="vkh_zubet"/><stop offset=".733" class="k5u7lbcal"/><stop offset=".942" class="gds77obnh"/></linearGradient><linearGradient id="iVu6Jkc" x1="20.518" x2="28.627" y1="18.002" y2="18.002" gradientUnits="userSpaceOnUse"><stop class="vkh_zubet"/><stop offset=".733" class="k5u7lbcal"/><stop offset=".942" class="gds77obnh"/></linearGradient><linearGradient id="iOZQSpb" x1="14.62" x2="21.664" y1="21.4" y2="15.75" gradientUnits="userSpaceOnUse"><stop class="zasaeub2s"/><stop offset="1" class="t77dcut_r"/><stop offset="1" class="pj2i25v0y"/></linearGradient><linearGradient id="iDPZgob" x1="22.62" x2="29.664" y1="21.4" y2="15.75" gradientUnits="userSpaceOnUse"><stop class="zasaeub2s"/><stop offset="1" class="t77dcut_r"/><stop offset="1" class="pj2i25v0y"/></linearGradient><linearGradient id="iRwXzze" x1="11.02" x2="21.02" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="vo0ul_xjo"/><stop offset=".063" class="v2zdd5jwa"/><stop offset=".93" class="v2zdd5jwa"/><stop offset="1" class="v5mkgpb0m"/></linearGradient><linearGradient id="iFnquOF" x1="16.02" x2="16.02" y1="11" y2="11.266" gradientUnits="userSpaceOnUse"><stop class="q5rgccb4p"/><stop offset="1" class="uwu0mxa-j"/></linearGradient><linearGradient id="ioA4Xqb" x1="11.02" x2="21.02" y1="5" y2="5" gradientUnits="userSpaceOnUse"><stop class="g32tbkeva"/><stop offset=".191" class="sqkpcmbna"/><stop offset=".803" class="sqkpcmbna"/><stop offset="1" class="qjbnq53mx"/></linearGradient><linearGradient id="imWhIPb" x1="17.582" x2="17.582" y1="7" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="g223hhx9k"/><stop offset="1" class="jv6p1eb5t"/></linearGradient><linearGradient id="iKrmRGd" x1="16.02" x2="16.02" y1="2.082" y2="4.059" gradientUnits="userSpaceOnUse"><stop class="t1emytk5a"/><stop offset=".943" class="apv_-xb-d"/></linearGradient><linearGradient id="if8Z7mb" x1="17.02" x2="15.207" y1="8.281" y2="8.281" gradientUnits="userSpaceOnUse"><stop class="ccop9ib7d"/><stop offset="1" class="qgrd4ybtf"/></linearGradient><linearGradient id="iw7PUsb" x1="14.02" x2="17.677" y1="11" y2="11" gradientUnits="userSpaceOnUse"><stop class="ob2927byv"/><stop offset="1" class="s53ynhzyr"/></linearGradient><filter id="iWy2b2d" width="28.5" height="18.5" x="2.02" y="11.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.556863 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12890"/></filter><filter id="iwUqKve" width="28.75" height="4.75" x="1.27" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.643137 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12890"/></filter><filter id="iq1p5Oc" width="12" height="11.25" x=".02" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-2" dy="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.670588 0 0 0 0 0.913725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12890"/></filter><filter id="il1dFIc" width="6.75" height="8.5" x="13.27" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.670588 0 0 0 0 0.913725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12890"/></filter><filter id="ipaDoye" width="6.75" height="8.5" x="21.27" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.670588 0 0 0 0 0.913725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12890"/></filter><radialGradient id="ihWlKqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .90624 -1.24528 -1.46 12.098 5.734)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="bwi8tgn0u"/><stop offset="1" class="y6vyhk1ok"/></radialGradient><radialGradient id="iXw4ieL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76563 0 0 -1.85938 12.223 5)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="x1e1hp_8q"/><stop offset="1" class="wbnzwtozk"/></radialGradient><radialGradient id="iQPqHee" cx="0" cy="0" r="1" gradientTransform="matrix(-23.87508 7.94588 -111.24257 -334.25167 26.31 19.054)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="gi-s0xm_l"/><stop offset=".993" class="rjrf3rbph"/></radialGradient><radialGradient id="ixTOAke" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.37883 3.12506 0 16.02 11)" gradientUnits="userSpaceOnUse"><stop offset=".917" class="re9um8bmb"/><stop offset=".984" class="qgrd4ybtf"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:suspension-railway" /></template>
<style>
.apv_-xb-d {
  stop-color: var(--svg-color--706c75, #706C75);
  stop-opacity: 0;
}

.as-ub2bld {
  stop-color: var(--svg-color--f0e9f5, #F0E9F5);
  stop-opacity: 0;
}

.awehjacnx {
  stop-color: var(--svg-color--ded7e4, #DED7E4);
}

.bek4ghb0w {
  d: path("M17.017 7h.003v4h-2V7.007c.594-.413 1.516-.382 1.997-.007");
}

.bwi8tgn0u {
  stop-color: var(--svg-color--544d5c, #544D5C);
}

.ccop9ib7d {
  stop-color: var(--svg-color--a29fa5, #A29FA5);
}

.ciz7q9d2j {
  stop-color: var(--svg-color--ffca56, #FFCA56);
}

.clvaovrzg {
  d: path("M19.02 3h-6c-1.1 0-2 .9-2 2s.9 2 2 2h6c1.1 0 2-.9 2-2s-.9-2-2-2");
}

.cp-8_o_vi {
  d: path("M30.02 5h-28v2h28z");
}

.di0pbrc_x {
  stop-color: var(--svg-color--4169a1, #4169A1);
}

.fg1-dxbrx {
  d: path("M15.024 9.23c-.637.335-1.004 1.004-1.004 1.77h4c0-.766-.363-1.435-1-1.77z");
}

.ft5dv1b6b {
  fill: none;
}

.g223hhx9k {
  stop-color: var(--svg-color--6f6879, #6F6879);
}

.g32tbkeva {
  stop-color: var(--svg-color--6c6770, #6C6770);
}

.gds77obnh {
  stop-color: var(--svg-color--00a6ed, #00A6ED);
}

.ge-asxv_k {
  d: path("M18.918 14h-3.796c-.611 0-1.102.49-1.102 1.1v5.8c0 .61.49 1.1 1.102 1.1h3.796c.611 0 1.102-.49 1.102-1.1v-5.8c0-.6-.49-1.1-1.102-1.1");
}

.gi-s0xm_l {
  stop-color: var(--svg-color--b4934e, #B4934E);
  stop-opacity: 0;
}

.gkaxbebhv {
  stop-color: var(--svg-color--ffb45d, #FFB45D);
}

.hfv13198d {
  stop-color: var(--svg-color--dfd4e6, #DFD4E6);
}

.hghvyqyng {
  stop-color: var(--svg-color--837f87, #837F87);
}

.ihg21322o {
  stop-color: var(--svg-color--817d85, #817D85);
}

.jlajlkb6g {
  d: path("M2.02 24h8.899c.61 0 1.101-.49 1.101-1.1v-7.8c0-.61-.49-1.1-1.101-1.1H2.02z");
}

.jv6p1eb5t {
  stop-color: var(--svg-color--6f6879, #6F6879);
  stop-opacity: 0;
}

.k5u7lbcal {
  stop-color: var(--svg-color--79def8, #79DEF8);
}

.m4vxu3qez {
  stop-color: var(--svg-color--5ef0ff, #5EF0FF);
}

.ob2927byv {
  stop-color: var(--svg-color--626263, #626263);
}

.ovs_5abkg {
  stop-color: var(--svg-color--f0e9f5, #F0E9F5);
}

.p2bz6xaok {
  stop-color: var(--svg-color--c8c1cd, #C8C1CD);
}

.pj2i25v0y {
  stop-color: var(--svg-color--56d6ff, #56D6FF);
}

.pumcc_aja {
  stop-color: var(--svg-color--4169a1, #4169A1);
  stop-opacity: 0;
}

.pv9rmh2eg {
  d: path("M30.02 4h-28v1h28z");
}

.q5rgccb4p {
  stop-color: var(--svg-color--d4d2d5, #D4D2D5);
}

.qfllb7hun {
  d: path("M30.02 16v-2.224c0-.978-.8-1.776-1.78-1.776H3.82c-.99 0-1.8.808-1.8 1.796v2.194h28z");
}

.qgrd4ybtf {
  stop-color: var(--svg-color--69666e, #69666E);
}

.qjbnq53mx {
  stop-color: var(--svg-color--a8a7aa, #A8A7AA);
}

.re9um8bmb {
  stop-color: var(--svg-color--69666e, #69666E);
  stop-opacity: 0;
}

.rjrf3rbph {
  stop-color: var(--svg-color--b4934e, #B4934E);
}

.s53ynhzyr {
  stop-color: var(--svg-color--adabae, #ADABAE);
}

.sm1teyw2a {
  stop-color: var(--svg-color--635994, #635994);
}

.sqkpcmbna {
  stop-color: var(--svg-color--919091, #919091);
}

.t1emytk5a {
  stop-color: var(--svg-color--706c75, #706C75);
}

.t77dcut_r {
  stop-color: var(--svg-color--51c9ff, #51C9FF);
}

.taue81kbj {
  stop-color: var(--svg-color--eee2f5, #EEE2F5);
}

.tzjyfabxq {
  d: path("M26.918 14h-3.796c-.611 0-1.102.49-1.102 1.1v5.8c0 .61.49 1.1 1.102 1.1h3.796c.611 0 1.102-.49 1.102-1.1v-5.8c0-.6-.49-1.1-1.102-1.1");
}

.u8in69b8w {
  d: path("M2.04 25h.01c.06.72.27 1.39.59 2h27.4v-2z");
}

.uwu0mxa-j {
  stop-color: var(--svg-color--d4d2d5, #D4D2D5);
  stop-opacity: 0;
}

.v2ysev_pr {
  d: path("M20.43 11h-8.82c-.33 0-.59.27-.59.59V12h10v-.41c0-.32-.27-.59-.59-.59");
}

.v2zdd5jwa {
  stop-color: var(--svg-color--d8d5e2, #D8D5E2);
}

.v3jx2d1bw {
  stop-color: var(--svg-color--ffa053, #FFA053);
}

.v5mkgpb0m {
  stop-color: var(--svg-color--f0edf7, #F0EDF7);
}

.vbo5qbcfz {
  d: path("M30.02 7h-28v1h28z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vkh_zubet {
  stop-color: var(--svg-color--c0fffe, #C0FFFE);
}

.vo0ul_xjo {
  stop-color: var(--svg-color--9194a3, #9194A3);
}

.vt206obwd {
  d: path("M30.02 13.78c0-.98-.8-1.78-1.78-1.78H3.83c-.99 0-1.8.81-1.8 1.8V18h-.01v6.5c0 .1 0 .2.01.3l.01.2a5.515 5.515 0 0 0 5.232 4.99c.05 0 .09.01.14.01h20.927c.93 0 1.681-.81 1.681-1.8z");
}

.wbnzwtozk {
  stop-color: var(--svg-color--918996, #918996);
  stop-opacity: 0;
}

.x1e1hp_8q {
  stop-color: var(--svg-color--918996, #918996);
}

.y6vyhk1ok {
  stop-color: var(--svg-color--544d5c, #544D5C);
  stop-opacity: 0;
}

.ykq--y_8h {
  stop-color: var(--svg-color--8d65c5, #8D65C5);
}

.z_3m-0bbd {
  stop-color: var(--svg-color--ffb45d, #FFB45D);
  stop-opacity: 0;
}

.zasaeub2s {
  stop-color: var(--svg-color--6bffff, #6BFFFF);
}

.zokric68q {
  fill: var(--svg-color--518fe8, #518FE8);
  d: path("M30.02 16v-2.224c0-.978-.8-1.776-1.78-1.776H3.82c-.99 0-1.8.808-1.8 1.796v2.194h28z");
}

</style>
