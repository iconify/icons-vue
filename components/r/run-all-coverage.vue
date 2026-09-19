<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qtgb06r4t.css';
import '../../css/z/z9zekhb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="qtgb06r4t"/><path class="z9zekhb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:run-all-coverage" /></template>
