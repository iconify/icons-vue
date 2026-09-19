<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g8idwqlpa.css';
import '../../css/j/jwcvhdcld.css';
import '../../css/e/e3fdoqbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="g8idwqlpa"/><path class="jwcvhdcld"/><path class="e3fdoqbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-in-motorized-wheelchair-facing-right" /></template>
