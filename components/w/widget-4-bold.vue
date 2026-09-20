<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rm0w3acvs.css';
import '../../css/u/urak06bsx.css';
import '../../css/b/bid5r0rff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rm0w3acvs"/><path class="urak06bsx"/><path class="bid5r0rff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-4-bold" /></template>
