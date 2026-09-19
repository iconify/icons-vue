<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jarc2sbrx.css';
import '../../css/u/ud40kobrs.css';
import '../../css/a/ai8-50cvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="jarc2sbrx"/><path class="ud40kobrs"/><path class="ai8-50cvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tennis" /></template>
