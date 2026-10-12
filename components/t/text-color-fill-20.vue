<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq1rrzxbk.css';
import '../../css/y/yx-p2ubml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yq1rrzxbk"/><path class="yx-p2ubml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-color-fill-20" /></template>
