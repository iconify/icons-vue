<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/svav8jh5q.css';
import '../../css/d/dikszcc_o.css';
import '../../css/s/sjl2bfbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="svav8jh5q"/><path class="dikszcc_o wm-a"/><path class="sjl2bfbwr wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:party-popper" /></template>
