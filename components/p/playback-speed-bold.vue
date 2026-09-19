<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r3hmpab7s.css';
import '../../css/h/hq-wbibec.css';
import '../../css/o/o_k6lcc5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r3hmpab7s"/><path clip-rule="evenodd" class="hq-wbibec"/><path class="o_k6lcc5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:playback-speed-bold" /></template>
