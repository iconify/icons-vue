<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u-_1ozgrf.css';
import '../../css/n/ni6lcyb1p.css';
import '../../css/x/xiieusbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u-_1ozgrf"/><path class="ni6lcyb1p"/><path class="xiieusbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-right-duotone" /></template>
