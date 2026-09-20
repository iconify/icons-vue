<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nj3877h8f.css';
import '../../css/q/qus9g24-x.css';
import '../../css/b/bej489v3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nj3877h8f"/><path class="qus9g24-x"/><path class="bej489v3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:telescope-bold" /></template>
