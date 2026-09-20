<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gxfzg3ajy.css';
import '../../css/x/xuod9ccmn.css';
import '../../css/z/znudi822w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gxfzg3ajy"/><path class="xuod9ccmn"/><path clip-rule="evenodd" class="znudi822w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:station2-filled" /></template>
