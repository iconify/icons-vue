<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zw6nc7b0r.css';
import '../../css/o/onm8dobqc.css';
import '../../css/l/l3pucg3gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zw6nc7b0r"/><path class="onm8dobqc"/><path class="l3pucg3gf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:tag-sale-price" /></template>
