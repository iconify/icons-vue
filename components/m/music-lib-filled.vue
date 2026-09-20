<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s3xsa2b9s.css';
import '../../css/m/ml9jcl9xy.css';
import '../../css/y/yrdyw7tff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s3xsa2b9s"/><path clip-rule="evenodd" class="ml9jcl9xy"/><path class="yrdyw7tff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-lib-filled" /></template>
