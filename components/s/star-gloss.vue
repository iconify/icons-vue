<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb8h83o9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb8h83o9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:star-gloss" /></template>
