<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emn7phbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="emn7phbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:medium-workmark" /></template>
