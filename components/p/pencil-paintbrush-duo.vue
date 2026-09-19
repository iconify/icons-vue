<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hj8tmj6jq.css';
import '../../css/f/fxo16bbjw.css';
import '../../css/u/u9ltmbbpb.css';
import '../../css/r/roaf1_b0h.css';
import '../../css/c/cu5ei1b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hj8tmj6jq"/><path class="fxo16bbjw"/><path class="u9ltmbbpb"/><path class="roaf1_b0h"/><path class="cu5ei1b8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pencil-paintbrush-duo" /></template>
