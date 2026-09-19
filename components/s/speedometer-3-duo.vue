<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s_5je2bdi.css';
import '../../css/d/dmxtwacpa.css';
import '../../css/o/ofb6srb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="s_5je2bdi"/><path class="dmxtwacpa"/><path class="ofb6srb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:speedometer-3-duo" /></template>
