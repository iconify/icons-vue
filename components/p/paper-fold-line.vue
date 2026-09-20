<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yty-xqb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yty-xqb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:paper-fold-line" /></template>
