<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uspk1ccev.css';
import '../../css/o/ojdk2obcb.css';
import '../../css/o/o8x1mgcwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uspk1ccev"/><path class="ojdk2obcb"/><path class="o8x1mgcwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-diamond-solid" /></template>
