<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="pwa5zfuki"/><path fill="url(#iQMrkvR)" class="m94avobjp"/><path fill="url(#i8turTY)" class="m94avobjp"/><path fill="url(#iCOBA0b)" class="m94avobjp"/><path fill="url(#ippzTLb)" class="m94avobjp"/><path fill="url(#i3tFMhb)" class="j3r04ebal"/><path fill="url(#izphtye)" class="j3r04ebal"/><path fill="url(#i76DKJc)" class="rj_tl4b9z"/><path class="mma8alg1t"/><path fill="url(#i505l6b)" class="qlhlr8b_e"/><path class="l42joobdb"/><path fill="url(#ia9Oc4m)" class="glmvb0aez"/><path fill="url(#iK5lTdd)" class="glmvb0aez"/><path fill="url(#iu1k92b)" class="glmvb0aez"/><path class="td3njubjv"/><path fill="url(#ic1F2Kx)" class="pblj7o2zv"/><path fill="url(#i06oquc)" class="pblj7o2zv"/><path fill="url(#ipDOi0c)" class="pblj7o2zv"/><path fill="url(#ic5yxcc)" class="grheocics"/><path class="tve5erbqo"/><path fill="url(#iH7c6tb)" class="p94i54bvd"/><path fill="url(#iY5SqGb)" class="p94i54bvd"/><path fill="url(#iKe41me)" class="p94i54bvd"/><defs><radialGradient id="iCOBA0b" cx="0" cy="0" r="1" gradientTransform="rotate(117.759 8.8 9.066)scale(.67097 1.01132)" gradientUnits="userSpaceOnUse"><stop class="gz_vvknev"/><stop offset="1" class="iok7gtbtv"/></radialGradient><radialGradient id="ippzTLb" cx="0" cy="0" r="1" gradientTransform="rotate(120.466 10.516 8.026)scale(.30817 2.03396)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="wq4gzsy4x"/></radialGradient><radialGradient id="i76DKJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 .8878 -1.80158 -.88782 21.188 5.622)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="k-6t3xoad"/><stop offset=".688" class="bqav5ecnr"/><stop offset="1" class="dcp9hl-qd"/></radialGradient><radialGradient id="i505l6b" cx="0" cy="0" r="1" gradientTransform="rotate(100.312 4.494 13.292)scale(13.044)" gradientUnits="userSpaceOnUse"><stop offset=".199" class="xzdagyb4i"/><stop offset=".603" class="rt46a9byz"/></radialGradient><radialGradient id="ia9Oc4m" cx="0" cy="0" r="1" gradientTransform="matrix(-8.75 16.8122 -16.82975 -8.75915 21.5 15.008)" gradientUnits="userSpaceOnUse"><stop class="viq0i2gxk"/><stop offset=".35" class="v2-u70stn"/><stop offset="1" class="uvbadlbvs"/></radialGradient><radialGradient id="iK5lTdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12502 12.25066 -23.5324 -4.08197 11.875 31.038)" gradientUnits="userSpaceOnUse"><stop class="a0s6x-bva"/><stop offset=".515" class="bza4cdbbo"/><stop offset="1" class="h4n0c-bcg"/></radialGradient><radialGradient id="ic1F2Kx" cx="0" cy="0" r="1" gradientTransform="rotate(118.486 6.1 14.21)scale(18.3461 18.799)" gradientUnits="userSpaceOnUse"><stop class="viq0i2gxk"/><stop offset=".35" class="v2-u70stn"/><stop offset="1" class="uvbadlbvs"/></radialGradient><radialGradient id="i06oquc" cx="0" cy="0" r="1" gradientTransform="rotate(100.251 -7.01 20.46)scale(11.9406 23.8533)" gradientUnits="userSpaceOnUse"><stop class="a0s6x-bva"/><stop offset=".515" class="bza4cdbbo"/><stop offset="1" class="h4n0c-bcg"/></radialGradient><radialGradient id="iH7c6tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.35671 -8.875 0 4.313 11.018)" gradientUnits="userSpaceOnUse"><stop class="xs6ay3b1j"/><stop offset="1" class="hduuc5yvr"/></radialGradient><radialGradient id="iKe41me" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75 -11.3125 0 23.313 10.625)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="b33o2ybwb"/></radialGradient><linearGradient id="iQMrkvR" x1="20.438" x2="21.453" y1="3.992" y2="4.406" gradientUnits="userSpaceOnUse"><stop class="clpfqccrx"/><stop offset="1" class="mh6dfjvkn"/></linearGradient><linearGradient id="i8turTY" x1="22.172" x2="21.422" y1="4.813" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="hx_04w-zb"/><stop offset=".184" class="xqdmcwben"/><stop offset=".531" class="j4t01-bhd"/><stop offset="1" class="y2uwj4qig"/></linearGradient><linearGradient id="i3tFMhb" x1="18.938" x2="20.484" y1="6.875" y2="7.75" gradientUnits="userSpaceOnUse"><stop class="j7csm5biv"/><stop offset=".521" class="y081ikbpt"/><stop offset=".793" class="ny29tkb0y"/><stop offset="1" class="wqjvhnbmx"/></linearGradient><linearGradient id="izphtye" x1="20.375" x2="20.141" y1="6" y2="6.391" gradientUnits="userSpaceOnUse"><stop class="ohcnrfbxt"/><stop offset="1" class="ej-r-bygy"/></linearGradient><linearGradient id="iu1k92b" x1="16.04" x2="16.04" y1="12.188" y2="13.625" gradientUnits="userSpaceOnUse"><stop class="ylzpl6btl"/><stop offset="1" class="nse2mcbeb"/></linearGradient><linearGradient id="ipDOi0c" x1="16.04" x2="16.04" y1="12.043" y2="13.625" gradientUnits="userSpaceOnUse"><stop class="ylzpl6btl"/><stop offset="1" class="nse2mcbeb"/></linearGradient><linearGradient id="ic5yxcc" x1="8.267" x2="27.306" y1="8.847" y2="14.886" gradientUnits="userSpaceOnUse"><stop class="h_j9u0wvt"/><stop offset=".994" class="kt__1405u"/></linearGradient><linearGradient id="iY5SqGb" x1="16.035" x2="16.035" y1="10.625" y2="12.043" gradientUnits="userSpaceOnUse"><stop class="g7-garb2y"/><stop offset="1" class="pc7l3cb8h"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mate" /></template>
<style>
.a0s6x-bva {
  stop-color: var(--svg-color--a26289, #A26289);
}

.b33o2ybwb {
  stop-color: var(--svg-color--dad8e2, #DAD8E2);
  stop-opacity: 0;
}

.bqav5ecnr {
  stop-color: var(--svg-color--dcae2b, #DCAE2B);
}

.bza4cdbbo {
  stop-color: var(--svg-color--9c5361, #9C5361);
}

.clpfqccrx {
  stop-color: var(--svg-color--999c9c, #999C9C);
}

.dcp9hl-qd {
  stop-color: var(--svg-color--bf9d62, #BF9D62);
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.ej-r-bygy {
  stop-color: var(--svg-color--939783, #939783);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g7-garb2y {
  stop-color: var(--svg-color--c9b8df, #C9B8DF);
  stop-opacity: 0;
}

.glmvb0aez {
  d: path("m26.47 15.483l.03.02s-.04-.08-.1-.21a8 8 0 0 0-.3-.75c-.31-.88-.6-2.1-.02-2.54c.95-.73-1.99-.72-1.99-.72l-.25.77H8.26l-.25-.78s-2.93 0-1.99.72c.57.44.27 1.62-.05 2.5c-.16.32-.3.65-.42.98c-.01.02-.01.03-.01.03h.01c-.36.96-.55 2.04-.55 3.57c0 6.1 4.94 11.04 11.04 11.04s11.04-4.94 11.04-11.04c.01-1.26-.23-2.47-.61-3.59");
}

.grheocics {
  d: path("M22.73 10.033H9.36c-.31 0-.6.15-.77.41l-1.11 1.6h17.14l-1.11-1.6a.95.95 0 0 0-.78-.41");
}

.gz_vvknev {
  stop-color: var(--svg-color--e4d7d1, #E4D7D1);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h4n0c-bcg {
  stop-color: var(--svg-color--9e5460, #9E5460);
  stop-opacity: 0;
}

.hduuc5yvr {
  stop-color: var(--svg-color--b0aeb6, #B0AEB6);
  stop-opacity: 0;
}

.hx_04w-zb {
  stop-color: var(--svg-color--b3b3b5, #B3B3B5);
}

.iok7gtbtv {
  stop-color: var(--svg-color--e3d6d3, #E3D6D3);
  stop-opacity: 0;
}

.j3r04ebal {
  d: path("m19.95 5.243l-5.27 9.13l1.3.75l5.27-9.13z");
}

.j4t01-bhd {
  stop-color: var(--svg-color--c4c4cd, #C4C4CD);
}

.j7csm5biv {
  stop-color: var(--svg-color--9ea39e, #9EA39E);
}

.k-6t3xoad {
  stop-color: var(--svg-color--ffd571, #FFD571);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l42joobdb {
  fill: var(--svg-color--7a5445, #7A5445);
  d: path("m26.47 15.483l.03.02s-.04-.08-.1-.21a8 8 0 0 0-.3-.75c-.31-.88-.6-2.1-.02-2.54c.95-.73-1.99-.72-1.99-.72l-.25.77H8.26l-.25-.78s-2.93 0-1.99.72c.57.44.27 1.62-.05 2.5c-.16.32-.3.65-.42.98c-.01.02-.01.03-.01.03h.01c-.36.96-.55 2.04-.55 3.57c0 6.1 4.94 11.04 11.04 11.04s11.04-4.94 11.04-11.04c.01-1.26-.23-2.47-.61-3.59");
}

.m94avobjp {
  d: path("m23.31 3.133l-1.91-1.1a.255.255 0 0 0-.37.15l-.8 2.66l-.25.43l1.23.71l.25-.43l1.9-2.02c.12-.13.09-.32-.05-.4");
}

.mh6dfjvkn {
  stop-color: var(--svg-color--acacb2, #ACACB2);
  stop-opacity: 0;
}

.mma8alg1t {
  fill: var(--svg-color--85c35e, #85C35E);
  d: path("M16.04 24.083a8.03 8.03 0 1 0 0-16.06a8.03 8.03 0 0 0 0 16.06");
}

.nse2mcbeb {
  stop-color: var(--svg-color--894f51, #894F51);
  stop-opacity: 0;
}

.ny29tkb0y {
  stop-color: var(--svg-color--ccd6cc, #CCD6CC);
}

.ohcnrfbxt {
  stop-color: var(--svg-color--959e8c, #959E8C);
}

.p94i54bvd {
  d: path("M26.02 12.043H6.05c-.55 0-1-.45-1-1v-.05c0-.55.45-1 1-1h19.97c.55 0 1 .45 1 1v.05c0 .55-.45 1-1 1");
}

.pblj7o2zv {
  d: path("m25.61 13.543l-1-1.5H6.05s.32.26.29.95c-.01.39-.2 1-.2 1c-.64 1.64-1.14 2.49-1.14 5.08c0 6.1 4.94 11.04 11.04 11.04s11.04-4.94 11.04-11.04c.01-2.02-.53-3.9-1.47-5.53");
}

.pc7l3cb8h {
  stop-color: var(--svg-color--a686b8, #A686B8);
}

.pwa5zfuki {
  fill: var(--svg-color--c0beca, #C0BECA);
  d: path("m23.31 3.133l-1.91-1.1a.255.255 0 0 0-.37.15l-.8 2.66l-.25.43l1.23.71l.25-.43l1.9-2.02c.12-.13.09-.32-.05-.4");
}

.qlhlr8b_e {
  d: path("M16.04 24.083a8.03 8.03 0 1 0 0-16.06a8.03 8.03 0 0 0 0 16.06");
}

.rj_tl4b9z {
  d: path("m21.01 6.443l-1.33-.77a.505.505 0 0 1 .51-.87l1.33.77c.24.14.32.45.18.69c-.14.23-.45.32-.69.18");
}

.rt46a9byz {
  stop-color: var(--svg-color--b2ff64, #B2FF64);
  stop-opacity: 0;
}

.td3njubjv {
  fill: var(--svg-color--7a5445, #7A5445);
  d: path("m25.61 13.543l-1-1.5H6.05s.32.26.29.95c-.01.39-.2 1-.2 1c-.64 1.64-1.14 2.49-1.14 5.08c0 6.1 4.94 11.04 11.04 11.04s11.04-4.94 11.04-11.04c.01-2.02-.53-3.9-1.47-5.53");
}

.tve5erbqo {
  fill: var(--svg-color--d0d0d6, #D0D0D6);
  d: path("M26.02 12.043H6.05c-.55 0-1-.45-1-1v-.05c0-.55.45-1 1-1h19.97c.55 0 1 .45 1 1v.05c0 .55-.45 1-1 1");
}

.uvbadlbvs {
  stop-color: var(--svg-color--ae6a57, #AE6A57);
  stop-opacity: 0;
}

.v2-u70stn {
  stop-color: var(--svg-color--b47159, #B47159);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.viq0i2gxk {
  stop-color: var(--svg-color--cb937a, #CB937A);
}

.wq4gzsy4x {
  stop-color: var(--svg-color--cccad4, #CCCAD4);
  stop-opacity: 0;
}

.wqjvhnbmx {
  stop-color: var(--svg-color--bbbfba, #BBBFBA);
}

.xqdmcwben {
  stop-color: var(--svg-color--c2c2c8, #C2C2C8);
}

.xs6ay3b1j {
  stop-color: var(--svg-color--9c9ba1, #9C9BA1);
}

.xzdagyb4i {
  stop-color: var(--svg-color--b4ff62, #B4FF62);
}

.y081ikbpt {
  stop-color: var(--svg-color--ced8ce, #CED8CE);
}

.y2uwj4qig {
  stop-color: var(--svg-color--c1c1c7, #C1C1C7);
  stop-opacity: 0;
}

.ylzpl6btl {
  stop-color: var(--svg-color--8a4e4b, #8A4E4B);
}

</style>
