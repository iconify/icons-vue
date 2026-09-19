<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/ptk67nbuj.css';
import '../../css/q/qxpfaf6dk.css';
import '../../css/q/qle0cdbgv.css';
import '../../css/e/e0i688bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ptk67nbuj"/><path clip-rule="evenodd" class="qxpfaf6dk"/><path class="qle0cdbgv"/><path clip-rule="evenodd" class="e0i688bvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:search-tint-outline" /></template>
