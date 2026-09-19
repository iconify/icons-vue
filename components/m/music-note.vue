<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/yp2pgobra.css';
import '../../css/t/t2s1tmb8r.css';
import '../../css/w/wa95x5b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="yp2pgobra"/><ellipse class="t2s1tmb8r"/><path class="wa95x5b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:music-note" /></template>
