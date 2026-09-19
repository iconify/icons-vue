<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sz6bki7ve.css';
import '../../css/b/bvfnbqqth.css';
import '../../css/q/qvs9goe1w.css';
import '../../css/g/gpk4jg8ax.css';
import '../../css/b/bad077nrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="sz6bki7ve"/><path class="bvfnbqqth"/><path class="qvs9goe1w"/><path class="gpk4jg8ax"/><path class="bad077nrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:trolley-arrow-up" /></template>
