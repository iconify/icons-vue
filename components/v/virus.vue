<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lrw3p1b1a.css';
import '../../css/e/e5db84qsw.css';
import '../../css/g/g-brd0vfh.css';
import '../../css/p/p8qto7xhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lrw3p1b1a"/><rect class="e5db84qsw"/><rect class="g-brd0vfh"/><rect class="p8qto7xhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:virus" /></template>
