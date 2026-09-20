<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1dcc6b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1dcc6b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:text" /></template>
