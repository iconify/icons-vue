<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a-7jhj4gy.css';
import '../../css/z/zf57rje2z.css';
import '../../css/y/ygtvqmgmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a-7jhj4gy"/><path class="wm-shadow zf57rje2z"/><path class="ygtvqmgmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wifi-low-engrave" /></template>
