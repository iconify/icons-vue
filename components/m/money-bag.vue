<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cu074ceyk.css';
import '../../css/m/mlsr-8b5c.css';
import '../../css/f/fe0kd1bhq.css';
import '../../css/y/ycltykv5o.css';
import '../../css/g/g-whbv2xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cu074ceyk"/><path class="mlsr-8b5c"/><path class="fe0kd1bhq"/><path class="ycltykv5o"/><path class="g-whbv2xh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:money-bag" /></template>
