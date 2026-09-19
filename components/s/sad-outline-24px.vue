<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xdqd7gb2y.css';
import '../../css/c/cgri5gdtm.css';
import '../../css/z/zso2mq8uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xdqd7gb2y"/><path clip-rule="evenodd" class="cgri5gdtm"/><path clip-rule="evenodd" class="zso2mq8uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sad-outline-24px" /></template>
