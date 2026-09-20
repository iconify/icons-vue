<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wjgebtbst.css';
import '../../css/m/myatxhbsg.css';
import '../../css/o/ohv-qybzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(1 3)" class="bi12bsetm"><path class="wjgebtbst"/><path class="myatxhbsg"/><rect class="ohv-qybzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:tags" /></template>
