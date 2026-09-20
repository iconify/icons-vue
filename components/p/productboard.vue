<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lmmvpew-x.css';
import '../../css/z/zbkydgbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":42};
const content = `<g class="cuyn6tgcc"><path class="lmmvpew-x"/><path class="zbkydgbar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:productboard" /></template>
