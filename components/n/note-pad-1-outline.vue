<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d0-ux1bvw.css';
import '../../css/l/l22prnp0x.css';
import '../../css/z/zmfcjwbzt.css';
import '../../css/q/q4tm2pwul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="d0-ux1bvw"/><path clip-rule="evenodd" class="l22prnp0x"/><path class="zmfcjwbzt"/><path clip-rule="evenodd" class="q4tm2pwul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-pad-1-outline" /></template>
