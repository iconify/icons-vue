<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y92_fgbke.css';
import '../../css/r/rvc7i_b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><circle transform="rotate(-9 18.078 8.286)" class="y92_fgbke"/><path class="rvc7i_b9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:sort" /></template>
