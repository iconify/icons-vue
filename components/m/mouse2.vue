<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv_gh48en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zv_gh48en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:mouse2" /></template>
