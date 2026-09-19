<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ifrgsKc)" class="te5lusssm"/><path fill="url(#in2AbWd)" class="te5lusssm"/><path fill="url(#i92hSyb)" class="te5lusssm"/><path fill="url(#inlPNyb)" class="te5lusssm"/><path fill="url(#iUmOU4b)" class="te5lusssm"/><path fill="url(#i9J681c)" class="te5lusssm"/><path fill="url(#iEfL03d)" class="te5lusssm"/><path fill="url(#irGwbve)" class="ldbb5595h"/><path fill="url(#iuK4CXc)" class="ldbb5595h"/><path fill="url(#ijFA20c)" class="ldbb5595h"/><path fill="url(#inHD2Cc)" class="ldbb5595h"/><path fill="url(#iGELUWb)" class="ldbb5595h"/><path fill="url(#ixH4pBc)" class="ldbb5595h"/><path class="zhpnicbfs"/><path fill="url(#ifFoLEy)" class="m-egtj6lu"/><path fill="url(#iJam5Le)" class="m-egtj6lu"/><path fill="url(#iQDeaic)" class="m-egtj6lu"/><path fill="url(#ijbtH3d)" class="m-egtj6lu"/><path fill="url(#iZOH7ST)" class="m-egtj6lu"/><path fill="url(#id4xMRu)" class="m-egtj6lu"/><path fill="url(#i3gM8se)" class="m-egtj6lu"/><path fill="url(#iCgzZZd)" class="m-egtj6lu"/><path fill="url(#iie01Wd)" class="m-egtj6lu"/><path fill="url(#iujwahj)" class="m-egtj6lu"/><path clip-rule="evenodd" class="j0c2z9h3n"/><path fill="url(#irq8Xfd)" clip-rule="evenodd" class="mklo068xv"/><path clip-rule="evenodd" class="q6m37fbbg"/><path fill="url(#i8t4bzd)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#iY6GBKe)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#iAbYpMZ)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#iI7WEIb)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#irIEh2d)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#ivacV6d)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#iRfAief)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#iEx9xsl)" clip-rule="evenodd" class="quxrynbdt"/><path fill="url(#i7V05Kq)" clip-rule="evenodd" class="yqcytmbfv"/><path fill="url(#iHYbd2d)" clip-rule="evenodd" class="yqcytmbfv"/><path fill="url(#igJQHhc)" class="m-egtj6lu"/><path fill="url(#iO5HJSd)" class="m-egtj6lu"/><path fill="url(#iMhjFbe)" class="m-egtj6lu"/><path fill="url(#ijUEIQc)" class="m-egtj6lu"/><path fill="url(#iVNNjCd)" class="m-egtj6lu"/><path fill="url(#i0Xo5Xb)" class="m-egtj6lu"/><path fill="url(#ipTgFGb)" class="m-egtj6lu"/><path fill="url(#ioih0fe)" class="m-egtj6lu"/><path fill="url(#iICXWAn)" class="m-egtj6lu"/><path fill="url(#ieA8ZHE)" class="m-egtj6lu"/><path fill="url(#iv1Cwyd)" class="m-egtj6lu"/><path fill="url(#iyUDPNc)" class="m-egtj6lu"/><path fill="url(#iHq1N7c)" class="m-egtj6lu"/><path fill="url(#iVER9Je)" class="h7d5uv04b"/><path fill="url(#iPrYfpc)" class="h7d5uv04b"/><path fill="url(#iA8tq6b)" class="m-egtj6lu"/><path fill="url(#iTfpT7E)" clip-rule="evenodd" class="quxrynbdt"/><defs><radialGradient id="ifrgsKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45486 15.82406 -15.87814 -.45641 16.213 15.084)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="fubv-kbbk"/><stop offset=".859" class="fubv-kbbk"/><stop offset=".899" class="loikb719k"/><stop offset=".983" class="qzjs57bda"/></radialGradient><radialGradient id="in2AbWd" cx="0" cy="0" r="1" gradientTransform="rotate(94.236 -.093 15.577)scale(12.4951 12.5378)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="yb49kpbfn"/><stop offset=".916" class="wg0i3t8pb"/></radialGradient><radialGradient id="i92hSyb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.078 15.837)scale(13.3025)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="of0r7wq2o"/><stop offset=".867" class="r_52vrybx"/></radialGradient><radialGradient id="inlPNyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41006 -3.07726 0 27.158 23.738)" gradientUnits="userSpaceOnUse"><stop class="av6h53bro"/><stop offset=".8" class="sgjth1b6t"/></radialGradient><radialGradient id="iUmOU4b" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.078 15.837)scale(15.9852)" gradientUnits="userSpaceOnUse"><stop offset=".855" class="r_52vrybx"/><stop offset=".877" class="pw7f7obzx"/></radialGradient><radialGradient id="i9J681c" cx="0" cy="0" r="1" gradientTransform="rotate(98.493 1.863 15.785)scale(17.1822)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="r_52vrybx"/><stop offset=".919" class="pw7f7obzx"/></radialGradient><radialGradient id="iEfL03d" cx="0" cy="0" r="1" gradientTransform="rotate(93.996 .305 16.344)scale(11.7926)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="of0r7wq2o"/><stop offset=".867" class="r_52vrybx"/></radialGradient><radialGradient id="irGwbve" cx="0" cy="0" r="1" gradientTransform="rotate(-88.354 16.269 .498)scale(15.8306 15.8847)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="fubv-kbbk"/><stop offset=".859" class="fubv-kbbk"/><stop offset=".899" class="wk449o50m"/><stop offset=".983" class="qzjs57bda"/></radialGradient><radialGradient id="iuK4CXc" cx="0" cy="0" r="1" gradientTransform="rotate(-92.107 15.223 -.37)scale(12.4348 12.4774)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="loikb719k"/><stop offset=".892" class="b2g333vrx"/></radialGradient><radialGradient id="ijFA20c" cx="0" cy="0" r="1" gradientTransform="rotate(-90 15.837 .078)scale(13.3025)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="of0r7wq2o"/><stop offset=".867" class="r_52vrybx"/></radialGradient><radialGradient id="inHD2Cc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.673 15.839 .081)scale(15.9894)" gradientUnits="userSpaceOnUse"><stop offset=".855" class="r_52vrybx"/><stop offset=".877" class="pw7f7obzx"/></radialGradient><radialGradient id="iGELUWb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09564 15.95137 -17.22916 -5.50383 18.5 16.754)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="r_52vrybx"/><stop offset=".919" class="pw7f7obzx"/></radialGradient><radialGradient id="ixH4pBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2657 10.94717 -9.97346 -1.15312 18.635 16.515)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="of0r7wq2o"/><stop offset=".867" class="r_52vrybx"/></radialGradient><radialGradient id="iZOH7ST" cx="0" cy="0" r="1" gradientTransform="rotate(77.605 .134 13.852)scale(1.37545)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="id4xMRu" cx="0" cy="0" r="1" gradientTransform="matrix(.03482 1.22574 -1.48789 .04227 14.537 10.628)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="i3gM8se" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04537 -1.05507 0 15.231 10.83)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="iCgzZZd" cx="0" cy="0" r="1" gradientTransform="rotate(97.322 2.736 12.223)scale(.84906 1.33912)" gradientUnits="userSpaceOnUse"><stop class="qs6v65bnv"/><stop offset=".707" class="dzzsvzbef"/></radialGradient><radialGradient id="iie01Wd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83972 -2.01534 0 14.299 11.046)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="qs6v65bnv"/><stop offset=".707" class="dzzsvzbef"/></radialGradient><radialGradient id="iujwahj" cx="0" cy="0" r="1" gradientTransform="rotate(49.752 -5.217 20.244)scale(2.21432)" gradientUnits="userSpaceOnUse"><stop offset=".076" class="qs6v65bnv"/><stop offset=".316" class="dzzsvzbef"/></radialGradient><radialGradient id="i8t4bzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.99569 5.52618 0 15.232 12.788)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="tpxo8fbdg"/><stop offset=".77" class="gqduykb4u"/><stop offset=".812" class="gqduykb4u"/><stop offset=".975" class="n_6klihho"/></radialGradient><radialGradient id="iAbYpMZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.30097 .45365 -.4971 1.42557 15.232 10.869)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="iI7WEIb" cx="0" cy="0" r="1" gradientTransform="matrix(.5326 .84908 -.9304 .58361 16.143 10.791)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="irIEh2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.02178 1.09637 -1.20136 -.02387 16.776 11.094)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="ivacV6d" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.28 14.387)scale(2.63703)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="th8s44buy"/><stop offset="1" class="ijm9-wbbh"/></radialGradient><radialGradient id="iRfAief" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.2867 -5.68158 0 15.422 12.788)" gradientUnits="userSpaceOnUse"><stop offset=".824" class="v7e2km_9p"/><stop offset="1" class="v2tn_3ems"/></radialGradient><radialGradient id="i7V05Kq" cx="0" cy="0" r="1" gradientTransform="rotate(85.868 .044 14.371)scale(5.12495 8.86617)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="wh38egbdv"/><stop offset=".448" class="q4cmbw0fb"/><stop offset=".523" class="ewa96lbab"/><stop offset=".592" class="tzuclq-7b"/><stop offset=".699" class="dx6b3hbiu"/></radialGradient><radialGradient id="igJQHhc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.646 14.811)scale(1.7775)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="aw6-5j2fz"/><stop offset="1" class="k7lltkz0d"/></radialGradient><radialGradient id="iO5HJSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.52283 .01916 -.01934 1.53697 13.694 17.178)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="iMhjFbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.65338 0 0 1.66873 14.309 17.19)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="ijUEIQc" cx="0" cy="0" r="1" gradientTransform="rotate(26.764 -28.493 40.322)scale(1.73462 1.75073)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="iVNNjCd" cx="0" cy="0" r="1" gradientTransform="rotate(57.825 -5.908 24.157)scale(1.02524 1.45126)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="i0Xo5Xb" cx="0" cy="0" r="1" gradientTransform="rotate(108.286 3.584 14.684)scale(1.34121 1.89853)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="ipTgFGb" cx="0" cy="0" r="1" gradientTransform="rotate(104.704 3.895 15.153)scale(1.2583 1.78117)" gradientUnits="userSpaceOnUse"><stop class="loikb719k"/><stop offset=".707" class="b2g333vrx"/></radialGradient><radialGradient id="ioih0fe" cx="0" cy="0" r="1" gradientTransform="matrix(.00946 1.08319 -1.33929 .0117 13.909 17.806)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="v3juowbvc"/><stop offset=".707" class="ijm9-wbbh"/></radialGradient><radialGradient id="iICXWAn" cx="0" cy="0" r="1" gradientTransform="rotate(103.303 .298 14.732)scale(1.08734 1.38193)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="v3juowbvc"/><stop offset=".707" class="ijm9-wbbh"/></radialGradient><radialGradient id="ieA8ZHE" cx="0" cy="0" r="1" gradientTransform="matrix(0 36.0589 -27.706 0 16.07 -1.73)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="tcoi14v6o"/><stop offset=".724" class="haogwie1v"/></radialGradient><radialGradient id="iv1Cwyd" cx="0" cy="0" r="1" gradientTransform="matrix(.81708 .79455 -.4419 .45443 13.166 15.76)" gradientUnits="userSpaceOnUse"><stop class="gz6gydw7j"/><stop offset=".632" class="ve3wbhbuf"/></radialGradient><radialGradient id="iyUDPNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.67688 2.6652 0 14.188 15.897)" gradientUnits="userSpaceOnUse"><stop class="gz6gydw7j"/><stop offset=".632" class="ve3wbhbuf"/></radialGradient><radialGradient id="iHq1N7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6328 1.87861 0 15.738 15.928)" gradientUnits="userSpaceOnUse"><stop class="gz6gydw7j"/><stop offset=".632" class="ve3wbhbuf"/></radialGradient><radialGradient id="iVER9Je" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8456 -1.60901 0 12.21 22.481)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="yr8_8rbhe"/></radialGradient><radialGradient id="iPrYfpc" cx="0" cy="0" r="1" gradientTransform="rotate(97.105 -.02 20.05)scale(1.31052 1.43477)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="yr8_8rbhe"/></radialGradient><radialGradient id="iA8tq6b" cx="0" cy="0" r="1" gradientTransform="rotate(90 8.915 7.163)scale(36.0589)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="tcoi14v6o"/><stop offset=".715" class="haogwie1v"/></radialGradient><radialGradient id="iTfpT7E" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.08742 -6.05132 0 15.232 12.42)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="v7e2km_9p"/><stop offset=".962" class="v2tn_3ems"/></radialGradient><linearGradient id="ifFoLEy" x1="9.094" x2="23.351" y1="14.515" y2="14.515" gradientUnits="userSpaceOnUse"><stop offset=".112" class="kwdlj3b4x"/><stop offset=".186" class="it_i-hb8y"/><stop offset=".248" class="e_6e51bgb"/><stop offset=".258" class="e_6e51bgb"/><stop offset=".291" class="d62a7-97i"/><stop offset="1" class="k05n1gbkm"/></linearGradient><linearGradient id="iJam5Le" x1="15.822" x2="15.822" y1="5.491" y2="23.085" gradientUnits="userSpaceOnUse"><stop offset=".188" class="gb1uj557x"/><stop offset=".202" class="isa84ibom"/><stop offset=".215" class="x460z3oof"/><stop offset=".231" class="f6i2duyld"/><stop offset=".241" class="f6i2duyld"/><stop offset=".261" class="yvdqjyryh"/><stop offset=".276" class="iom_d3bwm"/><stop offset=".305" class="uudkl3b5c"/></linearGradient><linearGradient id="iQDeaic" x1="8.898" x2="23.715" y1="10.903" y2="10.903" gradientUnits="userSpaceOnUse"><stop offset=".12" class="ar_0x_g6j"/><stop offset=".175" class="sgcbkykfz"/></linearGradient><linearGradient id="ijbtH3d" x1="20.439" x2="15.224" y1="14.415" y2="14.415" gradientUnits="userSpaceOnUse"><stop offset=".51" class="v2tn_3ems"/><stop offset="1" class="v7e2km_9p"/></linearGradient><linearGradient id="irq8Xfd" x1="21.151" x2="15.777" y1="17.753" y2="21.317" gradientUnits="userSpaceOnUse"><stop offset=".321" class="j_qx7jvui"/><stop offset=".418" class="hw0cksbqc"/><stop offset=".473" class="hw0cksbqc"/><stop offset=".602" class="ahfhv0xqd"/><stop offset=".701" class="f8uzkobey"/><stop offset="1" class="imnk-_1cw"/></linearGradient><linearGradient id="iY6GBKe" x1="17.73" x2="15.983" y1="8.915" y2="19.296" gradientUnits="userSpaceOnUse"><stop offset=".234" class="kbztv3bfr"/><stop offset=".676" class="q38t5lbrw"/></linearGradient><linearGradient id="iEx9xsl" x1="17.73" x2="17.73" y1="11.534" y2="17.107" gradientUnits="userSpaceOnUse"><stop offset=".608" class="rdmqnbl2e"/><stop offset=".797" class="jisvjxhqe"/><stop offset=".926" class="q3tx-bcnn"/></linearGradient><linearGradient id="iHYbd2d" x1="16.7" x2="16.7" y1="12.805" y2="16.824" gradientUnits="userSpaceOnUse"><stop offset=".608" class="rdmqnbl2e"/><stop offset=".797" class="jisvjxhqe"/><stop offset=".926" class="q3tx-bcnn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:registered" /></template>
<style>
.ahfhv0xqd {
  stop-color: var(--svg-color--6b47be, #6B47BE);
}

.ar_0x_g6j {
  stop-color: var(--svg-color--45367b, #45367B);
}

.av6h53bro {
  stop-color: var(--svg-color--7962ca, #7962CA);
}

.aw6-5j2fz {
  stop-color: var(--svg-color--705eb2, #705EB2);
}

.b2g333vrx {
  stop-color: var(--svg-color--924cf9, #924CF9);
  stop-opacity: 0;
}

.d62a7-97i {
  stop-color: var(--svg-color--6150a0, #6150A0);
}

.dx6b3hbiu {
  stop-color: var(--svg-color--6a5aa4, #6A5AA4);
}

.dzzsvzbef {
  stop-color: var(--svg-color--503e8b, #503E8B);
  stop-opacity: 0;
}

.e_6e51bgb {
  stop-color: var(--svg-color--8979c8, #8979C8);
}

.ewa96lbab {
  stop-color: var(--svg-color--7162a7, #7162A7);
}

.f6i2duyld {
  stop-color: var(--svg-color--968acd, #968ACD);
}

.f8uzkobey {
  stop-color: var(--svg-color--5941a0, #5941A0);
}

.ft5dv1b6b {
  fill: none;
}

.fubv-kbbk {
  stop-color: var(--svg-color--7861c9, #7861C9);
}

.gb1uj557x {
  stop-color: var(--svg-color--6955a7, #6955A7);
}

.gqduykb4u {
  stop-color: var(--svg-color--9589cc, #9589CC);
}

.gz6gydw7j {
  stop-color: var(--svg-color--958bcc, #958BCC);
}

.h7d5uv04b {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M18.748 22.515c.21.35.58.57.99.57c.9 0 1.46-.98.96-1.73l-1.35-2.22c-.21-.32-.4-.59-.57-.82a6 6 0 0 0-.52-.63c-.17-.18-.35-.37-.55-.54q-.3-.255-.69-.48v-.04c.5-.12.94-.3 1.33-.53c.39-.24.73-.51 1.01-.84s.49-.7.64-1.12s.23-.88.23-1.38c0-.65-.12-1.2-.36-1.68c-.23-.48-.57-.88-.99-1.2s-.92-.56-1.49-.72s-1.19-.24-1.87-.24h-3.89c-.52.03-.84.23-.87.87v12.09c0 .67.54 1.2 1.2 1.2c.67 0 1.2-.54 1.2-1.2v-4.54h.97c.31 0 .58.03.82.11s.46.19.67.35s.41.36.61.61c.2.24.4.54.61.89zm-5.58-7.08v-4.6h2c.83 0 1.45.19 1.89.57q.66.57.66 1.59c0 .38-.06.72-.19 1.02c-.12.3-.3.56-.53.77q-.345.315-.81.48c-.31.11-.65.17-1.02.17z");
}

.haogwie1v {
  stop-color: var(--svg-color--41366a, #41366A);
}

.hw0cksbqc {
  stop-color: var(--svg-color--9085c9, #9085C9);
}

.ijm9-wbbh {
  stop-color: var(--svg-color--46377c, #46377C);
  stop-opacity: 0;
}

.imnk-_1cw {
  stop-color: var(--svg-color--7362b5, #7362B5);
  stop-opacity: 0;
}

.iom_d3bwm {
  stop-color: var(--svg-color--7057ba, #7057BA);
}

.isa84ibom {
  stop-color: var(--svg-color--6c58ab, #6C58AB);
}

.it_i-hb8y {
  stop-color: var(--svg-color--6a58ad, #6A58AD);
}

.j_qx7jvui {
  stop-color: var(--svg-color--6759a1, #6759A1);
}

.j0c2z9h3n {
  fill: var(--svg-color--8741e6, #8741E6);
  fill-rule: evenodd;
  d: path("M19.738 23.085c-.41 0-.78-.22-.99-.57l-1.91-3.22c-.21-.35-.41-.65-.61-.89c-.2-.25-.4-.45-.61-.61s-.43-.27-.67-.35s-.51-.11-.82-.11h-.968v-.705h3.858v.035q.39.225.69.48c.2.17.38.36.55.54s.35.39.52.63c.17.23.36.5.57.82l1.35 2.22c.5.75-.06 1.73-.96 1.73");
}

.jisvjxhqe {
  stop-color: var(--svg-color--8378c3, #8378C3);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7lltkz0d {
  stop-color: var(--svg-color--705eb2, #705EB2);
  stop-opacity: 0;
}

.kbztv3bfr {
  stop-color: var(--svg-color--524683, #524683);
  stop-opacity: 0;
}

.kwdlj3b4x {
  stop-color: var(--svg-color--47377d, #47377D);
}

.ldbb5595h {
  d: path("M2.549 11.274c1.918-5.446 7.115-9.359 13.21-9.359c7.72 0 14 6.28 14 14a13.9 13.9 0 0 1-2.367 7.781l-2.709-1.354a10.95 10.95 0 0 0 2.075-6.427c0-6.06-4.93-11-11-11c-4.925 0-9.1 3.247-10.5 7.714z");
}

.loikb719k {
  stop-color: var(--svg-color--924cf9, #924CF9);
}

.m-egtj6lu {
  d: path("M18.748 22.515c.21.35.58.57.99.57c.9 0 1.46-.98.96-1.73l-1.35-2.22c-.21-.32-.4-.59-.57-.82a6 6 0 0 0-.52-.63c-.17-.18-.35-.37-.55-.54q-.3-.255-.69-.48v-.04c.5-.12.94-.3 1.33-.53c.39-.24.73-.51 1.01-.84s.49-.7.64-1.12s.23-.88.23-1.38c0-.65-.12-1.2-.36-1.68c-.23-.48-.57-.88-.99-1.2s-.92-.56-1.49-.72s-1.19-.24-1.87-.24h-3.89c-.52.03-.84.23-.87.87v12.09c0 .67.54 1.2 1.2 1.2c.67 0 1.2-.54 1.2-1.2v-4.54h.97c.31 0 .58.03.82.11s.46.19.67.35s.41.36.61.61c.2.24.4.54.61.89zm-5.58-7.08v-4.6h2c.83 0 1.45.19 1.89.57q.66.57.66 1.59c0 .38-.06.72-.19 1.02c-.12.3-.3.56-.53.77q-.345.315-.81.48c-.31.11-.65.17-1.02.17z");
}

.mklo068xv {
  fill-rule: evenodd;
  d: path("M19.738 23.085c-.41 0-.78-.22-.99-.57l-1.91-3.22c-.21-.35-.41-.65-.61-.89c-.2-.25-.4-.45-.61-.61s-.43-.27-.67-.35s-.51-.11-.82-.11h-.968v-.705h3.858v.035q.39.225.69.48c.2.17.38.36.55.54s.35.39.52.63c.17.23.36.5.57.82l1.35 2.22c.5.75-.06 1.73-.96 1.73");
}

.n_6klihho {
  stop-color: var(--svg-color--9a90d1, #9A90D1);
  stop-opacity: 0;
}

.of0r7wq2o {
  stop-color: var(--svg-color--60519e, #60519E);
}

.pw7f7obzx {
  stop-color: var(--svg-color--554697, #554697);
}

.q38t5lbrw {
  stop-color: var(--svg-color--524582, #524582);
}

.q3tx-bcnn {
  stop-color: var(--svg-color--7660c4, #7660C4);
}

.q4cmbw0fb {
  stop-color: var(--svg-color--604d9c, #604D9C);
}

.q6m37fbbg {
  fill: var(--svg-color--6f56ba, #6F56BA);
  fill-rule: evenodd;
  d: path("M17.018 16.66v-.035c.5-.12.94-.3 1.33-.53c.39-.24.73-.51 1.01-.84s.49-.7.64-1.12s.23-.88.23-1.38c0-.65-.12-1.2-.36-1.68c-.23-.48-.57-.88-.99-1.2s-.92-.56-1.49-.72s-1.19-.24-1.87-.24h-.286v1.92c.798.01 1.398.2 1.826.57q.66.57.66 1.59c0 .38-.06.72-.19 1.02c-.12.3-.3.56-.53.77q-.345.315-.81.48q-.437.158-.956.17v1.225z");
}

.qs6v65bnv {
  stop-color: var(--svg-color--503e8a, #503E8A);
}

.quxrynbdt {
  fill-rule: evenodd;
  d: path("M17.018 16.66v-.035c.5-.12.94-.3 1.33-.53c.39-.24.73-.51 1.01-.84s.49-.7.64-1.12s.23-.88.23-1.38c0-.65-.12-1.2-.36-1.68c-.23-.48-.57-.88-.99-1.2s-.92-.56-1.49-.72s-1.19-.24-1.87-.24h-.286v1.92c.798.01 1.398.2 1.826.57q.66.57.66 1.59c0 .38-.06.72-.19 1.02c-.12.3-.3.56-.53.77q-.345.315-.81.48q-.437.158-.956.17v1.225z");
}

.qzjs57bda {
  stop-color: var(--svg-color--50467f, #50467F);
}

.r_52vrybx {
  stop-color: var(--svg-color--60519e, #60519E);
  stop-opacity: 0;
}

.rdmqnbl2e {
  stop-color: var(--svg-color--61539f, #61539F);
  stop-opacity: 0;
}

.sgcbkykfz {
  stop-color: var(--svg-color--43337c, #43337C);
  stop-opacity: 0;
}

.sgjth1b6t {
  stop-color: var(--svg-color--7962ca, #7962CA);
  stop-opacity: 0;
}

.tcoi14v6o {
  stop-color: var(--svg-color--423473, #423473);
  stop-opacity: 0;
}

.te5lusssm {
  d: path("M3.68 8.84a13.9 13.9 0 0 0-1.922 7.075c0 7.72 6.28 14 14 14c5.8 0 10.787-3.544 12.91-8.581l-2.69-1.345c-1.621 4.056-5.588 6.926-10.22 6.926c-6.07 0-11-4.94-11-11c0-2.098.59-4.06 1.611-5.73z");
}

.th8s44buy {
  stop-color: var(--svg-color--46377d, #46377D);
}

.tpxo8fbdg {
  stop-color: var(--svg-color--9a90d0, #9A90D0);
  stop-opacity: 0;
}

.tzuclq-7b {
  stop-color: var(--svg-color--786bb1, #786BB1);
}

.uudkl3b5c {
  stop-color: var(--svg-color--715abd, #715ABD);
  stop-opacity: 0;
}

.v2tn_3ems {
  stop-color: var(--svg-color--534683, #534683);
}

.v3juowbvc {
  stop-color: var(--svg-color--46377c, #46377C);
}

.v7e2km_9p {
  stop-color: var(--svg-color--534683, #534683);
  stop-opacity: 0;
}

.ve3wbhbuf {
  stop-color: var(--svg-color--958bcc, #958BCC);
  stop-opacity: 0;
}

.wg0i3t8pb {
  stop-color: var(--svg-color--8a7fc3, #8A7FC3);
  stop-opacity: 0;
}

.wh38egbdv {
  stop-color: var(--svg-color--413673, #413673);
}

.wk449o50m {
  stop-color: var(--svg-color--9488d2, #9488D2);
}

.x460z3oof {
  stop-color: var(--svg-color--8675c6, #8675C6);
}

.yb49kpbfn {
  stop-color: var(--svg-color--8b80c5, #8B80C5);
}

.yqcytmbfv {
  fill-rule: evenodd;
  d: path("M16.06 16.653v-1.346a3 3 0 0 1-.892.128h-1.996v1.218z");
}

.yr8_8rbhe {
  stop-color: var(--svg-color--9447fe, #9447FE);
  stop-opacity: 0;
}

.yv0g24i-p {
  stop-color: var(--svg-color--9447fe, #9447FE);
}

.yvdqjyryh {
  stop-color: var(--svg-color--7a69c1, #7A69C1);
}

.zhpnicbfs {
  fill: var(--svg-color--7362b5, #7362B5);
  d: path("M18.748 22.515c.21.35.58.57.99.57c.9 0 1.46-.98.96-1.73l-1.35-2.22c-.21-.32-.4-.59-.57-.82a6 6 0 0 0-.52-.63c-.17-.18-.35-.37-.55-.54q-.3-.255-.69-.48v-.04c.5-.12.94-.3 1.33-.53c.39-.24.73-.51 1.01-.84s.49-.7.64-1.12s.23-.88.23-1.38c0-.65-.12-1.2-.36-1.68c-.23-.48-.57-.88-.99-1.2s-.92-.56-1.49-.72s-1.19-.24-1.87-.24h-3.89c-.52.03-.84.23-.87.87v12.09c0 .67.54 1.2 1.2 1.2c.67 0 1.2-.54 1.2-1.2v-4.54h.97c.31 0 .58.03.82.11s.46.19.67.35s.41.36.61.61c.2.24.4.54.61.89zm-5.58-7.08v-4.6h2c.83 0 1.45.19 1.89.57q.66.57.66 1.59c0 .38-.06.72-.19 1.02c-.12.3-.3.56-.53.77q-.345.315-.81.48c-.31.11-.65.17-1.02.17z");
}

</style>
