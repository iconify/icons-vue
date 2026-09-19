<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iswbbkd)"><path class="n3hyqnbvk"/><path fill="url(#iNACced)" class="g0l6--bur"/></g><path fill="url(#injfZlK)" class="g0l6--bur"/><rect transform="rotate(45 22.34 6.5)" class="rfp5ocu_r"/><rect fill="url(#iALGQbs)" transform="rotate(45 22.34 6.5)" class="x_7sr0qhp"/><rect fill="url(#i5LlCpd)" transform="rotate(45 22.34 6.5)" class="x_7sr0qhp"/><rect fill="url(#iNx1htc)" transform="rotate(45 18.586 6.535)" class="v_2k-ubfy"/><rect fill="url(#iSJX9Ee)" transform="rotate(45 18.586 6.535)" class="v_2k-ubfy"/><rect fill="url(#i5cDzje)" transform="rotate(45 18.586 6.535)" class="v_2k-ubfy"/><rect fill="url(#i4lTP5c)" transform="rotate(45 18.586 6.535)" class="v_2k-ubfy"/><rect fill="url(#iXy04yb)" transform="rotate(45 18.586 6.535)" class="v_2k-ubfy"/><path class="lcx68xe7l"/><path fill="url(#ifhgqFb)" transform="rotate(45 7.098 21.773)" class="oz3opob6d"/><path fill="url(#iKK3lRq)" transform="rotate(45 7.098 21.773)" class="oz3opob6d"/><path fill="url(#i7oxlwv)" transform="rotate(45 7.098 21.773)" class="oz3opob6d"/><path fill="url(#iU8YPzi)" class="thbkcq3iq"/><path fill="url(#iWWqXOb)" class="thbkcq3iq"/><path fill="url(#iB9UsHd)" class="thbkcq3iq"/><path fill="url(#ipLrruF)" class="thbkcq3iq"/><path fill="url(#iSmXauP)" class="thbkcq3iq"/><path fill="url(#iGBr7yb)" class="fqhh-wbgt"/><path fill="url(#ixr9p5b)" class="j-zq6oooo"/><path fill="url(#iqknEqe)" class="qwajkbc7c"/><path fill="url(#ibK0l2c)" class="n-n665xen"/><path fill="url(#i8VDs7H)" class="n-n665xen"/><path fill="url(#iVkhYFb)" class="n-n665xen"/><path fill="url(#iHloMad)" class="n-n665xen"/><path fill="url(#iFb22Ad)" class="n-n665xen"/><defs><linearGradient id="iNACced" x1="25.715" x2="25.199" y1="7.094" y2="6.609" gradientUnits="userSpaceOnUse"><stop offset=".192" class="sddcq7qzv"/><stop offset="1" class="vzol4pchq"/></linearGradient><linearGradient id="injfZlK" x1="29.371" x2="29.225" y1="2.336" y2="2.482" gradientUnits="userSpaceOnUse"><stop offset=".139" class="p2rqg_j5y"/><stop offset="1" class="ditxxcb1u"/></linearGradient><linearGradient id="iNx1htc" x1="18.255" x2="28.331" y1="18.749" y2="18.926" gradientUnits="userSpaceOnUse"><stop class="yro_39bmf"/><stop offset="1" class="rerdu-biw"/></linearGradient><linearGradient id="iSJX9Ee" x1="28.463" x2="25.282" y1="16.053" y2="15.965" gradientUnits="userSpaceOnUse"><stop offset=".132" class="to79ffb-y"/><stop offset="1" class="ome4t5bzc"/></linearGradient><linearGradient id="i5cDzje" x1="17.967" x2="19.558" y1="16.297" y2="16.297" gradientUnits="userSpaceOnUse"><stop offset=".397" class="b-w64ozpi"/><stop offset="1" class="ju1zrjgga"/></linearGradient><linearGradient id="iKK3lRq" x1="6.302" x2="8.153" y1="24.834" y2="25.005" gradientUnits="userSpaceOnUse"><stop class="c0m1v-g_m"/><stop offset="1" class="ex6or0b7v"/></linearGradient><linearGradient id="i7oxlwv" x1="10.07" x2="10.07" y1="26.215" y2="25.375" gradientUnits="userSpaceOnUse"><stop class="xh36w-bor"/><stop offset="1" class="rya9dm7nl"/></linearGradient><linearGradient id="iU8YPzi" x1="2.759" x2="7.813" y1="25.342" y2="25.355" gradientUnits="userSpaceOnUse"><stop class="tk3uc0a2z"/><stop offset="1" class="e_jpm7qbw"/></linearGradient><linearGradient id="iWWqXOb" x1="5.746" x2="6.293" y1="28.375" y2="27.719" gradientUnits="userSpaceOnUse"><stop offset=".137" class="z7w65kbjz"/><stop offset="1" class="dfj8-h4uj"/></linearGradient><linearGradient id="iB9UsHd" x1="6.309" x2="5.676" y1="25.906" y2="26.563" gradientUnits="userSpaceOnUse"><stop offset=".137" class="tdgqgcb0d"/><stop offset="1" class="t3qyrc6lv"/></linearGradient><linearGradient id="ipLrruF" x1="2.09" x2="3.215" y1="24.75" y2="24.281" gradientUnits="userSpaceOnUse"><stop class="d5qv0p46o"/><stop offset="1" class="jzdkv9tpx"/></linearGradient><linearGradient id="iGBr7yb" x1="16.027" x2="17.637" y1="9.125" y2="10.75" gradientUnits="userSpaceOnUse"><stop class="rehlohbgy"/><stop offset="1" class="pb7m8cxts"/></linearGradient><linearGradient id="ixr9p5b" x1="14.135" x2="15.733" y1="11.01" y2="12.623" gradientUnits="userSpaceOnUse"><stop class="rehlohbgy"/><stop offset="1" class="pb7m8cxts"/></linearGradient><linearGradient id="iqknEqe" x1="12.25" x2="13.86" y1="12.902" y2="14.527" gradientUnits="userSpaceOnUse"><stop class="rehlohbgy"/><stop offset="1" class="pb7m8cxts"/></linearGradient><linearGradient id="ibK0l2c" x1="4.008" x2="13.441" y1="20.968" y2="20.994" gradientUnits="userSpaceOnUse"><stop class="tk3uc0a2z"/><stop offset="1" class="e_jpm7qbw"/></linearGradient><linearGradient id="i8VDs7H" x1="9.584" x2="10.434" y1="26.629" y2="25.688" gradientUnits="userSpaceOnUse"><stop offset=".243" class="z7w65kbjz"/><stop offset="1" class="dfj8-h4uj"/></linearGradient><linearGradient id="iVkhYFb" x1="10.633" x2="9.452" y1="22.021" y2="23.246" gradientUnits="userSpaceOnUse"><stop offset=".137" class="rt7-3vvcg"/><stop offset="1" class="uwn_-jiwd"/></linearGradient><linearGradient id="iHloMad" x1="2.76" x2="4.86" y1="19.864" y2="18.989" gradientUnits="userSpaceOnUse"><stop class="d5qv0p46o"/><stop offset="1" class="jzdkv9tpx"/></linearGradient><radialGradient id="iALGQbs" cx="0" cy="0" r="1" gradientTransform="matrix(.07458 2.88644 -2.44978 .0633 24.417 6.81)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="arhtgufuy"/><stop offset="1" class="f_x_ad2cl"/></radialGradient><radialGradient id="i5LlCpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .53033 -2.94501 0 24.528 6.699)" gradientUnits="userSpaceOnUse"><stop class="f9l259bxh"/><stop offset="1" class="emg76xbvm"/></radialGradient><radialGradient id="i4lTP5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.12695 -4.93041 0 23.381 7.016)" gradientUnits="userSpaceOnUse"><stop class="gqoyw4bfs"/><stop offset="1" class="i77e6nsnq"/></radialGradient><radialGradient id="iXy04yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5026 5.51141 0 23.248 24.627)" gradientUnits="userSpaceOnUse"><stop class="rzdw3ab9e"/><stop offset="1" class="w6_32bc7e"/></radialGradient><radialGradient id="ifhgqFb" cx="0" cy="0" r="1" gradientTransform="rotate(179.703 5.662 11.592)scale(4.2648 3.80133)" gradientUnits="userSpaceOnUse"><stop class="rrxqnbbsm"/><stop offset="1" class="a0ip0mwjs"/></radialGradient><radialGradient id="iSmXauP" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .20313 -1.45178 -1.45173 5.809 26.906)" gradientUnits="userSpaceOnUse"><stop class="f9q3g2btb"/><stop offset="1" class="td0l54b4s"/></radialGradient><radialGradient id="iFb22Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-.7375 .73541 -4.62165 -4.63474 10.059 23.531)" gradientUnits="userSpaceOnUse"><stop class="uxg7lub1o"/><stop offset="1" class="ctpcdkb9i"/></radialGradient><filter id="iswbbkd" width="7.02" height="6.655" x="22.875" y="2.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".45" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.545098 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25245"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:syringe" /></template>
<style>
.a0ip0mwjs {
  stop-color: var(--svg-color--7b5eab, #7B5EAB);
  stop-opacity: 0;
}

.arhtgufuy {
  stop-color: var(--svg-color--b6c9e3, #B6C9E3);
  stop-opacity: 0;
}

.b-w64ozpi {
  stop-color: var(--svg-color--afbfc7, #AFBFC7);
}

.c0m1v-g_m {
  stop-color: var(--svg-color--9b9faa, #9B9FAA);
}

.ctpcdkb9i {
  stop-color: var(--svg-color--34b0ee, #34B0EE);
  stop-opacity: 0;
}

.d5qv0p46o {
  stop-color: var(--svg-color--87b4d9, #87B4D9);
}

.dfj8-h4uj {
  stop-color: var(--svg-color--4072d5, #4072D5);
  stop-opacity: 0;
}

.ditxxcb1u {
  stop-color: var(--svg-color--c6c3ca, #C6C3CA);
  stop-opacity: 0;
}

.e_jpm7qbw {
  stop-color: var(--svg-color--377fe1, #377FE1);
}

.emg76xbvm {
  stop-color: var(--svg-color--c4dae9, #C4DAE9);
  stop-opacity: 0;
}

.ex6or0b7v {
  stop-color: var(--svg-color--9b9faa, #9B9FAA);
  stop-opacity: 0;
}

.f_x_ad2cl {
  stop-color: var(--svg-color--9dadbf, #9DADBF);
}

.f9l259bxh {
  stop-color: var(--svg-color--e0f5ff, #E0F5FF);
}

.f9q3g2btb {
  stop-color: var(--svg-color--5ca7f1, #5CA7F1);
}

.fqhh-wbgt {
  d: path("m15.555 9.566l.945-.945l1.26 1.26a.5.5 0 0 1 0 .707l-.238.238a.5.5 0 0 1-.707 0z");
}

.ft5dv1b6b {
  fill: none;
}

.g0l6--bur {
  d: path("M29.233 2.277a.1.1 0 0 1 .075.027l.106.1a.1.1 0 0 1 .031.073v.117a.1.1 0 0 1-.026.067l-5.614 6.171l-.93-.93l6.188-5.593a.1.1 0 0 1 .061-.025z");
}

.gqoyw4bfs {
  stop-color: var(--svg-color--e4f5ff, #E4F5FF);
}

.i77e6nsnq {
  stop-color: var(--svg-color--cadfed, #CADFED);
  stop-opacity: 0;
}

.j-zq6oooo {
  d: path("m13.666 11.455l.945-.945l1.243 1.242a.5.5 0 0 1 0 .707l-.239.238a.5.5 0 0 1-.707 0z");
}

.ju1zrjgga {
  stop-color: var(--svg-color--afbfc7, #AFBFC7);
  stop-opacity: 0;
}

.jzdkv9tpx {
  stop-color: var(--svg-color--87b4d9, #87B4D9);
  stop-opacity: 0;
}

.lcx68xe7l {
  fill: var(--svg-color--9395a6, #9395A6);
  d: path("m7.098 21.773l2.836 2.836l-3.226 3.227L3.87 25z");
}

.n-n665xen {
  d: path("M4.459 18.783a1 1 0 0 1 1.414 0l7.05 7.051a1 1 0 0 1 0 1.414l-.46.461a1 1 0 0 1-1.414 0l-7.05-7.05a1 1 0 0 1 0-1.415z");
}

.n3hyqnbvk {
  fill: var(--svg-color--bfbac4, #BFBAC4);
  d: path("M29.233 2.277a.1.1 0 0 1 .075.027l.106.1a.1.1 0 0 1 .031.073v.117a.1.1 0 0 1-.026.067l-5.614 6.171l-.93-.93l6.188-5.593a.1.1 0 0 1 .061-.025z");
}

.ome4t5bzc {
  stop-color: var(--svg-color--c4cafd, #C4CAFD);
  stop-opacity: 0;
}

.oz3opob6d {
  d: path("M7.098 21.773h4.011v4.563H7.098z");
}

.p2rqg_j5y {
  stop-color: var(--svg-color--c6c3ca, #C6C3CA);
}

.pb7m8cxts {
  stop-color: var(--svg-color--326ccd, #326CCD);
}

.qwajkbc7c {
  d: path("m11.778 13.344l.945-.946l1.26 1.26a.5.5 0 0 1 0 .707l-.239.239a.5.5 0 0 1-.707 0z");
}

.rehlohbgy {
  stop-color: var(--svg-color--607db9, #607DB9);
}

.rerdu-biw {
  stop-color: var(--svg-color--c5c9ff, #C5C9FF);
}

.rfp5ocu_r {
  width: 4.055px;
  height: 6.143px;
  x: 22.34px;
  y: 6.5px;
  fill: var(--svg-color--c4d4f8, #C4D4F8);
  rx: 0.6px;
}

.rrxqnbbsm {
  stop-color: var(--svg-color--8064af, #8064AF);
}

.rt7-3vvcg {
  stop-color: var(--svg-color--4dbdfe, #4DBDFE);
}

.rya9dm7nl {
  stop-color: var(--svg-color--7c78a2, #7C78A2);
  stop-opacity: 0;
}

.rzdw3ab9e {
  stop-color: var(--svg-color--cce1ff, #CCE1FF);
}

.sddcq7qzv {
  stop-color: var(--svg-color--a39cad, #A39CAD);
}

.t3qyrc6lv {
  stop-color: var(--svg-color--3382bb, #3382BB);
  stop-opacity: 0;
}

.td0l54b4s {
  stop-color: var(--svg-color--5ca7f1, #5CA7F1);
  stop-opacity: 0;
}

.tdgqgcb0d {
  stop-color: var(--svg-color--3382bb, #3382BB);
}

.thbkcq3iq {
  d: path("M2.853 24.19a.6.6 0 0 1 .849 0l3.815 3.815a.6.6 0 0 1 0 .849l-.08.081a.6.6 0 0 1-.85 0L2.773 25.12a.6.6 0 0 1 0-.849z");
}

.tk3uc0a2z {
  stop-color: var(--svg-color--4b99d5, #4B99D5);
}

.to79ffb-y {
  stop-color: var(--svg-color--b6b4e7, #B6B4E7);
}

.uwn_-jiwd {
  stop-color: var(--svg-color--4dbdfe, #4DBDFE);
  stop-opacity: 0;
}

.uxg7lub1o {
  stop-color: var(--svg-color--6ec8ff, #6EC8FF);
}

.v_2k-ubfy {
  width: 9.314px;
  height: 19.981px;
  x: 18.586px;
  y: 6.535px;
  rx: 1.25px;
}

.vzol4pchq {
  stop-color: var(--svg-color--a39cad, #A39CAD);
  stop-opacity: 0;
}

.w6_32bc7e {
  stop-color: var(--svg-color--cce1ff, #CCE1FF);
  stop-opacity: 0;
}

.x_7sr0qhp {
  width: 4.055px;
  height: 6.143px;
  x: 22.34px;
  y: 6.5px;
  rx: 0.6px;
}

.xh36w-bor {
  stop-color: var(--svg-color--7c78a2, #7C78A2);
}

.yro_39bmf {
  stop-color: var(--svg-color--b7c9de, #B7C9DE);
}

.z7w65kbjz {
  stop-color: var(--svg-color--4072d5, #4072D5);
}

</style>
