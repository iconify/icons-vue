<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/krek1qb5c.css';
import '../../css/k/kkqpawebx.css';
import '../../css/t/t2zt86a2w.css';
import '../../css/f/fb89hc7os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="krek1qb5c"/><path class="kkqpawebx"/><path class="t2zt86a2w"/><path class="fb89hc7os"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-desk-1" /></template>
