<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oms7h5bxr.css';
import '../../css/t/tbr084bwb.css';
import '../../css/t/tbsg3acud.css';
import '../../css/p/ppcxs2mja.css';
import '../../css/b/brq38abng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="oms7h5bxr"/><path class="tbr084bwb"/><path class="tbsg3acud"/><path class="ppcxs2mja"/><path class="brq38abng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="unjs:unctx" /></template>
