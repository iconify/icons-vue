<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4gjp9e0a.css';
import '../../css/x/xho5iubuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u4gjp9e0a"/><path class="xho5iubuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-x-20" /></template>
