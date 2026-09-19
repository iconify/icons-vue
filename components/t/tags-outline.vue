<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l4jz1gwne.css';
import '../../css/m/mszjz-b4f.css';
import '../../css/y/y66jmy99b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="l4jz1gwne"/><path clip-rule="evenodd" class="mszjz-b4f"/><path class="y66jmy99b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tags-outline" /></template>
