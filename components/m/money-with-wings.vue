<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mwvg59b8s.css';
import '../../css/c/cii0-5b2j.css';
import '../../css/r/rnz4p0b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="mwvg59b8s"/><path class="cii0-5b2j"/><path class="rnz4p0b8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:money-with-wings" /></template>
