<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qpt0s3b7j.css';
import '../../css/s/seqtysokt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qpt0s3b7j"/><path clip-rule="evenodd" class="seqtysokt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-mask-n95-outline-24px" /></template>
