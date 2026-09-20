<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5t715gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="un5t715gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:square-with-square-dot" /></template>
