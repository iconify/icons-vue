<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGrh4XmbLV)" class="r4i437pya"/><path clip-rule="evenodd" class="ujq1mkbwy"/><path class="oo2mzobsw"/><path clip-rule="evenodd" class="c8ted9b_d"/><path class="is7u9cbeg"/></g><defs><linearGradient id="SVGrh4XmbLV" x1="6.287" x2="9.268" y1="12.606" y2="18.721" gradientUnits="userSpaceOnUse"><stop class="e9nwqu0wp"/><stop offset=".857" class="mfxi6ubou"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nvt-background" /></template>
<style>
.c8ted9b_d {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.307 6.946h.003l.433.767l-.219.573l-.432-.765zm-.328 2.773l-.428-.756l-.216.58l.425.751zm-.768 2.02l-.416-.735l-.212.571l.413.729z");
}

.e9nwqu0wp {
  stop-color: var(--svg-color--4e90e2, #4e90e2);
}

.ft5dv1b6b {
  fill: none;
}

.is7u9cbeg {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.987 11.686l.427.756l-.221.58l-.421-.763zm-.329 2.781l-.437-.767l-.216.576l.438.774zm-.758 2.027l-.436-.766l-.206.562l.435.761z");
}

.mfxi6ubou {
  stop-color: var(--svg-color--17e9d9, #17e9d9);
}

.oo2mzobsw {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.69 17.051h-2.997l3.573-9.586a.8.8 0 0 1 .289-.376a.8.8 0 0 1 .447-.143H20l-3.574 9.586a.8.8 0 0 1-.289.377a.8.8 0 0 1-.447.142m-8.693 0H4l3.573-9.586a.8.8 0 0 1 .288-.376a.8.8 0 0 1 .447-.143h2.999l-3.574 9.586a.8.8 0 0 1-.289.377a.8.8 0 0 1-.447.142");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ujq1mkbwy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m11.308 6.946l-.216.58l3.104 5.492l.216-.58zm-1.725 4.63l3.112 5.477l.206-.553l-3.106-5.496zm3.856 3.47l-3.103-5.491l.216-.58l3.103 5.493z");
}

</style>
