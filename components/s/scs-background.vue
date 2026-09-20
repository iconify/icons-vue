<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="li94jsb-s"/><path fill="url(#SVGjuH2Zcnj)" class="l__z-xbhj"/><path class="om16j4bgy"/><path class="huwvc2bms"/><path class="oz1-kkbcn"/><path class="x05j6zbzv"/></g><defs><linearGradient id="SVGjuH2Zcnj" x1="8.75" x2="15" y1="4.75" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="pi5g78zuk"/><stop offset="1" class="pue33vb4s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:scs-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.huwvc2bms {
  fill: var(--svg-color--1f232a, #1f232a);
  d: path("m15.999 9.412l.235.706l-3.059-3.059l.471 2.588l3.765 3.53l.706 1.647l-5.883-4.941L12 5.177z");
}

.l__z-xbhj {
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.058");
}

.li94jsb-s {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.058m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.om16j4bgy {
  fill: var(--svg-color--16191d, #16191d);
  d: path("M11.53 5.883v-.706L7.765 8.94l-2.118 5.647l1.648.471l4-2.823l3.764 2.352l-4.235 1.883l.941.47l5.647-2.353l-6.117-4.705l-4.942 4L8 9.413z");
}

.oz1-kkbcn {
  fill: var(--svg-color--d2d2d4, #d2d2d4);
  d: path("M14.823 12.47v-1.412h.349v.57h.244v-.57h.349v1.412h-.349v-.616h-.244v.616zm-.682 0a.6.6 0 0 1-.268-.047a.33.33 0 0 1-.165-.141a.55.55 0 0 1-.061-.25l.325-.037q-.002.092.018.141q.02.058.047.08a.16.16 0 0 0 .085.024q.056.001.075-.034a.1.1 0 0 0 .02-.065a.2.2 0 0 0-.048-.142a.7.7 0 0 0-.141-.122l-.15-.103a1 1 0 0 1-.165-.146a.33.33 0 0 1-.066-.212c0-.113.047-.202.132-.264a.6.6 0 0 1 .348-.094q.143.001.221.038a.3.3 0 0 1 .127.094a.6.6 0 0 1 .061.132c.01.047.02.085.02.127l-.33.033c0-.042 0-.075-.01-.108a.12.12 0 0 0-.028-.066q-.021-.029-.07-.028a.1.1 0 0 0-.08.037a.13.13 0 0 0-.024.07c0 .048.014.095.047.128l.118.094l.14.103a.7.7 0 0 1 .19.175c.05.06.079.14.079.235a.3.3 0 0 1-.056.179a.4.4 0 0 1-.156.122a.5.5 0 0 1-.235.047m-1.435 0l.282-1.412h.376l.283 1.412h-.306l-.047-.296h-.221l-.052.296zM13.1 12h.16l-.08-.565zm-1.092.47a.6.6 0 0 1-.287-.056a.33.33 0 0 1-.15-.16a.6.6 0 0 1-.043-.24v-.494a.55.55 0 0 1 .047-.245a.3.3 0 0 1 .141-.16a.64.64 0 0 1 .292-.057c.118 0 .212.02.278.047a.34.34 0 0 1 .141.142a.5.5 0 0 1 .042.207v.117h-.348v-.211a.1.1 0 0 0-.033-.062q-.022-.027-.08-.028q-.056 0-.085.028a.12.12 0 0 0-.032.062v.814l.037.06q.03.021.08.02c.038 0 .066-.005.08-.024a.1.1 0 0 0 .028-.061l.005-.08v-.146h.348v.118q0 .12-.042.211a.3.3 0 0 1-.141.142a.56.56 0 0 1-.278.056m-2.715-2.127v-.226l-1.28 1.205l-.72 1.807l.56.15l1.36-.903l1.275.753l-1.435.602l.32.15l1.915-.752l-2.075-1.506l-1.68 1.28l.56-1.43z");
}

.pi5g78zuk {
  stop-color: var(--svg-color--383d45, #383d45);
}

.pue33vb4s {
  stop-color: var(--svg-color--1a1d22, #1a1d22);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x05j6zbzv {
  fill: var(--svg-color--d2d2d4, #d2d2d4);
  d: path("m10.81 11.473l.08.225l-1.036-.979l.155.829l1.28 1.13l.24.526l-2-1.58l-.075-1.507z");
}

</style>
