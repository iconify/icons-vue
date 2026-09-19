<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nkt0tm_pc.css';
import '../../css/s/swm4sl8ha.css';
import '../../css/o/orier7xvr.css';
import '../../css/o/oqkwxkbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nkt0tm_pc"/><path clip-rule="evenodd" class="swm4sl8ha"/><path class="orier7xvr"/><path clip-rule="evenodd" class="oqkwxkbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:trash-1-outline" /></template>
