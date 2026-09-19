<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m3c2kv-_z.css';
import '../../css/k/ks4-49wik.css';
import '../../css/t/tjiohdtgt.css';
import '../../css/x/xkvu3i4cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="m3c2kv-_z"/><path class="ks4-49wik"/><path clip-rule="evenodd" class="tjiohdtgt"/><path class="xkvu3i4cm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:shield" /></template>
