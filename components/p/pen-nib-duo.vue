<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qgm9wdbgk.css';
import '../../css/z/zne832bro.css';
import '../../css/a/argowfbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qgm9wdbgk"/><path class="zne832bro"/><path class="argowfbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-nib-duo" /></template>
