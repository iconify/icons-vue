<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/f/fi_edld4q.css';
import '../../css/j/jh5ifwous.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><path class="fi_edld4q"/><path class="jh5ifwous"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:monitor-bold" /></template>
