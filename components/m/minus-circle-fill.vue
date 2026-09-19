<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eerz48b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eerz48b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:minus-circle-fill" /></template>
