<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cu7qyy4za.css';
import '../../css/a/a4g_h2opr.css';
import '../../css/x/xyijo7zcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="cu7qyy4za"/><path class="a4g_h2opr"/><path class="xyijo7zcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone-add-bold" /></template>
