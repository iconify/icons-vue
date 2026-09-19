<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qx9a5vb2t.css';
import '../../css/m/mbdj0e04q.css';
import '../../css/j/jqrvh3_gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qx9a5vb2t"/><path class="mbdj0e04q"/><path class="jqrvh3_gi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:trash" /></template>
