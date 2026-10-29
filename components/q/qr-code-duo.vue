<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lsfh3fvrg.css';
import '../../css/k/kucpkacrh.css';
import '../../css/k/kcag22w9s.css';
import '../../css/e/e1ojx1b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lsfh3fvrg"/><path class="kucpkacrh wm-a"/><path class="kcag22w9s"/><path class="e1ojx1b4k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:qr-code-duo" /></template>
