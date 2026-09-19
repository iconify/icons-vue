<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nybkspifn.css';
import '../../css/n/n1u32wbyg.css';
import '../../css/b/b6v88-svo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="nybkspifn"/><path class="n1u32wbyg"/><path class="b6v88-svo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:patch-question" /></template>
