<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n2yxeu0zr.css';
import '../../css/p/pcl6sgbda.css';
import '../../css/a/actkwtdjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n2yxeu0zr"/><path class="pcl6sgbda"/><path clip-rule="evenodd" class="actkwtdjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:translate" /></template>
