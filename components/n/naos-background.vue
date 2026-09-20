<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG1cqSCc6d)" class="um_bbac7j"/><path class="aezt6hbvg"/><path class="bp0n3cy_p"/></g><defs><linearGradient id="SVG1cqSCc6d" x1="17.412" x2="4.941" y1="5.647" y2="17.412" gradientUnits="userSpaceOnUse"><stop class="iiy-gkbvj"/><stop offset="1" class="t3wc5db8y"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:naos-background" /></template>
<style>
.aezt6hbvg {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M13.647 10.23c.15.09.235.236.235.391q0 .106-.06.207a.45.45 0 0 1-.41.23a.4.4 0 0 1-.189-.06L8.235 7.953v7.939l2.174-1.007a.4.4 0 0 1 .217-.062c.15 0 .292.085.376.236c.047.07.066.155.061.235a.45.45 0 0 1-.226.358l-2.86 1.44c-.085.042-.17.085-.255.085c-.259 0-.428-.17-.428-.424V7.26c0-.085 0-.127.047-.212c.122-.211.376-.296.593-.169l5.718 3.346z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bp0n3cy_p {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M10.33 13.247a.42.42 0 0 1-.212-.377a.5.5 0 0 1 .043-.197c.06-.142.23-.207.4-.203c.07 0 .14.014.202.038l5.002 3.021V7.971L13.602 9.12a.43.43 0 0 1-.443-.01a.5.5 0 0 1-.155-.155a.38.38 0 0 1-.061-.23a.44.44 0 0 1 .235-.344l2.843-1.478c.084-.037.169-.08.254-.08c.258 0 .433.165.433.41v9.063c0 .085 0 .123-.047.207c-.128.203-.386.245-.598.165z");
}

.ft5dv1b6b {
  fill: none;
}

.iiy-gkbvj {
  stop-color: var(--svg-color--5a47f0, #5a47f0);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t3wc5db8y {
  stop-color: var(--svg-color--2a1ba8, #2a1ba8);
}

.um_bbac7j {
  d: path("M12 4c4.39 0 8 3.567 8 8c0 4.39-3.567 8-8 8c-4.39 0-8-3.567-8-8s3.567-8 8-8");
}

</style>
