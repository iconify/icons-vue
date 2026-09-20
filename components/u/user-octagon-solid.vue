<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uspk1ccev.css';
import '../../css/i/ivh9cup-t.css';
import '../../css/m/m43n7c4en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uspk1ccev"/><path class="ivh9cup-t"/><path class="m43n7c4en"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-octagon-solid" /></template>
