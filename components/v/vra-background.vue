<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGLDioveXp)" class="r4i437pya"/><path class="wv0mehbjz"/></g><defs><linearGradient id="SVGLDioveXp" x1="5.465" x2="15.068" y1="8.919" y2="18.956" gradientUnits="userSpaceOnUse"><stop class="j4rigybbj"/><stop offset="1" class="xac7isbtf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vra-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j4rigybbj {
  stop-color: var(--svg-color--f82b1e, #f82b1e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wv0mehbjz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.883 7.749c.085 0 .139.1.108.18l-.293.754a.12.12 0 0 1-.11.068H18.54a.12.12 0 0 0-.103.074l-.17.325c-.018.037.028.099.07.1h.925c.084 0 .139.102.109.176l-.306.74c-.02.04-.064.082-.11.082h-1.048c-.046-.002-.11.01-.128.052l-3.23 7.389a.09.09 0 0 1-.09.062H9.614c-.046.002-.09-.034-.109-.076l-2.733-6.74c-.035-.07.025-.186.103-.186h4.397c.043 0 .085.044.104.087l.622 1.414l2.923-5.926c.02-.04.064-.075.11-.075h4.39c.078 0 .137.104.103.174l-.623 1.254c-.018.037.013.072.054.072zm-7.245.93a.12.12 0 0 1-.107.07H4.563a.12.12 0 0 1-.106-.07l-.448-.739c-.032-.071.028-.19.106-.191h.927c.043 0 .07-.018.053-.058l-.537-1.276c-.032-.072.028-.165.106-.166h4.39c.047 0 .088.027.107.069l.585 1.387c.02.042.06.044.106.044h3.069c.083 0 .14.113.105.192zm-.846 1.493c-.018.042-.061.076-.107.076H5.277c-.045 0-.088-.034-.105-.076l-.46-.746c-.033-.071.027-.177.105-.178h7.24c.085 0 .141.1.107.178z");
}

.xac7isbtf {
  stop-color: var(--svg-color--531685, #531685);
}

</style>
