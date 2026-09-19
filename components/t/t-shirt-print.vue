<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lbbc56xbn.css';
import '../../css/l/l35_cxukk.css';
import '../../css/p/pdx-mjvpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="lbbc56xbn"/><path clip-rule="evenodd" class="l35_cxukk"/><path class="pdx-mjvpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:t-shirt-print" /></template>
