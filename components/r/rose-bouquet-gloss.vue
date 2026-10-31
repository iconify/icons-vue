<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/frkxq78kw.css';
import '../../css/r/razmnrbbm.css';
import '../../css/d/d3vf8keel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="frkxq78kw wm-deco"/><path class="razmnrbbm wm-k"/><path class="d3vf8keel wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rose-bouquet-gloss" /></template>
