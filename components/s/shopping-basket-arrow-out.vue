<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w7poixe4p.css';
import '../../css/x/xjt4mmbhg.css';
import '../../css/y/ypms94bds.css';
import '../../css/h/hwt9rfbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w7poixe4p"/><path class="xjt4mmbhg"/><path class="ypms94bds"/><path class="hwt9rfbqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-basket-arrow-out" /></template>
