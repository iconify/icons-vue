<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nwjdbdcvs"/><path class="p7ii8tfgd"/><path class="xg137yxmz"/><path class="g2_pbqb2a"/><path class="onfi6jxpl"/><path class="gbb3uh7ot"/><path class="o672ssb5h"/><path class="q-j5gnb2m"/><path clip-rule="evenodd" class="lx_5o7bll"/><path fill="url(#SVG2qYEseIF)" clip-rule="evenodd" class="lwxfv921z"/><path class="zcocd9mlh"/><defs><linearGradient id="SVG2qYEseIF" x1="3.74" x2="20.075" y1="15.445" y2="17.255" gradientUnits="userSpaceOnUse"><stop offset=".47" class="evdjsvaiv"/><stop offset=".48" class="hmzhytbjs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tama" /></template>
<style>
.evdjsvaiv {
  stop-color: var(--svg-color--ffff74, #ffff74);
}

.ft5dv1b6b {
  fill: none;
}

.g2_pbqb2a {
  fill: var(--svg-color--a31b3f, #a31b3f);
  d: path("M10 16.5h-.5v.43l.8.57h3.755s2.135-1.82 3.136-2.65v-1.91l-1.04-1.665V10.26l.6-.705V7h-1.016l-1.734 2.19h-.55v.19l.55.345l1.88-2.345h.61v2l-1.025.88l-.205.785l1.004 2.07v1.74L13.77 17H10z");
}

.gbb3uh7ot {
  fill: var(--svg-color--ff9b37, #ff9b37);
  d: path("M7.5 13.065V14.5H8v-.935l.4-.82h1.1v.57l.3.375h.68l.655-.945h1.995l.715.945h.655l.495-.375v-.565h.8l.7.82v.93h.5v-1.435L15.91 11.68v-.36h-.35v-.62H16v-.5l.5-.77V7.3h-.585L13.965 9c-.215-.12-.895-.35-1.865-.35c-.965 0-1.65.23-1.865.35l-1.83-1.7H7.73v2.13l.77.775v.5h.25v.615H8.4v.36z");
}

.hmzhytbjs {
  stop-color: var(--svg-color--a31b3f, #a31b3f);
}

.lwxfv921z {
  fill-rule: evenodd;
  d: path("M12 20.75a8.75 8.75 0 1 0 0-17.498a8.75 8.75 0 0 0 0 17.498M20.75 12a8.75 8.75 0 1 1-17.499 0a8.75 8.75 0 0 1 17.499 0m.25 0a8.998 8.998 0 0 1-12.444 8.315A9 9 0 1 1 21 12m-.5 0a8.5 8.5 0 1 1-17 0a8.5 8.5 0 0 1 17 0");
}

.lx_5o7bll {
  fill: var(--svg-color--ff9b37, #ff9b37);
  fill-rule: evenodd;
  d: path("M19.5 12a7.5 7.5 0 1 1-15 0a7.5 7.5 0 0 1 15 0m-.5 0a7 7 0 1 1-14.001 0a7 7 0 0 1 14 0");
}

.nwjdbdcvs {
  fill: var(--svg-color--ffd643, #ffd643);
  d: path("M20.5 12a8.5 8.5 0 1 1-17 0a8.5 8.5 0 0 1 17 0");
}

.o672ssb5h {
  fill: var(--svg-color--ffd643, #ffd643);
  d: path("M10.5 10.501h.5v-.5h-.5zm2.5-.5v.5h.5v-.5zm2.525-2.21l-.795.79v.92h.475v.5h.32l.66-.765v-1.45h-.66zm-6.86.03l.835.795v.885H9v.5h-.34L8 9.271v-1.45z");
}

.onfi6jxpl {
  fill: var(--svg-color--ffff74, #ffff74);
  d: path("M7.23 14.57L9.47 17l.39-.175l-2.2-2.07l-.15-.71l.44-1.27l2.34-.96l5.95-4.425V7h-.64l-1.636 2h-.72v.01h-2.42V9h-.535L8.364 7H7.95l-.435.39V9.5l1.02 1.35l-1.305 2.06z");
}

.p7ii8tfgd {
  fill: var(--svg-color--a31b3f, #a31b3f);
  d: path("M9.82 14H9.5v.775l1.09.725h2.83l1.08-.725V14h-.34l-.475.775h-1.184V14.5h-1v.275h-1.215z");
}

.q-j5gnb2m {
  fill: var(--svg-color--a31b3f, #a31b3f);
  d: path("M10.6 11H10v1h.5v.5h.5v-1.04zm2.8 0h.6v1h-.5v.5H13v-1.04z");
}

.xg137yxmz {
  fill: var(--svg-color--ff9b37, #ff9b37);
  d: path("M11 15.71V15h2v.71h-.5V16h-1v-.29z");
}

.zcocd9mlh {
  fill: var(--svg-color--a31b3f, #a31b3f);
  d: path("M11 12.74v.52l.3.24h1.4l.3-.24v-.52l-.3-.24h-1.4z");
}

</style>
