<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikhn5z8rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ikhn5z8rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:navigation-arrow-up" /></template>
