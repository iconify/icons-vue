<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1-x7w-ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d1-x7w-ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:refresh-right" /></template>
