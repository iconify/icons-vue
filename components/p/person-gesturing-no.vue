<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qgm_jcctn.css';
import '../../css/c/ci6mbbc_m.css';
import '../../css/b/br6ab8rnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="qgm_jcctn"/><path class="ci6mbbc_m"/><path class="br6ab8rnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-gesturing-no" /></template>
