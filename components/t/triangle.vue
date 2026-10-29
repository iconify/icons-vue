<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fhomj3b2y.css';
import '../../css/e/e80p1vb8l.css';
import '../../css/y/yfkwu4bgz.css';
import '../../css/w/w2q9-jbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fhomj3b2y wm-k"/><path class="e80p1vb8l wm-k"/><path class="wm-k yfkwu4bgz"/><path class="w2q9-jbxn wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:triangle" /></template>
