<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qa3q44xuv.css';
import '../../css/u/u_nwqzbhk.css';
import '../../css/q/q9pr91bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qa3q44xuv"/><path class="u_nwqzbhk"/><path clip-rule="evenodd" class="q9pr91bjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:pen-fountain" /></template>
