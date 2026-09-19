<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo3ctxiik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jo3ctxiik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:user" /></template>
