<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ury1xy_5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ury1xy_5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:square-caret-left" /></template>
