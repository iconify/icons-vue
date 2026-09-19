<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lyl5rtb9m.css';
import '../../css/c/col8s83ww.css';
import '../../css/b/boxfqhb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="lyl5rtb9m"/><path class="col8s83ww"/><path class="boxfqhb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-alpha-down-bold" /></template>
