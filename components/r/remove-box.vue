<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycgn9rbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycgn9rbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:remove-box" /></template>
