<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5pdp9b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j5pdp9b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:paper-plane" /></template>
