<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/g63mxooxl.css';
import '../../css/f/f0p3izb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<g transform="translate(1)" class="n1lsf0bnc"><path class="g63mxooxl"/><ellipse class="f0p3izb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:ying-yang" /></template>
