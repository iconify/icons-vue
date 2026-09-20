<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjl1wbc5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pjl1wbc5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stone-arrowhead-right" /></template>
