<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uspk1ccev.css';
import '../../css/x/x0i1b1bbc.css';
import '../../css/s/suxtfubdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uspk1ccev"/><path class="x0i1b1bbc"/><path class="suxtfubdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-waves-solid" /></template>
