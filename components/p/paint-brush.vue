<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzj_hkyox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="yzj_hkyox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:paint-brush" /></template>
