<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dsdpatbbu.css';
import '../../css/g/gqt1trakv.css';
import '../../css/z/zf-73sbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="dsdpatbbu"/><path class="gqt1trakv"/><path class="zf-73sbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:open" /></template>
