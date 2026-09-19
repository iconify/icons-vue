<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b23vqdbdf.css';
import '../../css/f/fle2h5bsn.css';
import '../../css/z/zbj15_b-k.css';
import '../../css/v/vz6f2jbnw.css';
import '../../css/z/zjsy__bjj.css';
import '../../css/l/lz1nthk-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="b23vqdbdf"/><path class="fle2h5bsn"/><path clip-rule="evenodd" class="zbj15_b-k"/><path class="vz6f2jbnw"/><path class="zjsy__bjj"/><path class="lz1nthk-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:van" /></template>
