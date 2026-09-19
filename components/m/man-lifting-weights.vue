<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ivipgsbps.css';
import '../../css/i/i01gd7s9p.css';
import '../../css/k/k15ug01ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ivipgsbps"/><path class="i01gd7s9p"/><path class="k15ug01ci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-lifting-weights" /></template>
