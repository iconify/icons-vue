<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5zqrfbjz.css';
import '../../css/c/cjj93mxay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5zqrfbjz"/><path class="cjj93mxay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:skywork" /></template>
