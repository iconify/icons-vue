<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/r4eb564mb.css';
import '../../css/c/c18re7vav.css';
import '../../css/n/njoak0bdt.css';
import '../../css/e/es9uiwbnk.css';
import '../../css/x/xb8_cbr0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="r4eb564mb"/><path class="c18re7vav"/><path class="njoak0bdt"/><circle transform="rotate(45 26.041 22.042)" class="es9uiwbnk"/><path class="xb8_cbr0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:microscope-one" /></template>
