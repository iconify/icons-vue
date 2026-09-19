<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e8-14pblu.css';
import '../../css/w/whtc4r5ex.css';
import '../../css/o/ovr92_bin.css';
import '../../css/s/suljz2g3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="e8-14pblu"/><path clip-rule="evenodd" class="whtc4r5ex"/><path class="ovr92_bin"/><path clip-rule="evenodd" class="suljz2g3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:question-circle-outline" /></template>
