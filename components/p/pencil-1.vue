<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mcz2a8bsd.css';
import '../../css/q/qagdjebam.css';
import '../../css/c/c6eoz-bnz.css';
import '../../css/v/v89bqvxpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mcz2a8bsd"/><path clip-rule="evenodd" class="qagdjebam"/><path clip-rule="evenodd" class="c6eoz-bnz"/><path class="v89bqvxpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:pencil-1" /></template>
