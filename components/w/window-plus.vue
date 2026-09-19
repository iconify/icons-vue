<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t_owy1dlv.css';
import '../../css/a/a1dbd2dld.css';
import '../../css/j/j_udulbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="t_owy1dlv"/><path class="a1dbd2dld"/><path class="j_udulbub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:window-plus" /></template>
