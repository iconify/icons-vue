<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt0u4kb6g.css';
import '../../css/z/zsooyfbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt0u4kb6g"/><path class="zsooyfbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:pie-chart-alt-2" /></template>
