<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jk86jvbyg.css';
import '../../css/d/d7o9i2bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="jk86jvbyg"/><path class="d7o9i2bac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-stack-overflow" /></template>
