<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe91o3b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fe91o3b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ribbon" /></template>
