<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sd99jr24q.css';
import '../../css/n/n1f1wybsn.css';
import '../../css/s/slqajwrnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sd99jr24q"/><path clip-rule="evenodd" class="n1f1wybsn"/><path class="slqajwrnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:thermometer-digital-24px" /></template>
