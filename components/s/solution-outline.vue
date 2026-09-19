<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn8lobeas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hn8lobeas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:solution-outline" /></template>
