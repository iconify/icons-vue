<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xy07pe4cu.css';
import '../../css/a/a7zornbiy.css';
import '../../css/t/t5e808btk.css';
import '../../css/l/lpqj20mmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xy07pe4cu"/><path class="a7zornbiy"/><path class="t5e808btk"/><path class="lpqj20mmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:printer-duo" /></template>
