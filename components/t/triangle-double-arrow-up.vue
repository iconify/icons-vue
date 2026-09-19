<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v1dlfbb5m.css';
import '../../css/i/iy7wambnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<g class="n1lsf0bnc"><path class="v1dlfbb5m"/><path class="iy7wambnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:triangle-double-arrow-up" /></template>
