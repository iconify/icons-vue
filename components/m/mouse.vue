<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hec_imb9e.css';
import '../../css/o/og38x22ig.css';
import '../../css/z/zsmg9wb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="hec_imb9e"/><path class="og38x22ig"/><path class="zsmg9wb3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:mouse" /></template>
