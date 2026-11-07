<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7_8g7q5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7_8g7q5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mouse-circle-outline" /></template>
