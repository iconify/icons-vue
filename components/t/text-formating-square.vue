<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r2pch-97f.css';
import '../../css/z/zx8da_loy.css';
import '../../css/o/oy13cc5we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r2pch-97f"/><path class="zx8da_loy"/><path class="oy13cc5we"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:text-formating-square" /></template>
