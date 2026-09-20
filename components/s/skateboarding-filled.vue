<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s1hme5bwb.css';
import '../../css/a/aimsb1rle.css';
import '../../css/q/q8mm7wb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s1hme5bwb"/><path class="aimsb1rle"/><path class="q8mm7wb4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:skateboarding-filled" /></template>
