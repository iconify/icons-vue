<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fpxg61buy.css';
import '../../css/w/wuqhv13kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="fpxg61buy"/><path class="wuqhv13kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:periscope" /></template>
