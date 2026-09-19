<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ffhtaigop"/><path fill="url(#ionLt1f)" class="dp9057bwr"/><path fill="url(#iNM1j4b)" class="dp9057bwr"/><g filter="url(#iuUObwv)"><path class="g97jm1wle"/><path fill="url(#iWndVkd)" class="r6qm_2b8l"/><path fill="url(#itLEHeb)" class="r6qm_2b8l"/></g><path class="tfkwpo5gc"/><path fill="url(#iG3LuSb)" class="glrwudb-b"/><path fill="url(#iTfZIlS)" class="glrwudb-b"/><g filter="url(#iLK8RJb)"><path class="mf6mvwb3t"/><path fill="url(#is3b2Ub)" class="bky-hdcgx"/><path fill="url(#i83ZjNN)" class="bky-hdcgx"/><path fill="url(#ivswZie)" class="bky-hdcgx"/><path fill="url(#iJvGkGc)" class="bky-hdcgx"/></g><path stroke="url(#iCW3Mvl)" class="r5d-fi_ni"/><path stroke="url(#iBMseNb)" class="s-n2urbtg"/><path stroke="url(#iSTsvIb)" class="w7a9xeygf"/><path stroke="url(#ixRVzJc)" class="w7a9xeygf"/><path class="on7epmbpd"/><path fill="url(#iTIbXOd)" class="o4-c11beo"/><g filter="url(#ipZLbeG)"><path class="r57zhhy8a"/><path fill="url(#ijvJPXj)" class="q9rpylqcb"/><path fill="url(#iirr89B)" class="q9rpylqcb"/><path fill="url(#icwZt6b)" class="q9rpylqcb"/><path fill="url(#iliqkIe)" class="q9rpylqcb"/></g><path class="g0687rbhu"/><path fill="url(#iyS46rI)" class="ljd2g1oiw"/><path fill="url(#irvV7Ed)" class="ljd2g1oiw"/><defs><linearGradient id="ionLt1f" x1="11.486" x2="29.982" y1="4.625" y2="2.938" gradientUnits="userSpaceOnUse"><stop class="d0o17gbjo"/><stop offset=".246" class="iww8uqh_g"/><stop offset=".707" class="rvwaysbyf"/><stop offset="1" class="qai962ack"/></linearGradient><linearGradient id="iNM1j4b" x1="22.328" x2="22.266" y1="5.219" y2="4.266" gradientUnits="userSpaceOnUse"><stop offset=".178" class="pyy_70zlg"/><stop offset="1" class="mu44_vb1o"/></linearGradient><linearGradient id="iWndVkd" x1="11.826" x2="29.5" y1="4.875" y2="3.25" gradientUnits="userSpaceOnUse"><stop offset=".062" class="hlae_ebud"/><stop offset=".154" class="wlzc1o45e"/><stop offset=".281" class="te-1lacis"/><stop offset=".971" class="n7p36ejfd"/><stop offset="1" class="eojf8ybwf"/></linearGradient><linearGradient id="itLEHeb" x1="12.531" x2="13.773" y1="4.867" y2="4.82" gradientUnits="userSpaceOnUse"><stop offset=".062" class="r32btp4cf"/><stop offset=".256" class="c2b_b7uia"/><stop offset=".601" class="jie-sdbfg"/><stop offset="1" class="xy8og6bno"/></linearGradient><linearGradient id="iG3LuSb" x1="11.489" x2="29.945" y1="9.267" y2="7.303" gradientUnits="userSpaceOnUse"><stop class="d0o17gbjo"/><stop offset=".246" class="iww8uqh_g"/><stop offset=".707" class="rvwaysbyf"/><stop offset="1" class="qai962ack"/></linearGradient><linearGradient id="iTfZIlS" x1="22.219" x2="22.342" y1="9.813" y2="8.346" gradientUnits="userSpaceOnUse"><stop offset=".178" class="kpsd_yb7k"/><stop offset="1" class="mu44_vb1o"/></linearGradient><linearGradient id="is3b2Ub" x1="12.188" x2="29.107" y1="8.446" y2="7.896" gradientUnits="userSpaceOnUse"><stop offset=".062" class="hlae_ebud"/><stop offset=".154" class="wlzc1o45e"/><stop offset=".281" class="te-1lacis"/><stop offset=".991" class="n7p36ejfd"/><stop offset="1" class="eojf8ybwf"/></linearGradient><linearGradient id="i83ZjNN" x1="12.523" x2="13.656" y1="9.297" y2="9.313" gradientUnits="userSpaceOnUse"><stop offset=".062" class="r32btp4cf"/><stop offset=".256" class="c2b_b7uia"/><stop offset=".601" class="jie-sdbfg"/><stop offset="1" class="xy8og6bno"/></linearGradient><linearGradient id="ivswZie" x1="14.563" x2="15.406" y1="9.297" y2="9.301" gradientUnits="userSpaceOnUse"><stop offset=".062" class="r32btp4cf"/><stop offset=".256" class="clmzk-byq"/><stop offset=".601" class="dldczjbit"/><stop offset="1" class="xy8og6bno"/></linearGradient><linearGradient id="iJvGkGc" x1="16.563" x2="17.266" y1="9.297" y2="9.319" gradientUnits="userSpaceOnUse"><stop offset=".062" class="r32btp4cf"/><stop offset=".256" class="clmzk-byq"/><stop offset=".601" class="dldczjbit"/><stop offset="1" class="xy8og6bno"/></linearGradient><linearGradient id="iCW3Mvl" x1="12.938" x2="14.703" y1="9.313" y2="9.313" gradientUnits="userSpaceOnUse"><stop class="h2txlxb4n"/><stop offset=".251" class="ygc9nnbrb"/><stop offset=".496" class="j8za2e5lh"/><stop offset=".708" class="dyjd4l21l"/></linearGradient><linearGradient id="iBMseNb" x1="14.918" x2="16.683" y1="11.449" y2="11.449" gradientUnits="userSpaceOnUse"><stop class="h2txlxb4n"/><stop offset=".251" class="ygc9nnbrb"/><stop offset=".496" class="j8za2e5lh"/><stop offset=".708" class="dyjd4l21l"/></linearGradient><linearGradient id="iSTsvIb" x1="16.948" x2="18.713" y1="9.519" y2="9.519" gradientUnits="userSpaceOnUse"><stop class="h2txlxb4n"/><stop offset=".251" class="ygc9nnbrb"/><stop offset=".496" class="j8za2e5lh"/><stop offset=".708" class="dyjd4l21l"/></linearGradient><linearGradient id="iirr89B" x1="15.969" x2="15.969" y1="16" y2="17.063" gradientUnits="userSpaceOnUse"><stop class="czt6ptv1l"/><stop offset="1" class="nhzbpobqt"/></linearGradient><linearGradient id="icwZt6b" x1="4.029" x2="17.029" y1="17.75" y2="17.75" gradientUnits="userSpaceOnUse"><stop class="wfsmyoecn"/><stop offset=".553" class="lmddz1b4p"/><stop offset="1" class="spfcye07m"/></linearGradient><linearGradient id="irvV7Ed" x1="15.969" x2="15.969" y1="28.875" y2="29.875" gradientUnits="userSpaceOnUse"><stop class="g3_gcacha"/><stop offset="1" class="v-ime2b5s"/></linearGradient><radialGradient id="ixRVzJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.8125 -3.2793 0 17.53 8.656)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="ze9flnb9r"/><stop offset=".817" class="kvdnw-rmh"/></radialGradient><radialGradient id="iTIbXOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 16 -17.92 0 23.654 16.125)" gradientUnits="userSpaceOnUse"><stop class="l58vs7bhz"/><stop offset=".59" class="rhp62vm4y"/><stop offset=".957" class="n_yikgbaw"/></radialGradient><radialGradient id="ijvJPXj" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.3043 -17.92 0 23.654 16.393)" gradientUnits="userSpaceOnUse"><stop class="l58vs7bhz"/><stop offset=".59" class="rhp62vm4y"/><stop offset=".957" class="n_yikgbaw"/></radialGradient><radialGradient id="iliqkIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.25 -12.5 0 21 18.313)" gradientUnits="userSpaceOnUse"><stop class="fvgqy5bqy"/><stop offset="1" class="ahv-hrb6h"/></radialGradient><radialGradient id="iyS46rI" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -11.7219 0 20.438 27.5)" gradientUnits="userSpaceOnUse"><stop class="fd3pmzblt"/><stop offset=".663" class="imy_wrohr"/><stop offset=".898" class="aejut0z8d"/></radialGradient><filter id="iuUObwv" width="18.975" height="3.84" x="11.24" y="1.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28242" stdDeviation=".2"/></filter><filter id="iLK8RJb" width="18.79" height="3.348" x="11.426" y="6.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28242" stdDeviation=".25"/></filter><filter id="ipZLbeG" width="23.662" height="11.382" x="4.15" y="15.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28242" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:steaming-bowl" /></template>
<style>
.aejut0z8d {
  stop-color: var(--svg-color--ce274c, #CE274C);
  stop-opacity: 0;
}

.ahv-hrb6h {
  stop-color: var(--svg-color--f8497f, #F8497F);
  stop-opacity: 0;
}

.bky-hdcgx {
  d: path("M28.872 7.622L12.8 7.272c-.467-.019-.853.156-.872.623c-.02.457.414.545.872.574l16.045 1.14c.476.038.814-.021.833-.497l.038-.791c.02-.477-.366-.69-.843-.699");
}

.c2b_b7uia {
  stop-color: var(--svg-color--bb885b, #BB885B);
}

.clmzk-byq {
  stop-color: var(--svg-color--cb8350, #CB8350);
}

.czt6ptv1l {
  stop-color: var(--svg-color--ff568d, #FF568D);
}

.d0o17gbjo {
  stop-color: var(--svg-color--b18c66, #B18C66);
}

.dldczjbit {
  stop-color: var(--svg-color--ca814e, #CA814E);
}

.dp9057bwr {
  d: path("m28.93 2.005l-16.64 1.69c-.48.05-.84.48-.8.96c.04.49.46.85.94.82l16.7-.86a.9.9 0 0 0 .85-.96l-.07-.83a.894.894 0 0 0-.98-.82");
}

.dyjd4l21l {
  stop-color: var(--svg-color--e8b83e, #E8B83E);
}

.eojf8ybwf {
  stop-color: var(--svg-color--f5bb84, #F5BB84);
}

.fd3pmzblt {
  stop-color: var(--svg-color--ff5587, #FF5587);
}

.ffhtaigop {
  fill: var(--svg-color--e3af81, #E3AF81);
  d: path("m28.93 2.005l-16.64 1.69c-.48.05-.84.48-.8.96c.04.49.46.85.94.82l16.7-.86a.9.9 0 0 0 .85-.96l-.07-.83a.894.894 0 0 0-.98-.82");
}

.ft5dv1b6b {
  fill: none;
}

.fvgqy5bqy {
  stop-color: var(--svg-color--fa4a81, #FA4A81);
}

.g0687rbhu {
  fill: var(--svg-color--a8323d, #A8323D);
  d: path("M22.61 26.375H9.421l-.673 2.662c-.16.423.27.838.88.838h12.68c.6 0 1.04-.415.88-.838z");
}

.g3_gcacha {
  stop-color: var(--svg-color--cd215a, #CD215A);
  stop-opacity: 0;
}

.g97jm1wle {
  fill: var(--svg-color--e3af81, #E3AF81);
  d: path("M28.844 2.203L12.533 3.841c-.455.047-.929.342-.891.797s.544.625.999.596l16.328-.906c.474-.028.881-.338.843-.812l-.078-.657c-.038-.474-.416-.703-.89-.656");
}

.glrwudb-b {
  d: path("m29.12 7.384l-16.71-.37c-.49-.02-.9.36-.92.85c-.02.48.35.9.83.93L29 9.994c.5.04.94-.35.96-.85l.04-.83c.02-.5-.38-.92-.88-.93");
}

.h2txlxb4n {
  stop-color: var(--svg-color--ba8c3d, #BA8C3D);
}

.hlae_ebud {
  stop-color: var(--svg-color--d1a581, #D1A581);
}

.imy_wrohr {
  stop-color: var(--svg-color--ca2548, #CA2548);
}

.iww8uqh_g {
  stop-color: var(--svg-color--d8ac7d, #D8AC7D);
}

.j8za2e5lh {
  stop-color: var(--svg-color--ffd851, #FFD851);
}

.jie-sdbfg {
  stop-color: var(--svg-color--bc885a, #BC885A);
}

.kpsd_yb7k {
  stop-color: var(--svg-color--c45a46, #C45A46);
}

.kvdnw-rmh {
  stop-color: var(--svg-color--dd6219, #DD6219);
}

.l58vs7bhz {
  stop-color: var(--svg-color--fc4982, #FC4982);
}

.ljd2g1oiw {
  d: path("M22.61 26.375H9.421l-.673 2.662c-.16.423.27.838.88.838h12.68c.6 0 1.04-.415.88-.838z");
}

.lmddz1b4p {
  stop-color: var(--svg-color--cb2664, #CB2664);
}

.mf6mvwb3t {
  fill: var(--svg-color--e3af81, #E3AF81);
  d: path("M28.872 7.622L12.8 7.272c-.467-.019-.853.156-.872.623c-.02.457.414.545.872.574l16.045 1.14c.476.038.814-.021.833-.497l.038-.791c.02-.477-.366-.69-.843-.699");
}

.mu44_vb1o {
  stop-color: var(--svg-color--be7a5c, #BE7A5C);
  stop-opacity: 0;
}

.n_yikgbaw {
  stop-color: var(--svg-color--bb244e, #BB244E);
  stop-opacity: 0;
}

.n7p36ejfd {
  stop-color: var(--svg-color--e0a97b, #E0A97B);
}

.nhzbpobqt {
  stop-color: var(--svg-color--ff578e, #FF578E);
  stop-opacity: 0;
}

.o4-c11beo {
  d: path("M18.75 27.215h-5.58c-5.05 0-9.14-4.1-9.14-9.15v-1.66c0-.38.31-.69.69-.69h22.5c.38 0 .69.31.69.69v1.66c-.01 5.05-4.1 9.15-9.16 9.15");
}

.on7epmbpd {
  fill: var(--svg-color--b72751, #B72751);
  d: path("M18.75 27.215h-5.58c-5.05 0-9.14-4.1-9.14-9.15v-1.66c0-.38.31-.69.69-.69h22.5c.38 0 .69.31.69.69v1.66c-.01 5.05-4.1 9.15-9.16 9.15");
}

.pyy_70zlg {
  stop-color: var(--svg-color--bb7351, #BB7351);
}

.q9rpylqcb {
  d: path("M18.75 26.883h-5.463c-5.05 0-8.883-3.805-8.883-8.635V16.66c0-.363-.065-.66.315-.66h22.5c.38 0 .341.297.341.66v1.588c-.01 4.83-3.75 8.635-8.81 8.635");
}

.qai962ack {
  stop-color: var(--svg-color--db9e69, #DB9E69);
}

.r32btp4cf {
  stop-color: var(--svg-color--bb895c, #BB895C);
  stop-opacity: 0;
}

.r57zhhy8a {
  fill: var(--svg-color--b72751, #B72751);
  d: path("M18.75 26.883h-5.463c-5.05 0-8.883-3.805-8.883-8.635V16.66c0-.363-.065-.66.315-.66h22.5c.38 0 .341.297.341.66v1.588c-.01 4.83-3.75 8.635-8.81 8.635");
}

.r5d-fi_ni {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M13.52 3.834v14.53");
}

.r6qm_2b8l {
  d: path("M28.844 2.203L12.533 3.841c-.455.047-.929.342-.891.797s.544.625.999.596l16.328-.906c.474-.028.881-.338.843-.812l-.078-.657c-.038-.474-.416-.703-.89-.656");
}

.rhp62vm4y {
  stop-color: var(--svg-color--d72654, #D72654);
}

.rvwaysbyf {
  stop-color: var(--svg-color--d5a370, #D5A370);
}

.s-n2urbtg {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M15.5 7.125v11.47");
}

.spfcye07m {
  stop-color: var(--svg-color--e23874, #E23874);
  stop-opacity: 0;
}

.te-1lacis {
  stop-color: var(--svg-color--e4b184, #E4B184);
}

.tfkwpo5gc {
  fill: var(--svg-color--e3af81, #E3AF81);
  d: path("m29.12 7.384l-16.71-.37c-.49-.02-.9.36-.92.85c-.02.48.35.9.83.93L29 9.994c.5.04.94-.35.96-.85l.04-.83c.02-.5-.38-.92-.88-.93");
}

.v-ime2b5s {
  stop-color: var(--svg-color--bd2a56, #BD2A56);
}

.w7a9xeygf {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M17.53 7.125v6.35");
}

.wfsmyoecn {
  stop-color: var(--svg-color--a93e5b, #A93E5B);
}

.wlzc1o45e {
  stop-color: var(--svg-color--fac28a, #FAC28A);
}

.xy8og6bno {
  stop-color: var(--svg-color--bc8759, #BC8759);
  stop-opacity: 0;
}

.ygc9nnbrb {
  stop-color: var(--svg-color--deb030, #DEB030);
}

.ze9flnb9r {
  stop-color: var(--svg-color--db5d1b, #DB5D1B);
  stop-opacity: 0;
}

</style>
