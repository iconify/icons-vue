<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u7gemwb9q.css';
import '../../css/m/m6_rnhb7u.css';
import '../../css/s/sxb-9pbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="u7gemwb9q"/><path class="m6_rnhb7u"/><path class="sxb-9pbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:monkey-face" /></template>
