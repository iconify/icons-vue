<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l17g6jb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l17g6jb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star" /></template>
