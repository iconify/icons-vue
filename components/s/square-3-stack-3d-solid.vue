<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b75yygb-r.css';
import '../../css/i/iqu5xknni.css';
import '../../css/c/c5udlwswq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b75yygb-r"/><path class="iqu5xknni"/><path class="c5udlwswq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:square-3-stack-3d-solid" /></template>
