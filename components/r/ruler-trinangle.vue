<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uvcdgx14e.css';
import '../../css/j/jplez8box.css';
import '../../css/n/nc3sgkbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="uvcdgx14e"/><path class="jplez8box"/><path class="nc3sgkbcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:ruler-trinangle" /></template>
