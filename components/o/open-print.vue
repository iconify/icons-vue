<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t933p5bjg.css';
import '../../css/n/nqew7yb0d.css';
import '../../css/c/c9_66s66x.css';
import '../../css/e/ev47d1-as.css';
import '../../css/y/yd4f5xb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="t933p5bjg"/><path class="nqew7yb0d"/><path class="c9_66s66x"/><path class="ev47d1-as"/><path class="yd4f5xb8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:open-print" /></template>
