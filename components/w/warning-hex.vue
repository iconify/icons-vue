<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s3i77ouuq.css';
import '../../css/w/wrt-x_0am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(-1 -1)" class="bi12bsetm"><path class="s3i77ouuq"/><circle class="wrt-x_0am"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:warning-hex" /></template>
