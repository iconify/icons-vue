<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qh1hhtown.css';
import '../../css/s/san_b9rep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="qh1hhtown"/><path class="san_b9rep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:triangle-double-arrow-right" /></template>
