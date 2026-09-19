<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/prax9_bmi.css';
import '../../css/g/g8i_fbple.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<g class="n1lsf0bnc"><path class="prax9_bmi"/><path class="g8i_fbple"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:paper-shredder" /></template>
