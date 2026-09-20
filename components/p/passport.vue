<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ai4b0kbev.css';
import '../../css/a/al0e8zqyv.css';
import '../../css/s/sdy0koojq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ai4b0kbev"/><path class="al0e8zqyv"/><path clip-rule="evenodd" class="sdy0koojq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:passport" /></template>
