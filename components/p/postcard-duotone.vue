<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o36z5zbfl.css';
import '../../css/a/am4cq56ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="o36z5zbfl"/><path class="am4cq56ck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:postcard-duotone" /></template>
